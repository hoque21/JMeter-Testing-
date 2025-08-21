# API Testing with Apache JMeter

## 📌 Project Description
This repository contains **API testing for the Fintech API with Swagger** project using **Apache JMeter**.  
The goal of this assignment is to:
- Clone and run the Fintech API from the provided repository.
- Configure and execute API test plans in JMeter.
- Collect and analyze results for performance and correctness.
- Document the testing process with findings.

---

## ⚙️ Steps to Run the API using JMeter

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Katha-Sikdar/fintech-api-with-swagger.git
   cd fintech-api-with-swagger
Install & Open JMeter

Download Apache JMeter: https://jmeter.apache.org

Extract and open using:


Load the Test Plan

Open JMeter → File > Open

Select the test plan file:

Configure API Endpoints

Update the Server Name or IP and Port fields in HTTP Request Defaults to match your local API setup.

Ensure HTTP Header Manager includes required headers:

Content-Type: application/json

Authorization: Bearer <your-token> (if required)

Run the Test

Click the green Start button.

View results in:

View Results Tree

Summary Report

