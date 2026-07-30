# Solo Traveller 🌍

A full-stack travel community platform built with **Node.js, Express.js, Sequelize ORM and MySQL**, allowing travellers to create accounts, discover trips, share experiences and connect with a community of like-minded explorers.

🚀 **Live Application**

https://solo-traveller-main.onrender.com/

📂 **GitHub Repository**

https://github.com/NKC27/solo-traveller-main

---

# Overview

Solo Traveller is a full-stack web application designed to connect travellers through trip discovery, community posts and shared experiences.

The project demonstrates the development of a complete MVC-based application, including:

- Backend API development
- Relational database design
- User authentication
- Session management
- CRUD operations
- Cloud deployment
- Production environment configuration

This project showcases my ability to design, build, debug and deploy a complete web application from development through to production.

---

# Features

## Authentication & User Management

✅ User registration and login  
✅ Password encryption using bcrypt  
✅ Secure session-based authentication  
✅ Protected user areas  
✅ User profile management

---

## Travel Community Features

✅ Create and manage travel trips  
✅ Share traveller posts  
✅ Comment and interact with users  
✅ Company accounts for travel providers  
✅ Upload and manage user content

---

# Application Architecture

The application follows the **MVC (Model-View-Controller)** architectural pattern.

## Models

Responsible for database structure and relationships using Sequelize ORM.

Examples:

- Users
- Trips
- Posts
- Comments
- Sessions

---

## Views

Frontend rendering handled using:

- Handlebars.js
- Bootstrap
- HTML5
- CSS3
- JavaScript

---

## Controllers

Responsible for:

- Handling user requests
- Managing application logic
- Communicating with database models
- Returning responses to users

---

# Technology Stack

## Frontend

- HTML5
- CSS3
- JavaScript
- Handlebars.js
- Bootstrap

---

## Backend

- Node.js
- Express.js
- Sequelize ORM
- MySQL
- bcrypt
- Express Session
- Connect Session Sequelize

---

## Cloud & Deployment

- Render - Application Hosting
- Railway - MySQL Database Hosting
- GitHub - Version Control

---

# Database Architecture

The application uses a relational MySQL database managed through Sequelize ORM.

Database functionality includes:

- User authentication tables
- Trip management relationships
- Session storage
- Data validation
- One-to-many relationships
- CRUD operations

Sequelize provides an abstraction layer between the application and database, allowing models and relationships to be managed through JavaScript.

---

# Production Deployment

The original application was designed for local development using MySQL running on localhost.

To deploy successfully into production, I updated the application architecture to support cloud hosting.

## Deployment Improvements

Implemented:

✅ Environment variable configuration  
✅ External MySQL database connectivity  
✅ Production database credentials  
✅ Cloud hosting configuration  
✅ Secure separation between development and production settings

---

# Deployment Architecture

User
|
|
Render Hosting
(Node.js / Express Application)
|
|
Railway MySQL Database
|
|
Sequelize ORM
|
|
Application Models

---

# Development Challenges & Solutions

## Database Connectivity Issues

During deployment, the application initially failed because it was configured to connect to a local MySQL instance.

The production environment did not have access to:
127.0.0.1:3306

Solution:

- Updated Sequelize database configuration
- Added environment-based database settings
- Connected the application to Railway hosted MySQL
- Tested production database connectivity

---

## Environment Variable Management

The application originally relied on local `.env` configuration.

Production deployment required:

- Secure environment variables
- Database credentials managed through hosting platforms
- Removal of hard-coded configuration values

Implemented:

```javascript
process.env.MYSQL_URL

to allow cloud database connectivity.

Deployment Debugging

Resolved production deployment issues including:

Database connection failures
Railway private network restrictions
Incorrect environment variables
Sequelize connection errors
Cloud hosting configuration problems

This process strengthened my understanding of debugging applications outside of a local development environment.

Local Installation

Clone the repository:

git clone https://github.com/NKC27/solo-traveller-main.git

Navigate into the project:

cd solo-traveller-main

Install dependencies:

npm install

Create a .env file:

DB_NAME=your_database
DB_USER=your_username
DB_PASSWORD=your_password
DB_HOST=localhost
DB_PORT=3306

Start the application:

npm start

Application runs locally:

http://localhost:3001

Screenshots
Homepage

Future Improvements

Potential future enhancements:

Automated testing using Jest
Improved validation and error handling
Advanced trip search and filtering
Maps integration
User notifications
Expanded traveller profiles
CI/CD deployment workflows
API documentation using Swagger
Author
Nick Clarke

Full Stack Developer | Learning & Development Designer

GitHub:

https://github.com/NKC27

⭐ If you found this project interesting, feel free to explore the repository or try the live application.


---
```
