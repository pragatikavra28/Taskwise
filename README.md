# Taskwise
A Trello-like full-stack task manager for teams to organize work with boards, lists, and cards.

# 📦 TaskWise – Team Task Management App

TaskWise is a full-stack collaborative task management application designed for teams. It allows users to create boards, lists, and cards to organize projects efficiently – similar to Trello.

---

## 🛠️ Tech Stack

**Frontend:**
- Next.js (React)
- Tailwind CSS
- React Beautiful DnD / Framer Motion

**Backend:**
- Node.js
- Express.js

**Database:**
- PostgreSQL (with Prisma ORM)

**Authentication:**
- JWT or OAuth (Google login)

---

## ✅ Features

- 🔐 User registration and login
- 🧑‍🤝‍🧑 Team/workspace creation with invitations
- 🗂️ Boards with drag-and-drop task cards
- 📝 Add/edit tasks with due dates, labels, and comments
- 📅 Optional calendar view for tasks
- 📊 Activity logs per user/project
- 📱 Fully responsive design

---

## 📁 Folder Structure
taskwise/
├── client/ # Frontend (Next.js)
│ ├── components/ # Reusable UI components
│ ├── pages/ # Next.js pages (login, dashboard, etc.)
│ ├── styles/ # Tailwind or custom CSS
│ ├── services/ # API calls
│ ├── context/ # Global state (Auth, Theme, etc.)
│ └── utils/ # Helper functions
├── server/ # Backend (Node.js + Express)
│ ├── controllers/
│ ├── models/ # Prisma schemas
│ ├── routes/
│ ├── middleware/
│ ├── prisma/
│ │ └── schema.prisma
│ └── index.js
├── .env
├── README.md
└── package.json
