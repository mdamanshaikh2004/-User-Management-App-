User Management App

A Node.js + Express + MySQL + EJS application for managing users.
Demonstrates CRUD operations, server-side rendering, and basic authentication.

🚀 Features

✅ View total users

✅ List all users

✅ Edit username with password verification

✅ Fully functional server-side rendered app with EJS templates

🛠 Tech Stack

Backend: Node.js, Express

Database: MySQL

Templating: EJS

Frontend: HTML, CSS

Other Tools: Faker.js (for generating dummy data), Method-Override

💻 Setup Instructions

Clone the repository

git clone <repo_url>
cd user-management-app


Install dependencies

npm install


Setup MySQL database

CREATE DATABASE metadata;
USE metadata;

CREATE TABLE user (
    id VARCHAR(255) PRIMARY KEY,
    username VARCHAR(255),
    email VARCHAR(255),
    password VARCHAR(255)
);


Start the server

node server.js


Open in browser

http://localhost:8080

📂 Project Structure
user-management-app/
├── server.js
├── package.json
├── README.md
├── views/
│   ├── home.ejs
│   ├── showusers.ejs
│   └── edit.ejs
├── public/
│   └── css/styles.css

💡 Skills Demonstrated

Node.js & Express server setup

MySQL database integration & CRUD operations

Server-side rendering with EJS

Form handling and data validation

Generating dummy data with Faker.js
