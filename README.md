# Not.Habit

A habit tracking web app with user registration and login.

## Features

- User registration and login (JWT authentication)
- Passwords hashed with bcrypt
- Habit dashboard with charts

## Tech Stack

- Node.js, Express
- MongoDB, Mongoose
- JWT, bcryptjs
- HTML, CSS, JavaScript

## Setup

1. Install dependencies:
   ```
   npm install
   ```

2. Set environment variables:
   ```
   MONGO_URI=mongodb://127.0.0.1:27017/habitapp
   JWT_SECRET=your_secret_key
   PORT=3000
   ```

3. Start the server:
   ```
   npm start
   ```

4. Open https://not-habit.onrender.com
