# Student Management System

A simple full-stack web application built to manage student information like marks, attendance, and roll numbers. This project helped me understand frontend-backend communication, REST APIs, and CRUD operations using Node.js and Express.js.

---

## Features

- Add new student records dynamically
- View all student details in a structured table
- Delete student records instantly
- Responsive UI using Bootstrap 5
- REST API integration between frontend and backend

---

## Tech Stack

### Frontend
- HTML5
- CSS3
- JavaScript
- Bootstrap 5

### Backend
- Node.js
- Express.js

### Other
- Fetch API
- Local Memory Array (temporary data storage)

---

## Project Structure

Student-Management-System/
│
├── index.html
├── server.js
├── package.json
└── README.md

---

## How to Run the Project

### 1. Clone the Repository

git clone <your-repository-link>

### 2. Open Project Folder

cd Student-Management-System

### 3. Install Dependencies

npm install express cors

### 4. Start Backend Server

node server.js

Server will run on:

http://localhost:3000

### 5. Run Frontend

Open `index.html` in your browser.

---

## API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | /api/students | Fetch all students |
| POST | /api/students | Add a new student |
| DELETE | /api/students/:rollNo | Delete student by roll number |

---

## Learning Outcomes

Through this project, I learned:

- CRUD operations
- REST API basics
- Frontend and backend integration
- Handling JSON data
- Using Express.js server
- Dynamic DOM manipulation
- Fetch API usage

---

## Future Improvements

- Add database integration (MongoDB/MySQL)
- Add update/edit functionality
- User authentication system
- Search and filter options
- Better UI design

---

## Author

Developed by a B.Tech student as a beginner full-stack development project 🚀
