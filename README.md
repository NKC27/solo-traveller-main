# Solo Traveller 🌍

A full-stack travel community platform built with **Node.js, Express.js, Sequelize ORM and MySQL**, allowing travellers to create accounts, discover trips, share experiences and interact with a community of like-minded explorers.

🚀 **Live Application:**
https://solo-traveller-main.onrender.com/

📂 **GitHub Repository:**
https://github.com/NKC27/solo-traveller-main

---

# Overview

Solo Traveller is a full-stack web application designed to connect travellers through trip discovery, community posts and shared experiences.

The application demonstrates the development of a complete MVC-based architecture, including a RESTful backend API, relational database design, authentication, session management and cloud deployment.

This project showcases my ability to:

- Design and structure a full-stack application
- Build secure user authentication workflows
- Create and manage relational database models
- Develop backend APIs using Express.js
- Implement MVC architecture
- Deploy and configure production applications using cloud platforms

---

# Features

## User Authentication

✅ User registration and login
✅ Secure password hashing using bcrypt
✅ Session-based authentication
✅ Protected user areas
✅ User profile management

## Travel Community

✅ Create and manage travel trips
✅ Share traveller posts
✅ Comment and interact with other users
✅ Company accounts for travel providers
✅ Upload and manage user content

## Application Architecture

✅ MVC design pattern
✅ RESTful API routes
✅ Sequelize ORM database management
✅ MySQL relational database
✅ Environment-based configuration
✅ Production cloud deployment

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

- Render (Application Hosting)
- Railway (MySQL Database Hosting)
- GitHub (Version Control)

---

# Database Design

The application uses a relational MySQL database managed through Sequelize ORM.

Key database concepts implemented:

- User authentication models
- Trip management relationships
- Session storage
- Data validation
- CRUD operations

---

# Local Installation

Clone the repository:

```bash
git clone https://github.com/NKC27/solo-traveller-main.git
```

Navigate into the project:

```bash
cd solo-traveller-main
```

Install dependencies:

```bash
npm install
```

Create a `.env` file:

```env
DB_NAME=your_database
DB_USER=your_username
DB_PASSWORD=your_password
DB_HOST=localhost
DB_PORT=3306
```

Start the application:

```bash
npm start
```

The application will run locally at:

```
http://localhost:3001
```

---

# Deployment

The application is deployed using a production cloud architecture:

**Frontend / Backend Hosting**

- Render

**Database Hosting**

- Railway MySQL

Deployment configuration includes:

- Production environment variables
- External database connectivity
- Secure credential management
- Cloud-hosted application services

---

# Development Challenges & Solutions

During deployment, the application required production configuration changes including:

### Database Connectivity

The original application was configured for local MySQL development.

I updated the database connection handling to support hosted environments by:

- Moving database configuration into environment variables
- Configuring external MySQL connectivity
- Debugging Sequelize connection errors
- Separating development and production configuration

### Deployment Troubleshooting

Resolved issues including:

- Localhost database connection failures
- Railway private network access restrictions
- Environment variable conflicts
- Production Sequelize configuration

---

# Future Improvements

Potential future enhancements:

- Add automated testing with Jest
- Improve UI/UX design
- Add advanced trip search and filtering
- Implement user notifications
- Add maps integration
- Expand traveller profiles
- Add CI/CD deployment workflows

---

# Screenshots

```markdown
![Homepage](https://github.com/NKC27/solo-traveller-main/public/images/homepage.png)
```

---

# Author

**Nick Clarke**

Full Stack Developer | Learning & Development Designer

GitHub:
https://github.com/NKC27

---

⭐ If you found this project interesting, feel free to explore the repository or try the live application.
