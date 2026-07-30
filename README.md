# Solo Traveller 🌍

![Solo Traveller Banner](https://raw.githubusercontent.com/NKC27/solo-traveller-main/main/public/images/homepage.png)

A full-stack travel community platform built with **Node.js, Express.js, Sequelize ORM and MySQL**.

Solo Traveller allows users to create accounts, discover trips, share experiences and interact with a community of travellers.

![Node](https://img.shields.io/badge/Node.js-24-green)
![Express](https://img.shields.io/badge/Express.js-framework-black)
![MySQL](https://img.shields.io/badge/MySQL-database-blue)
![Deployment](https://img.shields.io/badge/Deployed-Render-success)

🚀 **Live Application**

https://solo-traveller-main.onrender.com/

📂 **GitHub Repository**

https://github.com/NKC27/solo-traveller-main

---

# Project Overview

Solo Traveller is a full-stack MVC web application designed to connect travellers through trip discovery, community posts and shared experiences.

The project demonstrates the development of a complete production-style application including:

- Backend API development
- Relational database architecture
- Authentication systems
- Session management
- MVC application structure
- Cloud deployment
- Production environment configuration

This project showcases my ability to:

✅ Design and structure full-stack applications
✅ Build secure authentication workflows
✅ Create relational database models
✅ Develop RESTful backend services
✅ Debug production deployment issues
✅ Configure cloud-hosted applications

---

# Screenshots

## Homepage

![Homepage](https://raw.githubusercontent.com/NKC27/solo-traveller-main/main/public/images/homepage.png)

## Create Trip

![Create Trip](https://raw.githubusercontent.com/NKC27/solo-traveller-main/main/public/images/create-trip.png)

## User Dashboard

![Dashboard](https://raw.githubusercontent.com/NKC27/solo-traveller-main/main/public/images/user-dashboard.png)

## Company Dashboard

![Company Dashboard](https://raw.githubusercontent.com/NKC27/solo-traveller-main/main/public/images/company-dashboard.png)

---

# Features

## Authentication

- User registration and login
- Password encryption using bcrypt
- Secure session-based authentication
- Protected user areas
- User profile management

## Travel Community

- Create and manage travel trips
- Share traveller posts
- Comment and interact with users
- Company accounts for travel providers
- Image upload functionality

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

## Cloud & Deployment

- Render - Application hosting
- Railway - Managed MySQL database
- GitHub - Version control

---

# Application Architecture

The application follows the MVC (Model View Controller) pattern.

```
MVC Architecture

Models
 |
 |-- Sequelize ORM
 |-- Database relationships
 |-- Data validation


Controllers
 |
 |-- Business logic
 |-- API handling
 |-- Request processing


Views
 |
 |-- Handlebars templates
 |-- Dynamic user interfaces
```

---

# Database Design

The application uses a relational MySQL database managed through Sequelize ORM.

Key concepts implemented:

- User models
- Trip relationships
- Post and comment relationships
- Session storage
- CRUD operations
- Database migrations and synchronisation

---

# Deployment Journey

The application was originally built for local development using MySQL.

To prepare the application for production deployment, several improvements were implemented:

### Environment Management

Database configuration was moved away from hardcoded values and into environment variables.

Implemented:

- Secure credential management
- Production database configuration
- Separate development and production environments

### Database Deployment

The local MySQL database was migrated to Railway MySQL.

Challenges solved:

- External database connectivity
- Sequelize configuration
- Railway networking issues
- Environment variable conflicts

### Cloud Deployment

The application was deployed using:

Frontend / Backend Hosting:

- Render

Database:

- Railway MySQL

Production deployment required debugging:

- Database connection failures
- Localhost references
- Private network restrictions
- Sequelize connection errors

---

# Developer Notes
This project involved migrating an application from local development to production deployment, resolving database connectivity issues between Render and Railway, configuring environment variables, and debugging Sequelize connection problems.

---

# Local Installation

Clone repository:

```bash
git clone https://github.com/NKC27/solo-traveller-main.git
```

Install dependencies:

```bash
npm install
```

Create environment variables:

```env
DB_NAME=your_database
DB_USER=your_username
DB_PASSWORD=your_password
DB_HOST=localhost
DB_PORT=3306
```

Start application:

```bash
npm start
```

Application runs locally:

```
http://localhost:3001
```

---

# Future Improvements

Potential enhancements:

- Automated testing with Jest
- Improved UI/UX design
- Advanced trip search
- Maps integration
- Traveller messaging
- Notifications
- CI/CD pipeline

---

# Developer

## Nick Clarke

Full Stack Developer | Learning & Development Designer

GitHub:

https://github.com/NKC27

---

⭐ This project demonstrates the journey from local development to a fully deployed production application, including backend architecture, database design, authentication and cloud deployment.
