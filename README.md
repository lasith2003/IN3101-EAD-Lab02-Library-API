# Library Management REST API

A RESTful Library Management API developed using Spring Boot, Java, and MySQL as part of the IN3101 – Enterprise Application Development (EAD) Lab 02.

## Technologies Used

- Java 21
- Spring Boot 4.1.2
- Maven
- Spring Data JPA
- MySQL
- Bean Validation
- Swagger / OpenAPI
- Postman

## Features

- Create a new book
- Retrieve all books
- Retrieve a book by ID
- Update book details
- Delete a book
- Input validation
- REST API documentation using Swagger UI

## API Endpoints

| Method | Endpoint | Description |
|---|---|---|
| GET | `/api/books` | Get all books |
| GET | `/api/books/{id}` | Get a book by ID |
| POST | `/api/books` | Create a new book |
| PUT | `/api/books/{id}` | Update a book |
| DELETE | `/api/books/{id}` | Delete a book |

## Database Configuration

This project uses MySQL with a database named `library_db`.

Configure your local database credentials in:

`src/main/resources/application.properties`

Do not commit database passwords or other sensitive credentials to GitHub.

## Running the Project

1. Clone the repository:

   ```bash
   git clone https://github.com/lasith2003/IN3101-EAD-Lab02-Library-API.git
   ```

2. Open the project in your IDE.

3. Configure your MySQL database credentials.

4. Run the application:

   ```bash
   ./mvnw spring-boot:run
   ```

   On Windows:

   ```powershell
   .\mvnw.cmd spring-boot:run
   ```

5. The application will run at:

   `http://localhost:8080`

## Swagger Documentation

After starting the application, access the API documentation at:

`http://localhost:8080/swagger-ui.html`

## Author

**Name:** S.K.L.Undulanga

**Index Number:** 235114A

**Module:** IN3101 – Enterprise Application Development
