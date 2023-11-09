# SQL CRUD Operations Backend Using Nodejs Express MSSQL Server tested By Postman

This repository contains the code for a Node.js backend application that performs CRUD (Create, Read, Update, Delete) operations on a SQL Server database. It is designed to provide a set of RESTful API endpoints for managing partner records in the database.

**Special Note:** This backend task was assigned by senior developers during my internship at CORTRACKER IT Private Limited.

## Why We Built

We created this project to demonstrate how to implement basic CRUD operations on a SQL Server database using Node.js and the mssql library. This project serves as an example for developers who are working on similar applications and need a starting point for handling database interactions.

## Usage

To use this project, follow these steps:

1. Clone the repository to your local machine.
2. Make sure you have Node.js and npm installed.
3. Configure the database connection details by updating the `config` object in the `app.js` file with your SQL Server credentials and database information.
4. Install the required npm packages by running `npm install` in the project directory.
5. Start the application by running `node app.js`.
6. You can use a tool like Postman or any HTTP client to send requests to the following endpoints:

   - `POST /get_partner/:id`: Retrieve partner information by ID.
   - `POST /get_partner`: Create a new partner record.
   - `POST /update_partner/:id`: Update an existing partner record.
   - `POST /update_status/:id`: Update the status of a partner record.

**Note:** In the `config` object, users need to provide their database and authentication details.

## Main Operations Involved

The main operations involved in this project include:

- **Retrieve Partner**: `POST /get_partner/:id` - Get partner information by ID.
- **Create Partner**: `POST /get_partner` - Create a new partner record.
- **Update Partner**: `POST /update_partner/:id` - Update an existing partner record.
- **Update Status**: `POST /update_status/:id` - Update the status of a partner record.

Make sure to customize the database connection details, and feel free to extend the project to suit your specific needs.

---

Feel free to explore and use this project as a reference for building similar applications that require CRUD operations on a SQL Server database.

Happy coding!
