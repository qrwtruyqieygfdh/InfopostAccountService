# infopost-account-service

The infopost-account-service is a RESTful service designed for managing users’ personal data, status, and transactions. It allows for account operations such as replenishment and debiting, with support for concurrent transactions on a single account.

## Features

- Store and manage personal user data
- Record account status and transactions
- Support for account replenishment and debiting
- Concurrent operations on accounts

## Built With

- Java 17
- Spring Boot (version 3.0.2)
- PostgreSQL
- Gradle (version 7.4)
- JUnit Jupiter (version 5.9.0), Mockito(version 5.9.0), SpringBootTest for testing
- Swagger (version 2.0.10) for API documentation
- Docker for containerization
- Flyway for database migration

## Getting Started

### Prerequisites

- Java 17
- Gradle
- Docker
- PostgreSQL

### Installation

1. Clone the repository:
   `bash
   git clone https://github.com/your-repo/infopost-account-service.git`

2. Navigate to the project directory:
   `bash
   cd infopost-account-service`

3. Build the project:
   `bash
   gradle build`

4. Run the application:
   `bash
   gradle bootRun`


## API Endpoints

You can view and interact with the API using Swagger UI. To open Swagger UI, navigate to:

http://localhost:8080/swagger-ui.html

Replace 8080 with the appropriate port if your application runs on a different one.

![image](https://github.com/qrwtruyqieygfdh/InfopostAccountService/assets/63457388/c3e9003b-6b0e-40ca-a30a-f70abfea8918)

## Entity Relationship Diagram

![image](https://github.com/qrwtruyqieygfdh/InfopostAccountService/assets/63457388/c65845f5-20ba-4ac9-8c0c-7137e02d0487)

## Authors

- **Ilya Kukharchuk** - *Java Software Engineer*

   - [LinkedIn Profile](https://linkedin.com/in/ilya-kukharchuk)
   - Email: iliakuharchuk@mail.ru

