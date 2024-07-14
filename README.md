# CRUD Employee Management App

## Description

This is a full-stack CRUD application designed for managing employee details. It features a React frontend and a Node.js backend with Express and MongoDB. The app allows users to perform basic CRUD operations: create, read, update, and delete employee records. The project also includes an API for interacting with the employee data and a user-friendly interface for managing employee records.

## Features

- **Add Employee**: Form to add new employee records.
- **View Employees**: Table view of all employees with options to update or delete records.
- **Update Employee**: Form to update existing employee records.
- **Delete Employee**: Option to delete employee records.
- **Backend API**: RESTful API endpoints for CRUD operations.
- **Frontend**: Built with React and Material-UI for a responsive and modern user experience.
- **Postman**: Used for testing API endpoints during development.

## Technologies Used

- **Frontend**: React, Material-UI, React Router
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **API Testing**: Postman

## Installation

### Frontend

1. Navigate to the frontend directory:
   cd frontend
2.Install the dependencies:
npm install
3.Start the React development server:
npm start


###Backend
1.Navigate to the backend directory:
cd backend
2.Install the dependencies:
npm install
3.run the code
nodemon ./index.js

###API Endpoints
POST /add: Add a new employee record.
GET /view: Retrieve all employee records.
PUT /update/: Update an employee record by ID.
DELETE /remove/: Delete an employee record by ID.
###Frontend Routes
/: Add Employee (Form for adding new employees)
/a: View Employees (Table displaying employee records)
###Postman Collection
The Postman collection for testing API endpoints is included in the Postman directory.





Contact
For any questions or suggestions, you can reach me at wishnukv2349@gmail.com



Summary
Here’s a summary of what each file does and why it’s important for the repo:

employee.js: Mongoose schema and model for the employee collection.
connection.js: Connects the backend application to the MongoDB database.
index.js: Main backend server file with API routes for CRUD operations.
Add.jsx: React component for adding and updating employee records.
Navbar.jsx: Navigation bar for the frontend app.
View.jsx: React component for viewing, updating, and deleting employee records.
App.jsx: Main React component that sets up routes and includes the Navbar.
index.jsx: Entry point for the React app with routing setup.
Feel free to adjust any of the content as necessary for your specific project or personal preferences.
