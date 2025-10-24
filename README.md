Description

BlogSpace is a simple blogging platform where users can write, edit, and share blog posts.
It has a clean design, user login, and admin control to manage posts.
Project Structure

blogspace
│
├── backend/     → Server, API routes, database connection  
│   └── server.js
│
└── frontend/    → React UI, pages, components  
    └── App.js
    Features

Add, edit, and delete posts

Login and signup

View latest posts

Clean and easy design
Tools Used

Frontend: React

Backend: Node.js + Express

Database: MongoDB
Setup Guide

1️⃣ Clone Repository

git clone https://github.com/your-username/blogspace.git
cd blogspace

2️⃣ Install Dependencies

cd backend
npm install
cd ../frontend
npm install

3️⃣ Create .env File

In backend:

PORT=5000
MONGO_URI=mongodb://127.0.0.1:27017/blogspace
JWT_SECRET=secretkey

In frontend:

REACT_APP_API_URL=http://localhost:5000/api

4️⃣ Run the Application

# Run backend
cd backend
npm run dev

# Run frontend
cd ../frontend
npm start

Then open http://localhost:3000
