# JavaFX-EmployeeManagementSystem

### Employee Management System

Welcome to our Employee Management System application!

This application was built for a university project for the course Graphical User Interface - GUI, which is a Design Patterns and JavaFX course.

### The design patterns we used are:

Factory - The factory design pattern serves to generate specific Iterator objects based on different criteria (name, salary, employment date), encapsulating their creation in a centralized place and allowing flexibility to create new instances without exposing the creation logic directly.

Composite - The Composite design pattern is used to treat both Manager and Contributor uniformly as Employee objects, enabling the management system to handle and manipulate them interchangeably as part of the same hierarchy.

Visitor - The Visitor design pattern is used to facilitate the implementation of operations that vary based on the type of employee (Manager or Contributor) without modifying the core structure of the Employee Management System.

Iterator - The Iterator design pattern is employed to create specialized iterators, such as NameIterator and SalaryIterator, which enable controlled access to an employee collection while abstracting the underlying data structure and allowing iteration based on different criteria, such as name or salary.

Singelton - Singleton pattern is used to ensure that only one instance of the database connection is created and that the same instance is reused throughout the application.

MVC - MVC is used to separate concerns related to data management (the model), user interface presentation (the view), and user input handling and application logic (the controller), allowing for a more organized and maintainable structure for our employee management system.

### To run this application

Create a new mysql database for named "employee"
Set the correct username and password for this database inside Database/DatabaseConnection
