🚀 MegaBlog – Full Stack Blogging Platform

🔗 Live Demo:
https://megablog-personal-projects.appwrite.network/

📌 Overview

MegaBlog is a modern full-stack blogging platform built using React, Redux Toolkit, and Appwrite (Backend-as-a-Service).

It allows authenticated users to create, edit, and delete blog posts with cloud-based image uploads and secure access control.

The project demonstrates production-level frontend architecture, backend integration, and real-world deployment practices.

✨ Features

🔐 Secure Authentication (Login / Logout)

📝 Create, Edit, Delete Blog Posts (Full CRUD)

🖼️ Cloud Image Upload & Management

🧠 Rich Text Editor for Post Content

🔒 Author-Based Access Control (Only creator can edit/delete)

⚡ Global State Management using Redux Toolkit

🌍 Deployed on Appwrite Hosting

🛠️ Modular Service Layer Architecture

📦 Environment-based Production Configuration

🛠️ Tech Stack
Frontend

React (Vite)

Redux Toolkit

React Router

Tailwind CSS

Backend (BaaS)

Appwrite Authentication

Appwrite Database

Appwrite Cloud Storage

Deployment

Appwrite Sites

Environment Variable Configuration

🏗️ Architecture

MegaBlog follows a modular architecture:

Service Layer abstracts all Appwrite API calls.

Redux Store manages authentication and global state.

Protected Routes restrict unauthorized access.

Component-Based Design for scalability and maintainability.

This structure ensures separation of concerns and clean, scalable code organization.

📂 Project Structure
src/
 ├── appwrite/
 │    ├── auth.js
 │    └── config.js
 ├── components/
 │    ├── PostCard.jsx
 │    ├── PostForm.jsx
 │    ├── Header.jsx
 │    └── ...
 ├── pages/
 │    ├── Home.jsx
 │    ├── Post.jsx
 │    ├── EditPost.jsx
 │    └── ...
 ├── store/
 │    └── authSlice.js
 └── main.jsx

🚀 Installation & Setup
1️⃣ Clone Repository
git clone https://github.com/Spandan3251/MegaBlog.git
cd MegaBlog

2️⃣ Install Dependencies
npm install

3️⃣ Create Environment Variables
Create a .env file in root:

VITE_APPWRITE_URL=YOUR_APPWRITE_ENDPOINT
VITE_APPWRITE_PROJECT_ID=YOUR_PROJECT_ID
VITE_APPWRITE_DATABASE_ID=YOUR_DATABASE_ID
VITE_APPWRITE_COLLECTION_ID=YOUR_COLLECTION_ID
VITE_APPWRITE_BUCKET_ID=YOUR_BUCKET_ID

4️⃣ Run Development Server
npm run dev

🧠 Key Learnings

Managing authentication lifecycle in Single Page Applications

Handling async state updates with Redux Toolkit

Debugging CORS and cloud storage permission issues

Handling production environment variables during deployment

Managing case-sensitive imports in Linux-based builds

Deploying full-stack apps with environment isolation