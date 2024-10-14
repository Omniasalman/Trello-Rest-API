# Trello-Rest-API
# Manual And Automation API Testing Project 
This project involves testing the [Trello Rest API](https://developer.atlassian.com/cloud/trello/rest/api-group-actions/#api-group-actions) using various tools and technologies including **Postman**, **Newan**, **Jenkins**, and **RestAssured**. The purpose is to automate the testing of API endpoints to ensure their reliability and performance.

[![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java&logoColor=white)](https://www.oracle.com/java/)
[![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)](https://www.postman.com/)
[![Newman](https://img.shields.io/badge/Newman-00BFFF?style=for-the-badge&logoColor=white)](https://github.com/postmanlabs/newman)

## Tools & Technologies
- **Postman**: Used for manual API testing, sending requests, and verifying responses.
- **Newman**: Command-line tool to run Postman collections for API testing automation.
### 1. Postman Testing

Postman is used to manually test the Trello Rest API. The test scenarios cover the following endpoints:
- **Post /Create Board - List - Card - Checklist 
- **GET /The create Board Id , and used it for the next creation step
- **PUT / Update an existing "Board - List - Card - Checklist " by ID.
- **DELETE /{id}**: Delete a "Board - List - Card - Checklist Board - List - Card - Checklist " by ID.

Assertions in Postman check:
- **Status codes** (200, 201, 404, etc.).
- **Response body content** to verify valid product data.
- **Response time** to ensure optimal API performance.

### 2. Newman Automation

**Newman** is used to run Postman collections from the command line or as part of a CI/CD pipeline. This makes it easy to automate tests across different environments.
