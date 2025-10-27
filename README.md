# Notely 🗑️



test
**Notely** is a full-stack note-taking web application built with **Django (backend)** and **React + Vite (frontend)**. This project demonstrates modern web app architecture, RESTful API integration, and deployment on free hosting platforms.

---

## Demo

* **Frontend:** [https://notely.vercel.app](https://notely.vercel.app)
* **Backend API:** [https://notely.liara.run](https://notely.liara.run/)

---

## Tech Stack

| Layer      | Technology                         |
| ---------- | ---------------------------------- |
| Backend    | Django, Django REST Framework      |
| Frontend   | React, Vite, Tailwind CSS          |
| Database   | PostgreSQL                         |
| Hosting    | Liara (Backend), Vercel (Frontend) |
| Deployment | GitHub Actions                     |

---

## Features

* User authentication (register, login, logout)
* CRUD notes functionality
* Responsive and mobile-friendly UI
* REST API powering the frontend
* Separate frontend/backend deployment

---

## Project Structure

```
Notely/
├─ backend/        # Django backend
├─ frontend/       # React + Vite frontend
│  ├─ src/
│  ├─ public/
│  ├─ package.json
│  └─ vite.config.js
├─ README.md
```

---

## Getting Started

### Backend

```bash
cd backend
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

### Frontend

```bash
cd frontend
npm install
npm run dev
```
#Ports for testing and developing:
Frontend: [http://localhost:5173](http://localhost:5173)
Backend: [http://localhost:8000](http://localhost:8000)

---

## Why This Project

* Demonstrates **full-stack development** with separate frontend/backend
* Highlights skills in **React, Vite, Django, PostgreSQL**

---

## Future Improvements

* Tags/categories for notes
* Search/filtering
* Real-time updates with WebSockets or Django Channels
* Enhanced UI/UX with animations or drag-an

# Feel free to contribute
