# 🏋️ Workout App Project

A simple CRUD application to manage your workout routines, built with **Next.js** (frontend) and **FastAPI** (backend).

## 🎯 Objective

This project was created to practice:
- **Frontend**: Next.js with React
- **Backend**: FastAPI with Python
- **Architecture**: REST API with authentication
- **Database**: PostgreSQL

## 🏗️ Project Structure

```
workout-app-project/
├── fastapi/                 # FastAPI Backend
│   ├── api/
│   │   ├── database.py      # Database configuration
│   │   ├── deps.py          # Dependencies and authentication
│   │   ├── main.py          # API entry point
│   │   ├── models.py        # Data models
│   │   └── routers/         # API routes
│   │       ├── auth.py      # Authentication
│   │       ├── routines.py  # Routine management
│   │       └── workouts.py  # Workout management
│   └── requirements.txt     # Python dependencies
│
└── nextjs/                  # Next.js Frontend
    ├── src/
    │   └── app/            # Next.js 13+ App Router
    │       ├── components/  # Reusable components
    │       ├── context/     # React Context (AuthContext)
    │       ├── login/       # Login page
    │       └── page.js      # Main page
    ├── package.json         # Node.js dependencies
    └── next.config.mjs      # Next.js configuration
```

## 🚀 Features

- **Authentication**: Secure login system
- **Routine Management**: Complete CRUD for workout routines
- **Workout Tracking**: Session tracking and management
- **Responsive Interface**: Modern and adaptive design
- **REST API**: Well-structured and documented endpoints

## 🛠️ Technologies Used

### Backend
- **FastAPI** - Modern and fast Python web framework
- **PostgreSQL** - Relational database
- **SQLAlchemy** - Python ORM

### Frontend
- **Next.js 13+** - React framework with App Router
- **React** - UI library
- **CSS Modules** - Modular styling
- **Context API** - Global state management with `useContext``

## 📋 Prerequisites

- Python 3.8+
- Node.js 18+

## 🔧 Installation and Setup

### Backend (FastAPI)
```bash
cd fastapi
pip install -r requirements.txt
uvicorn api.main:app --reload
```

### Frontend (Next.js)
```bash
cd nextjs
npm install
npm run dev
```

## 🌐 Access

- **Frontend**: http://localhost:3000
- **Backend API**: http://localhost:8000
- **API Documentation**: http://localhost:8000/docs

---

*Learning project to practive Next.js and FastAPI* 🚀
