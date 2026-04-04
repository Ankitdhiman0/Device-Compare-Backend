⚙️ Device Compare – Backend

Device Compare Backend is a RESTful API built with Node.js, Express, and MongoDB.
It powers the mobile and laptop comparison platform by handling authentication, authorization, device management, and secure API communication.

This backend is structured using clean architecture principles and follows REST standards for scalability and maintainability.

🚀 Tech Stack
Core

Node.js

Express 5

MongoDB

Mongoose

Authentication & Security

JWT (jsonwebtoken)

bcrypt (password hashing)

cookie-parser

dotenv

Middleware & Logging

cors

morgan

Development

Nodemon

HTTP Client

Axios (for external API integrations if required)

🔐 Core Features

User Registration & Login

Secure Password Hashing (bcrypt)

JWT-based Authentication

Role-based Authorization (Admin & User)

Device CRUD Operations

RESTful API Structure

Environment-based Configuration

MongoDB Data Modeling with Mongoose

📦 Installation

Clone the repository:

git clone <your-backend-repo-url>
cd backend

Install dependencies:

npm install

▶️ Running the Server
Development Mode
npm run dev

Uses nodemon for automatic restarts.

Production Mode
npm start

Runs the server using Node.

⚙️ Environment Variables

Create a .env file in the root directory:

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_super_secret_key

📂 Recommended Project Structure
backend/
│── controllers/
│── models/
│── routes/
│── middleware/
│── app.js
│── package.json
│── .env

🔄 API Base URL
http://localhost:5000/device-compare

🧠 Architecture Decisions

MVC pattern for separation of concerns

JWT for stateless authentication

Middleware-based authorization flow

Environment-based configuration with dotenv

Clean RESTful route structure

👨‍💻 Author

Ankit Dhiman
MERN Stack Developer
