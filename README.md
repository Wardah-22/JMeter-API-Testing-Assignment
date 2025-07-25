# Assignment 2 - JMeter API Testing

## 📋 Description
This repository contains a complete JMeter test plan for testing a REST API using CRUD operations. It covers thread groups, samplers, assertions, listeners, and CSV data-driven testing.

## ✅ Objectives Covered

- ✅ Created Thread Group, Samplers, and Listeners for `GET`, `POST`, `PUT`, and `DELETE`
- ✅ Created a full CRUD chain (POST → GET → PATCH → DELETE → GET again to verify deletion)
- ✅ Implemented dynamic data update using PATCH request
- ✅ Read data from a CSV file and used it to make POST & GET requests
- ✅ Verified that response values match the original CSV input

## 🛠️ How to Use

1. Open the JMeter `.jmx` file in Apache JMeter.
2. Ensure the test plan includes:
   - CSV Data Set Config (linked to `users.csv`)
   - HTTP Samplers for all endpoints
   - JSON Assertions for response validation
3. Run the test plan.
4. View results using "View Results Tree" and "Summary Report".



## 📝 CSV Format

| username         | userjob     |
|------------------|-------------|
| john.doe         | engineer    |
| jane.smith       | designer    |

Make sure your API accepts this format.

## 👤 Author

Wardah Sattar  
BS Software Engineering  


