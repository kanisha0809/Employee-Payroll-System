# Employee-Payroll-System
This project is a simple Employee Payroll System implemented in Java. It demonstrates the use of object-oriented programming (OOP) concepts such as inheritance, abstraction, and polymorphism.

# Overview
The Employee Payroll System allows users to manage full-time and part-time employees. It calculates the salary of each employee based on their employment type and displays their details. The system also provides functionality to add, remove, and display employees.

# Object-Oriented Programming (OOP) Concepts
This project emphasizes the following OOP concepts:

Inheritance: The FullTimeEmployee and PartTimeEmployee classes inherit from the Employee class, inheriting its properties and methods.
Abstraction: The Employee class is declared as an abstract class, and the calculateSalary() method is declared as abstract, providing a blueprint for subclasses to implement.
Polymorphism: The calculateSalary() method is overridden in the FullTimeEmployee and PartTimeEmployee classes to provide specific implementations.

# Classes
Employee: An abstract class representing an employee with common attributes like name and id. It contains an abstract method calculateSalary() to calculate the salary of the employee.

FullTimeEmployee: A subclass of Employee representing a full-time employee. It implements the calculateSalary() method to return the monthly salary.

PartTimeEmployee: A subclass of Employee representing a part-time employee. It implements the calculateSalary() method to return the salary based on hourly rate and hours worked.

PayrollSystem: A class to manage the list of employees. It provides methods to add, remove, and display employees.
