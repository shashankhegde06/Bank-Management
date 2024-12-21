# Bank Management System

Welcome to the Bank Management System repository built using Spring Boot! This project is designed to provide a foundation for managing banking operations using modern web technologies.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Database Schema](#database-schema)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)

## Introduction

The Bank Management System is a web-based application developed using Spring Boot that aims to streamline various banking operations. This system offers features to manage customer accounts and perform transactions.

## Features

- **User-Friendly Web Interface**: Designed for customers with a frontend crafted using Angular. The frontend repository can be found on GitHub.
- **Authentication and Authorization**: Robust user authentication and authorization mechanisms to ensure secure and controlled access.
- **Multi-Account Support**: Users can create up to three separate accounts to cater to various financial needs.
- **Comprehensive Account Details**: Access detailed account information, including balance summaries, card numbers, CVV numbers, and more.
- **Efficient Transaction Handling**: API endpoints for seamless fund transfers between accounts, ensuring efficient transaction processing.

## Installation

To run the Bank Management System locally, you will need:

- Java 11 or higher
- Maven
- PostgreSQL

### Steps to Install

1. Clone this repository:
   ```bash
   git clone [https://github.com/shashankhegde06/Bank-Management.git]
   ```
2. Edit the database configurations in the `application.properties` file.
3. Navigate to the project directory:
   ```bash
   cd bank-management
   ```
4. Build and run the application using Maven:
   ```bash
   mvn spring-boot:run
   ```
5. Access the application in your web browser at:
   ```
   http://localhost:8080
   ```
6. Explore API documentation at:
   ```
   http://localhost:8080/swagger-ui.html
   ```

## Usage

### Customer Actions

- **Account Creation**: Create multiple accounts tailored to financial needs.
- **View Account Details**: Access detailed information about balances and transactions.

### Transaction Operations

- **Deposit Funds**: Use the `/transaction/deposit` endpoint to deposit funds securely.
- **Withdraw Funds**: Use the `/transaction/withdraw` endpoint for seamless and accurate withdrawals.

## Database Schema

Details of the database schema are available in the project repository. PostgreSQL is used as the database for this application.

## Technologies Used

- Java
- Spring Boot
- Spring Security
- JSON Web Token (JWT)
- Spring Data JPA
- Lombok
- PostgreSQL
- Maven
- Swagger
- Docker

## Contributing

Contributions to the Bank Management System project are welcome! Follow these steps to contribute:

1. Fork the repository.
2. Create a new branch for your feature.
3. Commit your changes.
4. Push the branch.
5. Open a Pull Request explaining your changes.

---

We appreciate your contributions and efforts to make this project better!
