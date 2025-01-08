# CS-GY 6083: Principles of Database Systems - Database Management System for Order and Donation Handling

This repository contains the implementation of **Database Management System for Order and Donation Handling** for the course **Principles of Database Systems (CS-GY 6083)** at **NYU Tandon School of Engineering**.

## Overview

The project involves building a web application with features like secure login, user session handling, role-based access, and comprehensive order and inventory management. It uses a robust schema design to ensure integrity and smooth operation of the database.

## Features

- **User Authentication:** Secure login, registration, and session management.
- **Role-Based Access Control:** Different views and actions for staff, volunteers, clients, and donors.
- **Order Management:** Features to create, prepare, and track orders.
- **Donation Handling:** System to record donations and manage inventory.
- **Ranking System:** Track and rank volunteers based on delivery counts.
- **Dynamic Views:** Personalized views for users based on their roles.
- **Security:** Passwords hashed using SHA-256 with salted hashes.

## Technologies Used

### Backend
- **Python (Flask Framework):** Lightweight, easy to integrate with SQL databases.
  
### Frontend
- **HTML & CSS:** For static pages and styling.
- **JavaScript:** To add interactivity.

### Database
- **MySQL:** Relational database for structured storage and efficient querying.

### Security
- **Password Hashing:** Secure storage of sensitive information using cryptographic hashing.

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/WelcomeHome.git
   cd WelcomeHome
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Configure the database:
   - Create the database schema using the provided SQL scripts.
   - Update the database connection details in the configuration file.

4. Run the application:
   ```bash
   python3 app.py
   ```

5. Access the application at `http://localhost:5000`.

## Schema Design

- Includes tables for users, roles, items, orders, donations, and more.
- Constraints and triggers are used to enforce role compatibility and data integrity.

## Key Features

### Login & Registration
- Secure authentication with hashed passwords.
- Form validations to ensure data correctness.

### Role-Based Features
- **Staff:** Manage donations, create orders, and supervise tasks.
- **Volunteers:** Deliver orders and track tasks.
- **Clients & Donors:** Access order and donation details.

### Order & Inventory Management
- Create and track orders dynamically.
- Maintain inventory details including locations and item descriptions.

### Ranking System
- Rank volunteers based on delivery performance.

### Security
- Role-based access control.
- Protection against SQL injection using prepared statements.

## Challenges & Lessons Learned

### Challenges
- Managing role compatibility constraints.
- Implementing secure password hashing.
- Designing dynamic views for multiple user roles.

### Lessons Learned
- Importance of schema planning.
- Secure development practices.
- Effective team collaboration.

## Team Members

- **Khwaab Thareja** (kt3180)
- **Ansh Harjai** (ah7163)
- **Neeha Rathna Janjanam** (nj2330)

### Faculty Advisor
- **Prof. Phyllis Frankl**
