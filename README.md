# Spring-Boot-Todo-App
## Overview
This Spring Boot Todo App provides a comprehensive platform for managing tasks with user authentication and a user-friendly interface. The project incorporates Java, Spring Boot, Spring Security, JPA, and Bootstrap to create a robust and visually appealing application.

## Features
### User Authentication
- Implemented secure user authentication using Spring Security.
- Configured in-memory user details manager with role-based access (USER, ADMIN).
- Passwords are encrypted using BCryptPasswordEncoder.
### Task Management
CRUD operations for managing todo items.
- Each todo item includes a description, target date, and completion status.
- Users can view their personalized todo lists.
### Data Persistence
- Utilized JPA (Java Persistence API) for seamless data storage and retrieval.
- Integrated an H2 in-memory database for easy setup and testing.
### Responsive Frontend
- Incorporated Bootstrap to create a responsive and visually appealing user interface.
- Ensured a consistent and enjoyable user experience across devices.
### Web Pages
- Welcome Page: A landing page welcoming users with a link to manage their todos.
- Todo List Page: Displays a table of todos with options to delete or update each item.
- Add Todo Page: Allows users to add new todos with a description and target date.
- Update Todo Page: Enables users to modify existing todos.

## Dependencies
- Spring Boot
- Spring Security
- Spring Data JPA
- H2 Database
- Bootstrap
  
## Usage
- Clone the repository: git clone https://github.com/VladNicolas/Spring-Boot-Todo-App.git
- Navigate to the project directory: cd spring-boot-todo-app
- Run the application: ./mvnw spring-boot:run
- Open your browser and go to http://localhost:8080
