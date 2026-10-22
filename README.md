# Book Buddy – Reading Tracker

Book Buddy is a web application that helps users organize their personal reading lists, track reading progress, and manage their reading goals in one place.

## Features

- **Add Books:** Add books with title, author, genre, and reading status.
- **Reading Progress:** Track progress as you read.
- **Reading Status:** Organize books into Reading, Completed, and Wishlist.
- **Reading Statistics:** View reading progress and books by genre.
- **Personal Notes and Ratings:** Record thoughts and ratings for completed books.

##  Tech Stack

### Frontend
- React.js
- JavaScript
- HTML and CSS
- Vite

### Backend
- Python
- Flask
- Flask-CORS

### Database
- SQLite

## Project Structure

```text
book-buddy-project/
├── backend/
│   ├── app.py
│   ├── books.db
│   └── requirements.txt
├── frontend/
│   ├── src/
│   │   ├── app.jsx
│   │   ├── app.css
│   │   └── main.jsx
│   ├── index.html
│   ├── package.json
│   └── package-lock.json
└── README.md
```

## 🚀 Run Locally

### Prerequisites
- Python 3
- Node.js and npm
- Git

### 1. Clone the repository

```bash
git clone https://github.com/Adhithya20/book-buddy-project.git
cd book-buddy-project
```

### 2. Start the backend

```bash
cd backend
python -m venv venv
```

Activate the virtual environment on Windows Git Bash:

```bash
source venv/Scripts/activate
```

Install dependencies and run Flask:

```bash
pip install -r requirements.txt
python app.py
```

The backend should run at `http://127.0.0.1:5000`.

### 3. Start the frontend

Open a second terminal:

```bash
cd book-buddy-project/frontend
npm install
npm run dev
```

Open the local URL printed by Vite in your terminal.

For local development, configure the frontend API URL as `http://127.0.0.1:5000` if required by your application.

## 🌐 Live Demo

- **Frontend:** https://book-buddy-application-project-1.onrender.com
- **Backend API:** https://book-buddy-application-project.onrender.com

## 🔧 Deployment

The application is deployed using Render:
- Frontend: Render Static Site
- Backend: Render Web Service

The frontend uses the `VITE_API_URL` environment variable to communicate with the deployed backend.

## 🎯 Project Objective

The objective of Book Buddy is to provide a simple and convenient way to maintain a personal book collection, monitor reading habits, and organize books according to reading status.

## 📄 License and Attribution

Review the license and attribution requirements of any original code used in this project. Add your own license only if you have the right to do so.

---

Developed as a Book Buddy reading tracker project.
