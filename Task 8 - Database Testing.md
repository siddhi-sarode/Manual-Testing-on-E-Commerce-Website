# Database Testing – Task 8

## 📌 Task Description
- Test the accuracy of data storage and retrieval in the database.  
- Validate database performance under different load conditions.  
- Check data consistency and integrity during concurrent operations.  

---

## 📂 Test Case Details

### **Test Case ID:**  
`TC_Database_009`

### **Title:**  
**Validate Database Operations**

### **Preconditions**
- Access to the database and required SQL queries.  
- Application connected to the backend database must be functional.  

---

## 🧪 Test Steps

1. **Verify Data After User Registration**
   - Register a new user.
   - Run a SQL `SELECT` query to check if the user data is stored correctly.

2. **Test Data Integrity After Transactions**
   - Perform Insert, Update, and Delete operations.
   - Validate that data is modified correctly without corruption.

3. **Load Testing**
   - Simulate multiple concurrent users.
   - Perform continuous read/write operations.
   - Monitor database response time and stability.

---

## ✅ Expected Results
- Database must store and retrieve data accurately.  
- Transactions should reflect correct and consistent data.  
- Database should perform efficiently even under load.  

---

## 📘 Technologies Used
- SQL Database  
- Load Testing Tools (JMeter / Locust / Custom scripts)  
- Backend Application Interface  

---

## 📎 Author
Prepared for database testing documentation.
