# Employee Management System

## Overview

The Employee Management System is a web application built to efficiently manage employee records. It leverages React for the front end, Node.js for the server-side logic, and MySQL for database management.

## Features

- **User Authentication**: Secure login and registration system.
- **Employee CRUD Operations**: Create, read, update, and delete employee records.
- **Role-Based Access Control**: Different permissions for users and admins.
- **Search and Filter**: Advanced search and filter options for employee records.
- **Responsive Design**: Adaptable to various devices and screen sizes.

## Technologies Used

- **Frontend**: React, React Router, Axios
- **Backend**: Node.js, Express.js
- **Database**: MySQL
- **Authentication**: JWT (JSON Web Tokens)
- **Password Hashing**: bcrypt

## Installation

### Prerequisites

- [Node.js](https://nodejs.org/) and npm installed
- MySQL server running

### Clone the Repository

git clone https://github.com/harstar7/Employee_Management_System_Full_Stack_Project.git
cd employee-management-system

## Backend Setup

1. Navigate to the backend directory:

    ```bash
    cd ../Server Side
    ```

2. Install dependencies:

    ```bash
    npm install
    ```

3. Create a `.env` file in the `backend` directory with the following content:

    ```env
    DB_HOST=your-database-host
    DB_USER=your-database-username
    DB_PASSWORD=your-database-password
    DB_NAME=your-database-name
    JWT_SECRET=your-jwt-secret
    ```

4. Start the server:

    ```bash
    npm start
    ```

## Frontend Setup

1. Navigate to the frontend directory:

    ```bash
    cd ../FrontEndFolder
    ```

2. Install dependencies:

    ```bash
    npm install
    ```

3. Create a `.env` file in the `frontend` directory with the following content:

    ```env
    REACT_APP_API_URL=http://localhost:5000
    ```

4. Start the React application:

    ```bash
    npm start
    ```


