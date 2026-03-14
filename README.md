📚 Bookscape – MERN Bookstore Management System
🚀 Overview

Bookscape is a full-stack MERN application that allows users to browse, purchase, and manage books online. The platform provides a seamless experience for customers to discover books while giving administrators powerful tools to manage inventory and users.

This project demonstrates a complete production-style web application with authentication, role-based access, API integration, and modern frontend architecture.

🌐 Live Demo

Frontend: https://bookscape-zone.netlify.app


🧠 Project Motivation

The goal of Bookscape is to simulate a real-world e-commerce bookstore platform where:

Users can browse books

Add books to cart or favorites

Place orders

Manage their personal book lists

Administrators have full control over the platform including managing books and users.

This project highlights full-stack development skills including REST API design, database management, frontend UI development, and deployment.

🏗 Tech Stack
Frontend

React.js

Vite

Axios

CSS

Backend

Node.js

Express.js

MongoDB

Mongoose

Authentication

JSON Web Token (JWT)

Deployment

Netlify (Frontend)

Render (Backend)

MongoDB Atlas (Database)

👤 User Features

Users can:

📖 Browse all available books

🔍 View book details

❤️ Add books to favorites

🛒 Add books to cart

📦 Place orders

👤 Register and login securely

📚 View purchased books

🛠 Admin Features

Administrators have additional privileges:

➕ Add new books

✏️ Update book details

❌ Delete books

👥 Manage users

📦 View and manage orders

📂 Project Structure
Bookscape
│
├── backend
│   ├── conn
│   │   └── conn.js
│   ├── models
│   ├── routes
│   │   ├── user.js
│   │   ├── book.js
│   │   ├── cart.js
│   │   ├── favourite.js
│   │   └── order.js
│   └── app.js
│
├── frontend
│   ├── src
│   │   ├── components
│   │   ├── pages
│   │   └── App.jsx
│   └── package.json
⚙️ Installation & Setup
1️⃣ Clone the repository
git clone https://github.com/HarshSirohi/Bookscape-management-system-By-Mern.git
2️⃣ Install dependencies

Backend:

cd backend
npm install

Frontend:

cd frontend
npm install
3️⃣ Environment Variables

Create a .env file in backend:

MONGO_URI=your_mongodb_connection_string
PORT=1000
FRONTEND_URL=your_frontend_url
JWT_SECRET=your_secret_key
4️⃣ Run the application

Backend:

npm start

Frontend:

npm run dev
🔗 API Endpoints
User
POST /api/v1/signup
POST /api/v1/login
GET /api/v1/get-user-info
Books
GET /api/v1/get-all-books
GET /api/v1/get-recent-books
POST /api/v1/add-book
DELETE /api/v1/delete-book
Cart
POST /api/v1/add-to-cart
GET /api/v1/get-cart
DELETE /api/v1/remove-from-cart
Favourite
POST /api/v1/add-to-favourite
GET /api/v1/get-favourites
Orders
POST /api/v1/place-order
GET /api/v1/get-order-history
📸 Key Highlights

Full MERN stack architecture

Role-based authentication (Admin & User)

RESTful API design

Responsive frontend UI

Secure backend with JWT

Cloud deployment

🎯 Skills Demonstrated

Full Stack Development

REST API Design

Authentication & Authorization

Database Modeling

Cloud Deployment

Git & Version Control

📌 Future Improvements

Payment gateway integration

Search and filtering system

Book reviews and ratings

Email notifications

Admin analytics dashboard
