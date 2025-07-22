# 📚 BookReview - INSTALLATION GUIDE

Welcome! This guide walks you through setting up the BookReview project locally for development and testing.

📁 Project Structure

BookReview/
├── backend/
├── frontend/
└── .gitignore
├── CODE_OF_CONDUCT.md
├── CONTRIBUTION.md
└── installation.md

---

## 🛠 Prerequisites

Make sure you have the following installed and ready:

- **Node.js** v16 or later (includes `npm`; you can also use **yarn**)
- **Git**
- **Database**:
- **MongoDB** (if using MongoDB locally), or
- **PostgreSQL**, **MySQL**, etc.—ensure you have a running instance and a connection URI
- Optionally:
- **nodemon** (auto-restarts backend server in dev)
- **concurrently** (to run frontend & backend together)
- **Postman** or **Insomnia** for API testing

---

## 🔐 Setting Up Environment Variables

Create .env files in both frontend/ and backend/ directories with the following environment variables.

### Backend(`backend/.env`)
   PORT=5000
   FRONTEND_URL=http://localhost:5173

JWT_SECRET= # add your JWT secret here

PORT=5000

DATABASE_URL= # add your postgresql database URL here

AI_KEY= asd
AI_MODEL= gpt-3.5-turbo

### Frontend
   VITE_API_BASE_URL=http://localhost:5000/api

🚀 Getting Started

1. Clone the Repository
   -> git clone https://github.com/DonaldReddy/BookReview.git
   -> cd BookReview

2. 🧱 Backend Setup
cd backend

## Install dependencies
npm install

## Start the server
npm run dev

3. 🎨 Frontend Setup
Navigate to the frontend:
cd ../frontend

## Install dependencies:
npm install

## Start the development server:
npm start

React app will typically run at : http://localhost:3000/

✅ Verifying Setup

Frontend: http://localhost:3000

Backend API: http://localhost:5000/api

Make sure API routes return valid responses and the frontend connects to the backend.
