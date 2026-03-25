# MERN Todo App

A full-stack todo application built with the MERN stack (MongoDB, Express.js, React, Node.js) featuring a modern, responsive UI with TailwindCSS.

## Features

- **Create Todos**: Add new tasks with a clean, intuitive interface
- **Edit Todos**: Inline editing with save/cancel functionality
- **Delete Todos**: Remove tasks with confirmation
- **Complete/Uncomplete**: Toggle task completion status
- **Modern UI**: Clean, responsive design using TailwindCSS
- **Real-time Updates**: Instant feedback on all operations
- **Mobile Friendly**: Fully responsive design for all devices

## Tech Stack

### Frontend
- **React 19** - Modern React with latest features
- **Vite** - Fast build tool and development server
- **TailwindCSS** - Utility-first CSS framework
- **React Icons** - Beautiful icon library
- **Axios** - HTTP client for API calls

### Backend
- **Node.js** - JavaScript runtime
- **Express.js** - Web framework for REST API
- **MongoDB** - NoSQL database with Mongoose ODM
- **CORS** - Cross-origin resource sharing
- **dotenv** - Environment variable management

## Project Structure

```
mern-todo-app/
├── backend/
│   ├── config/
│   │   └── db.js              # MongoDB connection
│   ├── models/
│   │   └── todo.model.js      # Todo schema
│   ├── routes/
│   │   └── todo.route.js      # API routes
│   └── server.js              # Express server
├── frontend/
│   ├── public/
│   │   └── vite.svg
│   ├── src/
│   │   ├── App.jsx            # Main React component
│   │   ├── main.jsx           # React entry point
│   │   └── index.css          # Global styles
│   ├── package.json
│   └── vite.config.js
├── package.json               # Root package.json
└── .gitignore
```

## Getting Started

### Prerequisites
- Node.js (v16 or higher)
- MongoDB (local or cloud instance)
- npm or yarn

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Jayasrishanmugam/mern-todo-app 
   cd mern-todo-app
   ```

2. **Install dependencies**
   ```bash
   # Install root dependencies
   npm install
   
   # Install frontend dependencies
   cd frontend
   npm install
   cd ..
   ```

3. **Environment Setup**
   Create a `.env` file in the root directory:
   ```env
   MONGO_URI=mongodb://localhost:27017/mern-todo
   PORT=5000
   NODE_ENV=development
   ```

4. **Start the application**
   
   **For Development:**
   ```bash
   # Start backend server with nodemon
   npm run dev
   ```
   
   **For Production:**
   ```bash
   # Build the frontend
   npm run build
   
   # Start the production server
   npm start
   ```

5. **Access the application**
   - Frontend: http://localhost:5173 (development)
   - Backend API: http://localhost:5000
   - Production: http://localhost:5000 (serves both frontend and backend)
