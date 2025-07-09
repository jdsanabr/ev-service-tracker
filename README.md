# 🚗 EV Service & Maintenance Tracker

A full-stack web application that allows electric vehicle owners and service centers to manage vehicles and their service records efficiently. Built with modern technologies, the platform is designed to scale and evolve for future enhancements such as predictive maintenance, mobile app support, and API integrations.

---

## ✨ Features

- User authentication (signup/login) with JWT
- Add, edit, delete, and view vehicles
- Track service records for each vehicle (CRUD)
- Responsive UI for desktop and mobile
- REST API with modular architecture (Phase 2 ready)
- Deployed frontend and backend with environment variable support

---

## 🛠 Tech Stack

| Layer            | Technology                        |
|------------------|------------------------------------|
| **Frontend**     | React (Vite), Tailwind CSS         |
| **Backend**      | Node.js, Express.js, Prisma ORM    |
| **Database**     | PostgreSQL (hosted on Supabase)    |
| **Authentication** | JWT (JSON Web Tokens)           |
| **Version Control** | Git + GitHub                    |
| **Deployment**   | Vercel (frontend), Render (backend)|
| **Dev Tools**    | ESLint, Prettier, Postman          |

---

## 🚀 Live Demo

🔗 [COMING SOON]  
(Will update with deployed URL after deployment)

---

## 📦 Project Structure
ev-service-tracker/
├── backend/ # Node.js + Express API
├── frontend/ # React client app
├── .gitignore
├── README.md # Top-level README



Each folder includes its own README for specific setup instructions.

---

## ⚙️ Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/) (v18+)
- [PostgreSQL](https://www.postgresql.org/)
- Git

### Clone the repository
```bash
git clone https://github.com/<your-username>/ev-service-tracker.git
cd ev-service-tracker
```

### 🌐 Frontend Setup
cd frontend
npm install
npm run dev

### ⚙️ Backend Setup
cd backend
npm install
npx prisma migrate dev
npm run dev

