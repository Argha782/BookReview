## 📚 Welcome to BookReview Contributor Guide

Thank you for your interest in contributing to **BookReview**. Please follow these clear steps to set up the project and contribute efficiently.

---

## 🚀 How to Contribute (Step-by-Step)

### 1️⃣ **Fork the Repository**

- Go to the repository: [https://github.com/DonaldReddy/BookReview](https://github.com/DonaldReddy/BookReview)
- Click on **Fork** (top-right).

---

### 2️⃣ **Clone Your Fork Locally**

```bash
git clone https://github.com/<your-github-username>/BookReview.git
cd BookReview
```

---

### 3️⃣ **Set Up the Backend**

1. Go to the backend directory:

```bash
cd backend
```

2. Install backend dependencies:

```bash
npm install
```

3. Rename `.env.example` to `.env` and fill in:

```
FRONTEND_URL=http://localhost:5173
JWT_SECRET=your_secret
PORT=9999
DATABASE_URL=your_postgresql_connection_url
AI_KEY=your_ai_key
AI_MODEL=gpt-3.5-turbo
```

4. Start the backend server:

```bash
npm run dev
```

Backend runs at: `http://localhost:9999`

---

### 4️⃣ **Set Up the Frontend**

1. Go to the frontend directory:

```bash
cd ../frontend
```

2. Install frontend dependencies:

```bash
npm install
```

3. Rename `.env.example` to `.env` and fill in:

```
VITE_API_BASE_URL=http://localhost:9999
```

4. Start the frontend server:

```bash
npm run dev
```

Frontend runs at: `http://localhost:5173`

5. (Optional) Check code style using:

```bash
npm run lint
```

---

### 5️⃣ **Contribution Flow**

1. Always **start from the `deploy` branch**:

```bash
git checkout deploy
git pull origin deploy
```

2. Create your feature/fix branch:

```bash
git checkout -b feature/your-feature-name
```

3. Make your changes in backend or frontend.

4. **Test your changes locally** to ensure everything works.

5. **Ensure frontend code is linted**:

```bash
npm run lint
```

6. Add, commit, and push your branch:

```bash
git add .
git commit -m "Meaningful message"
git push origin feature/your-feature-name
```

7. **Raise a Pull Request to the `test` branch.**

---

## 🏷️ Issue Types

| Label           | Use For                      |
| --------------- | ---------------------------- |
| **Bug**         | Fix broken logic or UI       |
| **Feature**     | Add new functionality        |
| **Enhancement** | Improve existing logic or UI |
| **Doc**         | Documentation updates        |

---

## 📄 Issue Format

- **Title:**
  `[Bug/Feature/Enhancement/Doc] - Short description`

- **Description:**
  Explain clearly, include screenshots/code snippets if helpful.

---

## 📄 Pull Request Format

- **Title:**
  `[Bugfix/Feature/Enhancement/Doc] - Short description`

- **Description:**

- What changes were made?

- Why they are necessary?

- Mention related issue using `#issue-number`.

- **Checklist Before PR:**

  - [ ] Tested locally.
  - [ ] Frontend code linted (`npm run lint`).
  - [ ] PR is raised to the **`test`** branch (not deploy).
  - [ ] Clean and clear commit message.

---

## 📦 Deployment Process

- PRs merged into `test` will be reviewed and tested.
- Only maintainers merge changes from `test` to `deploy` for production.

---

## 🔥 Quick Tips

- Avoid large PRs. Keep your changes focused.
- Sync your fork regularly to avoid conflicts.
- Be respectful and professional in all discussions.

---

## 🎉 Happy Contributing! 🎉
