# Aspirent Frontend Developer Intern Assignment

## Author

**Full Name:** Gagandeep Singh

 **Email:** gagandeepsingh128548@gmail.com

## Table of Contents

1. [Introduction](#introduction)
2. [Architecture](#architecture)
3. [Key Components](#key-components)
4. [Setup Instructions](#setup-instructions)
5. [Running the Application](#running-the-application)
6. [Reviewing the Code](#reviewing-the-code)

## Introduction

This project is a web application built with a React frontend and an Express/MongoDB backend. It demonstrates user authentication and profile management functionalities.

## Architecture

The application is divided into two main parts:

- **Frontend:** Built with React and Vite.
- **Backend:** Built with Express and MongoDB.

### Directory Structure

```

/aspirent-frontend-developer-intern-assignment
│
├── /backend
│ ├── /src
│ │ ├── /controller
│ │ │ └── user.controller.js
│ │ ├── /db
│ │ │ └── connect.db.js
│ │ ├── /model
│ │ │ └── User.model.js
│ │ ├── /routes
│ │ │ └── user.routes.js
│ │ └── app.js
│ ├── index.js
│ └── package.json
│
├── /frontend
│ ├── /public
│ ├── /src
│ │ ├── /components
│ │ ├── /hooks
│ │ ├── /pages
│ │ └── main.jsx
│ ├── index.html
│ └── package.json
│
└── README.md

```

## Key Components

### Backend

- **index.js:** Entry point for the backend server.
- **app.js:** Sets up the Express app and user-related routes.
- **user.controller.js:** Contains controller functions for user authentication and profile management.
- **connect.db.js:** Connects to the MongoDB database using Mongoose.
- **User.model.js:** Defines the user model using Mongoose.
- **user.routes.js:** Defines the routes for user-related functionality.

### Frontend

- **main.jsx:** Main entry point for the React application.
- **components:** Contains reusable React components.
- **hooks:** Contains custom React hooks.
- **pages:** Contains the main pages of the application.

## Setup Instructions

### Prerequisites

- Node.js (v14 or higher)
- MongoDB

### Backend Setup

1. Navigate to the backend directory:
   ```bash
   cd backend
   ```


2. Install the dependencies:
   ```bash
   npm install
   ```
3. Create a `.env` file in the backend directory and add your MongoDB connection string:
   ```env
   MONGODB_URI=your_mongodb_connection_string
   ```
4. Start the backend server:
   ```bash
   npm start
   ```

### Frontend Setup

1. Navigate to the frontend directory:
   ```bash
   cd frontend
   ```
2. Install the dependencies:
   ```bash
   npm install
   ```
3. Start the frontend development server:
   ```bash
   npm run dev
   ```

## Running the Application

1. Ensure MongoDB is running.
2. Start the backend server as described in the Backend Setup section.
3. Start the frontend server as described in the Frontend Setup section.
4. Open your browser and navigate to `http://localhost:3000` to view the application.

## Reviewing the Code


- **Backend Code:** Located in the `/backend/src` directory.
- **Frontend Code:** Located in the `/frontend/src` directory.

Feel free to reach out to me at gagandeepsingh128548@gmail.com if you have any questions or need further assistance.

---
