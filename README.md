# 📱 MERN Social Media App

A full-stack social media platform built with the **MERN stack** (MongoDB, Express.js, React, Node.js), featuring real-time messaging powered by **Socket.IO**.

## ✨ Features

- **User Authentication** — JWT-based secure login and registration
- **Social Feed** — Create, read, update, and delete posts
- **Real-Time Messaging** — Live chat powered by Socket.IO WebSockets
- **Follow System** — Follow/unfollow users and personalised feed
- **RESTful API** — Clean MVC backend with modular routes and controllers
- **Middleware** — Auth middleware for protected routes

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | React.js |
| Backend | Node.js, Express.js |
| Database | MongoDB (Mongoose ODM) |
| Real-Time | Socket.IO |
| Auth | JWT (JSON Web Tokens) |

## 📁 Project Structure

```
mern-social-media-master/
├── client/              # React frontend
├── controllers/         # Route handler logic
├── middleware/          # Auth & validation middleware
├── models/              # Mongoose data models
├── routes/              # Express API routes
├── server.js            # Main Express server entry point
└── socketServer.js      # Socket.IO real-time server
```

## 🚀 Getting Started

### Prerequisites
- Node.js v16+
- MongoDB (local or Atlas)

### Installation

```bash
# Clone the repo
git clone https://github.com/satyamsh04/mern-social-media-app.git
cd mern-social-media-app/mern-social-media-master

# Install backend dependencies
npm install

# Install frontend dependencies
cd client
npm install
```

### Environment Setup

Copy `.env` and fill in your values:

```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
PORT=5000
```

### Run the App

```bash
# Run backend (from root)
npm run server

# Run frontend (from /client)
npm start
```

## 📚 What I Learned

- Designing a RESTful API with Express and MVC architecture
- Implementing real-time bidirectional communication with Socket.IO
- Managing application state and async data in React
- JWT-based authentication and protected route middleware

---

*Built as part of Griffith University CS curriculum — Satyam Sharma*
