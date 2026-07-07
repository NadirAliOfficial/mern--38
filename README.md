# MERN Stack Project

A full-stack web application built with MongoDB, Express, React, and Node.js featuring user authentication, REST API, and a responsive Tailwind CSS frontend.

## Tech Stack

- **Frontend:** React 18, Vite, Tailwind CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB with Mongoose
- **Auth:** JWT + bcrypt

## Features

- User registration and login with JWT authentication
- Protected routes on both frontend and backend
- RESTful API with full CRUD operations
- Responsive UI with Tailwind CSS

## Getting Started

```bash
# Install dependencies
npm install
cd client && npm install

# Set environment variables
cp .env.example .env

# Run development server
npm run dev
```

## API Endpoints

| Method | Route | Description |
|--------|-------|-------------|
| POST | /api/auth/register | Register new user |
| POST | /api/auth/login | Login and get token |
| GET | /api/users | Get all users (protected) |
| PUT | /api/users/:id | Update user |
| DELETE | /api/users/:id | Delete user |

## Project Structure

```
├── client/          # React frontend
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   └── App.jsx
├── server/          # Express backend
│   ├── routes/
│   ├── models/
│   └── index.js
└── package.json
```
