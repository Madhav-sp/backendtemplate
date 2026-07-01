# Backend Starter Template

A production-ready backend starter built with **Node.js**, **Express**, and **MongoDB** to help you kickstart backend development without repeatedly configuring common services.

Instead of setting up authentication, database connections, file uploads, middleware, and project structure from scratch for every project, this template provides a clean, scalable foundation so you can focus on building your application's business logic.

---

# Features

* Clean and scalable folder structure
* Express.js server setup
* MongoDB integration with Mongoose
* JWT-based authentication
* Cloudinary integration for image uploads
* Multer file upload configuration
* Environment-based configuration
* Centralized error handling
* Async request handling
* Request validation middleware
* Cookie parsing and CORS configuration
* API response and error utility classes
* Production-ready project structure

---

# Tech Stack

* Node.js
* Express.js
* MongoDB
* Mongoose
* JWT
* Cloudinary
* Multer
* bcrypt
* dotenv

---

# Project Structure

```text
src/
├── controllers/
├── models/
├── routes/
├── middlewares/
├── services/
├── utils/
├── db/
├── constants/
├── app.js
└── index.js
```

---

# Getting Started

## Clone the Repository

```bash
git clone https://github.com/yourusername/backend-starter.git

cd backend-starter
```

## Install Dependencies

```bash
npm install
```

## Configure Environment Variables

Create a `.env` file in the project root and configure the required variables.

Example:

```env
PORT=8000

MONGODB_URI=

ACCESS_TOKEN_SECRET=
REFRESH_TOKEN_SECRET=

ACCESS_TOKEN_EXPIRY=1d
REFRESH_TOKEN_EXPIRY=7d

CLOUDINARY_CLOUD_NAME=
CLOUDINARY_API_KEY=
CLOUDINARY_API_SECRET=

CORS_ORIGIN=http://localhost:3000
```

---

## Run the Development Server

```bash
npm run dev
```

---

## Build for Production

```bash
npm start
```

---

# Included Integrations

This starter already includes configuration for:

* MongoDB connection
* Cloudinary image storage
* Authentication utilities
* File uploads
* Environment variables
* Error handling
* API response formatting
* Middleware setup

You can start creating routes and controllers immediately without spending time on repetitive project setup.

---

# Why Use This Template?

Most backend projects begin with the same boilerplate:

* Creating the Express server
* Connecting MongoDB
* Configuring Cloudinary
* Setting up authentication
* Handling errors
* Creating utility classes
* Organizing folders

This repository already includes these essentials, allowing you to start building features from day one.

---

# Suitable For

* REST APIs
* SaaS applications
* Admin dashboards
* Social media applications
* E-commerce backends
* Portfolio projects
* Learning Express.js architecture

---

# Contributing

Contributions, improvements, and suggestions are welcome. Feel free to fork the repository and submit a pull request.

---

# License

This project is licensed under the MIT License.
