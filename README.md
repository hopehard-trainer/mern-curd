# 🚀 MERN CRUD Web Application

This is a full-stack **MERN (MongoDB, Express, React, Node.js)** CRUD web application that supports:

- Creating, Reading, and Deleting items
- React frontend deployed using **GitHub Pages**
- Express backend connected to **MongoDB Atlas**
- Continuous deployment via **GitHub Actions**
- Basic unit testing with **React Testing Library**

---

## 📁 Folder Structure

```
mern-crud/
├── frontend/            # React App (GitHub Pages hosted)
├── backend/             # Express API (MongoDB Atlas connected)
├── .github/
│   ├── workflows/       # GitHub Actions for deployment
│   └── pull_request_template.md
├── .env                 # MongoDB Atlas URI (not committed)
```

---

## 🌐 Live Demo

Frontend: [https://your-username.github.io/your-repo-name](https://your-username.github.io/your-repo-name)

Backend: Deploy to services like [Render](https://render.com), [Railway](https://railway.app), or [Fly.io](https://fly.io)

---

## 🧪 Tech Stack

| Layer      | Tech                        |
|------------|-----------------------------|
| Frontend   | React, HTML/CSS, JS         |
| Backend    | Express, Node.js            |
| Database   | MongoDB Atlas               |
| Deployment | GitHub Pages + GitHub Actions |
| Testing    | React Testing Library       |

---

## 🔧 Setup Instructions

### 1. Clone the Repo

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### 2. Configure Environment

Create a `.env` file in the root:

```env
MONGO_URI=mongodb+srv://<user>:<password>@cluster0.mongodb.net/<dbname>?retryWrites=true&w=majority
```

Create a `.env` file in the `frontend/` folder:

```env
REACT_APP_API_BASE=https://your-backend-api-url.com
# or use http://localhost:3001 for local development
```

### 3. Install Dependencies

```bash
# Install frontend
cd frontend
npm install

# Install backend
cd ../backend
npm install
```

### 4. Run Locally

```bash
# Backend
cd backend
npm start

# Frontend
cd ../frontend
npm start
```

---

## 🧪 Run Tests

```bash
cd frontend
npm test
```

---

## 📦 Build and Deploy

GitHub Actions will automatically:

- Build the frontend
- Deploy to GitHub Pages when you push to `main`

To trigger manually:

```bash
git add .
git commit -m "Deploy"
git push origin main
```

---

## 🤝 Contributing

Pull requests are welcome! Please follow the included PR template.

---

## 📄 License

MIT © [hopehard-trainer](https://github.com/your-username)
