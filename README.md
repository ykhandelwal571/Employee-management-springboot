# Employee Management System

This is a simple **Employee Management System** project developed using **Spring Boot**, **Java 17**, and **Maven**. The project implements basic CRUD operations (Create, Read, Update, and Delete) for managing employee records and is connected to a **MySQL** database.

## Features

- Add new employees
- View employee details
- Update or modify employee information
- Delete employee records
- Backend powered by **Spring Boot**
- Database connectivity using **MySQL**

## Technologies Used

- **Java 17**
- **Spring Boot**
- **Maven**
- **MySQL**

## Prerequisites

- Java 17 installed
- Maven installed
- MySQL installed and configured
- An IDE like IntelliJ IDEA, Eclipse, or VS Code (optional)

## Setup Instructions

### 1. Clone the repository
git clone https://github.com/your-username/employee-management-system.git
cd employee-management-system

### 2. Configure MySQL Database

- Create a MySQL database named `employee_management` (or any name you prefer).
- Update the database configurations in the `application.properties` file:

  properties
  spring.datasource.url=jdbc:mysql://localhost:3306/employee_management
  spring.datasource.username=your_mysql_username
  spring.datasource.password=your_mysql_password
  spring.jpa.hibernate.ddl-auto=update
