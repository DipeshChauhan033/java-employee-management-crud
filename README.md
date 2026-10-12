# Java Employee Management CRUD

A Java web application for managing employee records using **Java Servlets, JSP, JDBC, and MySQL**. The project follows the MVC architecture and a layered approach using DTO, DAO, and Service layers to keep the code organized and maintainable.

## Overview

This project demonstrates how a Java web application handles employee data from the user interface to the database using a structured backend flow.

## Technologies Used

* **Java** – Core application logic
* **Servlets** – Handle HTTP requests and responses
* **JSP** – Display dynamic web pages
* **JDBC** – Connect Java with the database
* **MySQL** – Store employee records
* **Apache Tomcat** – Run the web application
* **MVC Architecture** – Separate application responsibilities

## Architecture

```text
User
  |
  v
JSP (View)
  |
  v
Servlet (Controller)
  |
  v
Service Layer
  |
  v
DAO Layer
  |
  v
JDBC
  |
  v
MySQL Database
```

### Project Layers

* **JSP:** Provides the user interface for employee management.
* **Servlet:** Handles incoming requests and controls application flow.
* **DTO (Data Transfer Object):** Transfers employee data between application layers.
* **Service Layer:** Handles business logic.
* **DAO (Data Access Object):** Performs database operations.
* **JDBC:** Establishes database connectivity and executes SQL queries.

## Features

* Add new employee records.
* View employee details.
* Update existing employee information.
* Delete employee records.
* Store and retrieve employee data using MySQL.
* Separate responsibilities using a layered architecture.

## CRUD Operations

| Operation | Description                 |
| --------- | --------------------------- |
| Create    | Add a new employee          |
| Read      | View employee details       |
| Update    | Modify employee information |
| Delete    | Remove an employee record   |

## Application Flow

1. The user performs an action through a JSP page.
2. The Servlet receives and processes the request.
3. The Service layer handles the application logic.
4. The DAO layer interacts with the database using JDBC.
5. The result is returned to the Servlet.
6. The Servlet forwards the response to the appropriate JSP page.

## Learning Objectives

This project helps in understanding:

* Java web application development.
* Servlet and JSP integration.
* JDBC database connectivity.
* MVC architecture and separation of concerns.
* DTO, DAO, and Service layer responsibilities.
* End-to-end CRUD operations.
* The request-response lifecycle in Java web applications.

*This project is developed for learning and practicing Java enterprise application fundamentals.*
