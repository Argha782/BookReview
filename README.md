<h1 align="center">📖 BookReview</h1> <p align="center"> <img src="https://img.shields.io/badge/GSSoC-2025-orange?style=for-the-badge&logo=github"> <img src="https://img.shields.io/badge/PRs-welcome-brightgreen?style=for-the-badge&logo=github"> <a href="https://bookreview.donaldreddy.me"> <img src="https://img.shields.io/badge/Live-Demo-blue?style=for-the-badge&logo=vercel"> </a> </p> <p align="center"> <img src="https://img.shields.io/github/issues/DonaldReddy/BookReview?style=flat-square"> <img src="https://img.shields.io/github/forks/DonaldReddy/BookReview?style=flat-square"> <img src="https://img.shields.io/github/stars/DonaldReddy/BookReview?style=flat-square"> <img src="https://img.shields.io/github/last-commit/DonaldReddy/BookReview?style=flat-square"> </p>


**BookReview** is an AI-powered web application that helps users discover, rate, and review books with ease. Featuring an intuitive user interface, intelligent search and filter functionality, and AI-generated review suggestions via OpenRouter, it enhances the reading experience for the digital age.

🔗 **Live Demo:** [https://bookreview.donaldreddy.me](https://bookreview.donaldreddy.me)

---

## 🖼️ Preview

| Home Page | Review Page | Profile Page |
|-----------|-------------|--------------|
| ![Home](https://github.com/user-attachments/assets/ea2a1907-e6d0-4439-b605-f74efc056d62) | ![Review](https://github.com/user-attachments/assets/f314c800-5caf-4d31-bc48-dbbf6b8019c4) | ![Profile](https://github.com/user-attachments/assets/69aa71d8-6f74-4487-a7c7-a9299cfd5126) |


> 📌 *Screenshots reflect the latest UI after improvements.*

---

## 💡 Features

- 🧠 **AI-Assisted Reviews**  
  Integrated with **OpenRouter** to help generate intelligent, context-aware review suggestions.

- 🔍 **Search and Filter**  
  Search books by title, author, or keywords. Filter results dynamically to find books efficiently.

- 🧾 **Ratings & Reviews**  
  Leave star ratings and text reviews for books. Each review is linked to a user profile and is editable.

- 🔐 **User Authentication**  
  Secure login/signup using **JWT (JSON Web Tokens)** to ensure protected access and sessions.

- 👤 **User Profiles**  
  Users can view, edit, and manage their reviews and profile data from a dedicated profile page.

- 📚 **Book Listing**  
  Browse all books in a responsive, card-based layout with detailed information.

---

## 🛠️ **Tech Stack**

| Tech             | Role                        |
|------------------|-----------------------------|
| React.js         | Frontend UI                 |
| Tailwind CSS     | Styling & layout            |
| Node.js & Express| Backend APIs                |
| MongoDB          | Database                    |
| JWT              | Authentication              |
| OpenRouter      | AI-generated review content |
| Render           | Deployment platform         |

---

## 📂 **Project Structure**

```
BookReview/
├── .github/                # GitHub workflows and configs
├── Backend/                # Backend (Express.js + Prisma)
│   ├── controller/         # Request handlers
│   ├── database/           # DB connection logic
│   ├── middleware/         # Auth and error handling
│   ├── prisma/             # Prisma schema and migrations
│   ├── repository/         # DB query logic (e.g., books, users)
│   ├── routes/             # API route definitions
│   ├── service/            # Business logic
│   ├── utils/              # Helper functions
│   ├── .env.example        # Sample environment variables
│   ├── index.js            # Entry point for the server
│   ├── package.json        # Backend dependencies
│   └── package-lock.json
├── Frontend/               # Frontend (React + Tailwind)
│   ├── public/             # Static assets
│   ├── src/                # Main React source code
│   ├── .env.example        # Sample frontend env file
│   ├── eslint.config.js    # ESLint configuration
│   ├── package.json        # Frontend dependencies
│   ├── package-lock.json
│   ├── tsconfig.json       # TypeScript config
│   ├── tsconfig.app.json
│   ├── tsconfig.node.json
│   └── vite.config.ts      # Vite bundler config
├── .gitignore              # Ignore rules
├── CODE_OF_CONDUCT.md      # Contributor behavior rules
├── CONTRIBUTION.md         # Contribution guide
├── installation.md         # Local setup instructions
└── README.md               # Main project documentation

```

---

## 🛠️ **Installation**

To get this project up and running locally, follow the steps outlined in the Installation Guide. It includes everything from cloning the repository to setting up environment variables and running the development server.

🔗 [Installation Guide](./docs/installation.md)

---

## 🤝 **Contribution**

We welcome all contributions — from design tweaks to major features. Please follow our guidelines for coding style and pull requests.

🔗 [Contribution Guidelines](./docs/contribution.md)

---

## ✨ **AI Integration**

This app uses **OpenRouter** to assist users while writing reviews. Users can click a button during review entry to generate suggestions or summaries using AI.

---

## 🚧 **In Progress / Upcoming Features**

These features are currently being developed or planned:

- 🌓 **Dark/Light Mode Toggle** *(In Progress)*  
  Enable theme switching for improved accessibility and user preference.

- 🪟 **Toast Notifications** *(In Progress)*  
  Display real-time feedback messages (e.g., login success, errors, actions) using toast alerts.

- ❌ **Custom 404 Page** *(In Progress)*  
  Design and implement a user-friendly “Page Not Found” screen for invalid routes.

- 🎨 **UI Standardization** *(Ongoing)*  
  Improve layout consistency, spacing, and font styles across the site for a unified user experience.

---

## 🚀 **GirlScript Summer of Code (GSSoC) 2025**

This project is part of **GSSoC '25** — welcoming all new contributors!  
You can participate by working on open issues, UI improvements, documentation, or feature building.

> 👏 Feel free to open an issue to get started!

---

**Project by [DonaldReddy](https://github.com/DonaldReddy)** 💻

---
