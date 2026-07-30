# Solo Traveller 🌍

A full-stack travel community platform built with **Node.js, Express.js, Sequelize ORM and MySQL**, designed to connect travellers through trip discovery, community interaction and shared experiences.

🚀 **Live Application**

https://solo-traveller-main.onrender.com/

📂 **GitHub Repository**

https://github.com/NKC27/solo-traveller-main

---

# Project Overview

Solo Traveller is a full-stack web application that allows users to create accounts, discover trips, share travel experiences and interact with a community of travellers.

The project demonstrates the development of a complete production-style application using a traditional MVC architecture, including:

- Backend API development
- Relational database modelling
- Authentication workflows
- Session management
- CRUD operations
- Cloud deployment
- Production environment configuration

The application was originally developed for local development and later migrated to a production cloud environment using **Render and Railway**, requiring additional configuration, debugging and deployment improvements.

---

# Key Features

## Authentication & User Management

✅ User registration and login  
✅ Password encryption using bcrypt  
✅ Session-based authentication  
✅ Secure user sessions stored using Sequelize  
✅ Protected user functionality  
✅ User profile management

---

## Travel Community Features

✅ Create and manage travel trips  
✅ Traveller posts and comments  
✅ Company accounts for travel providers  
✅ User generated content  
✅ Image upload functionality  
✅ Trip management workflows

---

# Technical Architecture

The application follows an MVC (Model-View-Controller) architecture to separate responsibilities and create a maintainable codebase.

## Model Layer

Responsible for:

- Database structure
- Data relationships
- Sequelize ORM models
- MySQL communication

Examples:

- User models
- Trip models
- Comment models
- Session models

---

## View Layer

Built using:

- Handlebars.js
- HTML5
- CSS3
- Bootstrap

Responsible for rendering dynamic pages and user interfaces.

---

## Controller Layer

Responsible for:

- Handling user requests
- Application logic
- Database interactions
- Returning responses

This separation allows the application to remain organised and easier to maintain.

---

# Technology Stack

## Frontend

- HTML5
- CSS3
- JavaScript
- Handlebars.js
- Bootstrap

## Backend

- Node.js
- Express.js
- Sequelize ORM
- MySQL
- bcrypt
- Express Session
- Connect Session Sequelize

## Cloud & Development Tools

- Git & GitHub
- Render
- Railway MySQL
- npm
- Environment Variables
- AWS S3 image storage

---

# Database Architecture

The application uses a relational MySQL database managed through Sequelize ORM.

Key concepts implemented:

- Relational database modelling
- Database migrations/schema design
- Model relationships
- Data validation
- Session persistence
- CRUD operations

The database structure supports relationships between:

- Users
- Trips
- Comments
- Companies
- Sessions

---

# Production Deployment

The application was deployed using a cloud-based architecture:

## Application Hosting

**Render**

The Node.js Express application runs as a production web service.

## Database Hosting

**Railway MySQL**

The MySQL database is hosted separately and securely connected using environment variables.

## Version Control

**GitHub**

Source control, version management and deployment integration.

---

# Deployment Challenges & Solutions

Moving the application from local development to production required solving several real-world deployment issues.

## Database Connectivity

### Challenge

The original application was configured for local MySQL:

This worked locally but failed when deployed because the production environment did not have access to a local database instance.

### Solution

Updated the Sequelize configuration to support environment-based database connections:

- Local development database support
- Hosted MySQL connection support
- Production environment variables
- External database authentication

---

## Environment Management

### Challenge

The application required different database configurations depending on the environment.

### Solution

Implemented environment variables to securely manage:

- Database credentials
- Database host
- Database port
- Production configuration

Sensitive information was removed from the codebase and managed through deployment environment settings.

---

## Cloud Deployment Debugging

During deployment I diagnosed and resolved issues including:

- Localhost database connection failures
- Railway private network connection errors
- Incorrect production database host configuration
- Environment variable conflicts
- Sequelize connection failures

This involved analysing deployment logs, debugging connection errors and updating configuration until the application successfully deployed.

---

# Authentication Implementation

Authentication was implemented using:

- bcrypt password hashing
- Express sessions
- Sequelize session storage

User credentials are securely stored rather than using plain text passwords.

The authentication workflow includes:

1. User registration
2. Password hashing
3. Database storage
4. Login validation
5. Session creation
6. Protected routes

---

# Screenshots

## Homepage

![Homepage](https://raw.githubusercontent.com/NKC27/solo-traveller-main/main/public/images/homepage.png)

## Trip Management

![Trips](https://raw.githubusercontent.com/NKC27/solo-traveller-main/main/public/images/trips.png)

## User Dashboard

![Dashboard](https://raw.githubusercontent.com/NKC27/solo-traveller-main/main/public/images/company-dashboard.png)

## Community Features

![Comments](https://raw.githubusercontent.com/NKC27/solo-traveller-main/main/public/images/comments.png)

---

# Future Improvements

Potential enhancements:

- Add automated testing with Jest
- Improve frontend experience with React
- Add advanced search and filtering
- Add maps integration
- Improve accessibility
- Add CI/CD deployment workflows
- Containerise application using Docker

---

# What I Learned

Through building and deploying this application I gained practical experience in:

✅ Designing full-stack MVC applications  
✅ Building RESTful backend services  
✅ Working with relational databases  
✅ Implementing authentication systems  
✅ Managing production environment variables  
✅ Debugging cloud deployment issues  
✅ Connecting applications to external services  
✅ Deploying applications using modern cloud platforms

---

# Author

**Nick Clarke**

Full Stack Developer | Learning & Development Designer

GitHub:

https://github.com/NKC27

---

⭐ Feel free to explore the application or review the source code.
