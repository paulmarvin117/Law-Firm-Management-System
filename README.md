# Law Firm Management System

Web application for managing law firm operations.

## Stack
- Frontend: Next.js (`frontend/`)
- Backend: FastAPI + SQLAlchemy + Alembic (`backend/`)
- Database: PostgreSQL

## Setup

### Backend
```
cd backend
py -3 -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt
copy .env.example .env   # then edit .env
```

### Frontend
```
cd frontend
npm install
copy .env.example .env.local   # then edit
npm run dev
```