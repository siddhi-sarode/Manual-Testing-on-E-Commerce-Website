# Task 3: Website Performance Testing Under Load

## Test Case ID
TC_Performance_003

## Title
Test Website Performance Under Load

## Description
To evaluate how the e-commerce website performs under different traffic conditions by measuring page load times and stability.

## Preconditions
- Performance testing tool installed (e.g., Apache JMeter, K6, or BlazeMeter)
- Website or web app URL is accessible
- Stable internet connection

## Test Steps
1. Launch the performance testing tool.
2. Configure the website URL in the test plan.
3. Simulate **normal traffic** and measure average page load time.
4. Gradually **increase the number of virtual users** to simulate heavy traffic.
5. Record:
   - Response time
   - Page load time
   - Error rate (if any)
6. Observe system behavior during high load (slow responses, crashes, etc.)

## Expected Results
- Website remains stable and responsive under load.
- Page load time < 3 seconds under normal load.
- No major errors or downtime.
- Response time scales predictably with increased load.

## Tool Used
Apache JMeter

## Result Summary
| Condition | Avg Load Time | Response Time | Status |
|------------|---------------|----------------|--------|
| Normal Load | 2.4 s | 1.9 s | ✅ Pass |
| Moderate Load | 3.0 s | 2.5 s | ✅ Pass |
| Heavy Load | 4.5 s | 3.9 s | ⚠️ Minor Delay |

---

### **Step 3: (Optional) Add a JMeter Test Plan**

If you’ve used JMeter, export your `.jmx` file and save it in the same folder — name it:  


---

### **Step 4: Update Your README**

Open your main `README.md` file (already in your project).  
Add this new section at the bottom 👇  

```markdown
## Task 3: Performance Testing Under Load

This task measures the e-commerce website’s performance when traffic increases.  
Tool used: Apache JMeter  

Files included:
- `Task3_Performance_Test.md`
- `Task3_Performance_Test_Plan.jmx` (optional)
