<h1 align="center">🌟 Spring-Boot-Microservices-Banking-Application 🌟</h1>

## 📋 Table of Contents

- [🔍 About](#-about)
- [🏛️ Architecture](#-architecture)
- [🚀 Microservices](#-microservices)
- [🚀 Getting Started](#-getting-started)
- [📖 Documentation](#-documentation)
- [⌚ Future Enhancement](#-future-enhancement)

## 🔍 About
The Banking Application is built using a microservices architecture, incorporating the Spring Boot framework along with other Spring technologies such as Spring Data JPA, Spring Cloud, and Spring Security, alongside tools like Maven for dependency management. These technologies play a crucial role in establishing essential components like Service Registry, API Gateway, and more.  
Moreover, they enable us to develop independent microservices such as:
- **User service** for user management
- **Account service** for account generation and other related functionalities
- **Fund transfer service** for various transfer operations
- **Transaction service** for viewing transactions and facilitating withdrawals and deposits.

These technologies not only streamline development but also enhance scalability and maintainability, ensuring a robust and efficient banking system.

## 🏛️ Architecture

![Microservices Architecture](./images/architecture.png)

- **Service Registry:** The microservices use a discovery service for service registration and service discovery. This helps the microservices discover and communicate with other services without needing to hardcode the endpoints while communicating with other microservices.

- **API Gateway:** The API Gateway centralizes the API endpoints, providing a single entry point for all the endpoints. It also facilitates security by managing authorization and authentication for the application.

- **Database per Microservice:** Each microservice has its own dedicated database. For this application, we use MySQL for all the microservices. This isolation helps each service maintain its own data schemas and scale databases independently when required.

## 🚀 Microservices

- **👤 User Service:** This microservice provides functionalities for user management, including:
    - User registration, updating user details, and viewing user information.
    - Managing user authentication and authorization processes.

- **💼 Account Service:** The account microservice handles account-related APIs, enabling users to:
    - Modify account details and view all accounts linked to their profile.
    - Access transaction histories and support the account closure process.

- **💸 Fund Transfer Service:** This microservice handles fund transfer-related functionalities, such as:
    - Initiating fund transfers between accounts.
    - Viewing detailed fund transfer records and transaction details.

- **💳 Transactions Service:** The transaction microservice provides services related to:
    - Viewing transactions by account or transaction reference ID.
    - Making deposits or withdrawals from user accounts.

## 🚀 Getting Started

To get started, follow these steps to run the application locally:

1. Make sure you have **Java 17** installed. You can download it from the official Oracle website.
2. Choose an Integrated Development Environment (IDE) such as **Eclipse**, **Spring Tool Suite**, or **IntelliJ IDEA**, and configure it according to your preferences.
3. Clone the repository containing the microservices onto your local system using Git. Navigate to the directory where you cloned the repository.
4. Navigate to each microservice directory and run the application using your IDE or run specific commands depending on the build tool used (e.g., Maven or Gradle).
5. Set up **Keycloak** for authentication and authorization.
6. Ensure all required microservices and APIs are running to avoid any issues with the application workflow.

## 📖 Documentation

(Provide relevant documentation for each microservice and additional configuration here.)

## ⌚ Future Enhancement

We are planning several enhancements to improve the user experience and expand functionality, such as:

- **Notification System:** Implementing a robust notification system to keep users informed about important activities like transaction updates, account statements, and security alerts. This will integrate with email and SMS for timely communication.

- **Deposit and Investment Functionality:** Enabling users to manage savings and investments directly through the banking application. Features such as fixed deposits, recurring deposits, and investment portfolio tracking will empower users to make informed financial decisions.

- **And more…**

---

# Banking - Application
