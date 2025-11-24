# Task 9 – Load & Scalability Testing

## Objective
To evaluate how the e-commerce website performs under heavy traffic and ensure it can handle simultaneous user actions without failures or performance degradation.

## Scope of Load Testing
- Homepage loading under peak traffic  
- User login and signup  
- Product search and filters  
- Add to cart and checkout  
- API response time under load  
- Server behavior during traffic spikes  

## Approach
1. Use a load testing tool such as JMeter, LoadRunner, or Locust  
2. Simulate multiple virtual users performing real-time actions  
3. Gradually increase the virtual user count  
4. Measure system response time, throughput, and error rate  
5. Identify performance bottlenecks  
6. Record server resource usage (CPU, memory, bandwidth)

## Entry Criteria
- Stable build deployed  
- Test environment ready with monitoring tools  
- Load testing scripts prepared  

## Exit Criteria
- All load test scenarios executed  
- Response time within acceptable limits  
- No critical performance issues  
- Load test report completed  

## Test Case Details

### **Test Case ID:**  
`TC_Load_010`

### **Title:**  
**Test Website Scalability**

### **Preconditions:**  
Load testing tool installed (e.g., JMeter)

### **Test Steps:**
1. Simulate 100+ users performing key actions (login, search, checkout)  
2. Gradually increase the traffic load  
3. Record response time, throughput, and error count  
4. Monitor system performance during peak load  

### **Expected Results:**
- Website handles high traffic without crashing  
- Response time remains within acceptable limits  
- No major failures or timeouts  

## Conclusion
Load testing validates that the website can handle high user traffic and maintain performance during peak usage.
