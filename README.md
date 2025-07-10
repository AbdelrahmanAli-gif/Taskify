# 📋 Taskify

**Taskify** is a full-stack task management web application inspired by Trello and Jira. It allows users to register, authenticate, and manage their tasks across multiple boards. Built using the MERN stack with JWT-based authentication and a clean, responsive UI using React and Tailwind CSS.

---

## Features

### Authentication
- User registration and login
- JWT-based authentication with access and refresh tokens
- Password hashing with bcrypt

### Task Management
- Create and manage boards
- Add, update, and delete tasks
- Organize tasks into structured boards (Kanban-style)

### Backend (Express.js + MongoDB)
- Modular route handling (`/auth`, `/users`, `/boards`)
- MongoDB database with Mongoose
- Environment variable configuration
- Token-based auth and user session management

### Frontend (React + Tailwind + Vite)
- Modern UI built with Tailwind CSS
- Fast bundling using Vite
- React hooks and component-based structure
- Fully responsive layout

---

## Tech Stack

| Layer       | Technologies                            |
|-------------|------------------------------------------|
| Frontend    | React, Vite, Tailwind CSS                |
| Backend     | Node.js, Express.js, Mongoose            |
| Auth        | JWT, bcrypt                              |
| Database    | MongoDB                                  |
| Styling     | Tailwind CSS                             |

---

## Live Demo
https://taskify-frontend-five.vercel.app/
