Problem Statement: Employee Management System (CRUD) with MySQL
Create a Spring Boot Employee Management System that performs basic CRUD operations (Create, Read, Update, Delete) on employee data. The system will expose a REST API for interacting with a MySQL database.
Requirements:
Create an Employee
The system should allow the creation of a new employee with the following details:
firstName (String)
lastName (String)
email (String)
Read Employee Data
Get all employees: A GET endpoint to retrieve the list of all employees.
Get employee by ID: A GET endpoint to retrieve a single employee’s details using their unique ID.
Update Employee Data
The system should allow updating an existing employee’s information based on their unique ID.
Delete Employee
The system should allow the deletion of an employee from the system based on their unique ID.
REST API Endpoints:
GET /api/employees - Retrieve a list of all employees.
GET /api/employees/{id} - Retrieve an employee’s details by their ID.
POST /api/employees - Create a new employee.
PUT /api/employees/{id} - Update an employee’s information by their ID.
DELETE /api/employees/{id} - Delete an employee by their ID.
