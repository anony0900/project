# Banking Application

A full-stack banking application with a Python/Flask backend and React frontend that provides secure banking services and account management capabilities.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technology Stack](#technology-stack)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Configuration](#configuration)
- [Running the Application](#running-the-application)
- [API Documentation](#api-documentation)
- [Security](#security)
- [Contributing](#contributing)

## Overview
This banking application provides a secure platform for users to manage their accounts, perform transactions, and handle financial operations through a modern web interface.

## Features

### User Management
- User registration and authentication
- Secure login/logout functionality
- Profile management
- Password reset capabilities

### Account Operations
- View account balances
- Transaction history
- Fund transfers between accounts
- Bill payments
- Account statements generation

### Security Features
- Secure authentication
- Data encryption
- Session management
- Input validation
- Protection against common web vulnerabilities

## Technology Stack

### Backend
- Python 3.x
- Flask framework
- run the file app.py

### Frontend
- React.js
- Material-UI components
- React Router for navigation
- Webpack for bundling

## Installation

### Backend Setup
1. Create a Python virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

2. Install Dependencies
cd backend
pip install -r requirements.txt

3. Configure the database:
change the password from default to your own MySQL Password.
run python create_db.py

## Frontend Setup
1. Install Node.js dependencies:
cd frontend
npm install

## Running the Application
### Start the Backend Server
cd backend
python app.py
The backend server will start at http://localhost:5000

### Start the Frontend Development Server
cd frontend
npm start
The frontend application will start at http://localhost:3000

### Error Handling

The application includes comprehensive error handling for:

Invalid inputs
Authentication failures
Database errors
Network issues
Server errors

### Maintenance
Regular security updates
Database backups
Performance monitoring
Error logging

## Backend
The backend is built with Python/Flask and provides the API endpoints for the application. It includes:
- Database management and queries
- API endpoints
- Data validation

## Frontend
The frontend is a React-based web application that provides the user interface. It includes:
- User registration and account management
- View and account pages
- Form handling and submission

## Setup
1. Backend setup:
   - Set up a Python virtual environment
   - Install dependencies
   - Configure the database
   - Run the application

2. Frontend setup:
   - Install Node.js dependencies
   - Configure environment variables
   - Run the React development server

## Project Structure
- `/backend` - Contains the Flask backend application
- `/frontend` - Contains the React frontend application

# Screenshot of Banking Application

## Screenshot of Login Page 
<img src='/images/Dashboard.jpeg' alt='error'>

## Screenshot of Sign Up Form Page 
![SignUpForm](https://github.com/user-attachments/assets/166cd1b4-7b96-4add-9257-3912891d0f38)

## Screenshot of Records
![View Records](https://github.com/user-attachments/assets/6c5c20d8-9321-4b56-b9f9-ef030daa1c7e)


