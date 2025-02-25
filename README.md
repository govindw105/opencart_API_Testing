# OpenCart API Testing Project

## 📌 Project Overview
This project focuses on **API testing for the OpenCart web application**, ensuring the functionality and reliability of various API endpoints. The testing process includes manual testing using **Postman** and automation using **RestAssured (Java)** with **TestNG**.

## 🚀 Features Tested
- **User Authentication**  
  - Login / Logout API
  - Token-based authentication
- **Product Management**  
  - Add / Update / Delete products
  - Retrieve product details
- **Cart Operations**  
  - Add items to cart
  - Update cart items
  - Remove items from cart
- **Order Management**  
  - Place an order
  - Retrieve order details
  - Cancel order
- **Customer & Admin APIs**  
  - Fetch customer details
  - Admin functionalities testing

## 🛠️ Tech Stack & Tools
- **Java** (for automation)
- **RestAssured** (API testing framework)
- **TestNG** (test execution and reporting)
- **Postman** (manual testing and API validation)
- **Maven** (dependency management)
- **Jenkins** (CI/CD pipeline for API testing)
- **GitHub** (version control)

## 🔧 Setup & Installation
### Prerequisites
- Java (JDK 8+)
- Maven installed
- Postman (for manual testing)
- OpenCart API (accessible for testing)

### Steps to Clone and Run Tests
```sh
# Clone the repository
git clone https://github.com/your-username/opencart-api-testing.git
cd opencart-api-testing

# Install dependencies
mvn clean install

# Run API tests using TestNG
mvn test
```

## 📜 Test Execution & Reporting
- API test cases are executed using **TestNG**.
- Reports are generated under the `target/surefire-reports` directory.
- Jenkins integration for scheduled test execution.

## 🔗 Useful Links
- [OpenCart API Documentation](https://example.com/opencart-api-docs)
- [Postman API Collection](https://example.com/postman-collection)

## 📬 Contact
For any issues or contributions, feel free to open an issue or reach out! 🚀

