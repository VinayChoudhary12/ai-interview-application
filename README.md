# AI Interviewer

AI Interviewer is a MERN stack based web application that helps users prepare for interviews using AI-powered features like interview question generation, resume analysis, and interview reports.
user can download the interview report as well.

---

## Live Project

🚀 Frontend: https://frontend3-0jfb.onrender.com

⚡ Backend: https://backend1-a4h7.onrender.com

# Features

- User Authentication (Register/Login)
- JWT Based Authentication
- AI Generated Interview Questions
- Resume Upload and Analysis
- Interview Report Generation
- Protected Routes
- Responsive User Interface
- Cookie Based Authentication
- MongoDB Database Integration

---

# Tech Stack

## Frontend
- React.js
- Vite
- Axios
- SCSS

## Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication
- bcryptjs
- cookie-parser
- cors

---

# Project Structure

```bash
AI_INTERVIEW-main/
│
└── AI_INTERVIEWER/
    │
    ├── Backend/
    │   │
    │   ├── .gitignore
    │   ├── package.json
    │   ├── package-lock.json
    │   ├── server.js
    │   │
    │   └── src/
    │       │
    │       ├── app.js
    │       │
    │       ├── config/
    │       │   └── database.js
    │       │
    │       ├── controllers/
    │       │   ├── auth.controller.js
    │       │   └── interview.controller.js
    │       │
    │       ├── middlewares/
    │       │   ├── auth.middleware.js
    │       │   └── file.middleware.js
    │       │
    │       ├── models/
    │       │   ├── blacklist.model.js
    │       │   ├── interviewReport.model.js
    │       │   └── user.model.js
    │       │
    │       ├── routes/
    │       │   ├── auth.routes.js
    │       │   └── interview.routes.js
    │       │
    │       └── services/
    │           └── ai.service.js
    │
    └── Frontend/
        │
        ├── .gitignore
        ├── README.md
        ├── package.json
        ├── package-lock.json
        ├── vite.config.js
        ├── eslint.config.js
        ├── index.html
        │
        ├── public/
        │   └── vite.svg
        │
        └── src/
            │
            ├── App.jsx
            ├── main.jsx
            ├── app.routes.jsx
            ├── style.scss
            │
            ├── style/
            │   └── button.scss
            │
            └── features/
                │
                ├── auth/
                │   │
                │   ├── auth.context.jsx
                │   ├── auth.form.scss
                │   │
                │   ├── components/
                │   │   └── Protected.jsx
                │   │
                │   ├── hooks/
                │   │   └── useAuth.js
                │   │
                │   ├── pages/
                │   │   ├── Login.jsx
                │   │   └── Register.jsx
                │   │
                │   └── services/
                │       └── auth.api.js
                │
                └── interview/
                    │
                    ├── interview.context.jsx
                    │
                    ├── hooks/
                    │   └── useInterview.js
                    │
                    ├── pages/
                    │   ├── Home.jsx
                    │   └── Interview.jsx
                    │
                    ├── services/
                    │   └── interview.api.js
                    │
                    └── style/
                        ├── home.scss
                        ├── interview.scss
                        └── logout.scss
---

# Installation

## Clone Repository

```bash
git clone https://github.com/your-username/your-repository-name.git
```

---

# Backend Setup

Go to backend folder:

```bash
cd backend
```

Install dependencies:

```bash
npm install
```

Create `.env` file:

```env
PORT=3000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

Run backend server:

```bash
npm start
```

---

# Frontend Setup

Go to frontend folder:

```bash
cd frontend
```

Install dependencies:

```bash
npm install
```

Create `.env` file:

```env
VITE_BASE_URL=http://localhost:3000
```

Run frontend:

```bash
npm run dev
```

---

# Deployment

## Frontend Deployment
- Render
- Vercel
- Netlify

## Backend Deployment
- Render
- Railway

## Database
- MongoDB Atlas

---

# API Endpoints

## Authentication

### Register User

```http
POST /api/auth/register
```

### Login User

```http
POST /api/auth/login
```

### Logout User

```http
GET /api/auth/logout
```

### Get Current User

```http
GET /api/auth/get-me
```

---

# Environment Variables

## Backend

```env
PORT=
MONGO_URI=
JWT_SECRET=
```

## Frontend

```env
VITE_BASE_URL=
```

---

# Security Features

- Password Hashing using bcryptjs
- JWT Authentication
- HTTP Only Cookies
- CORS Protection
- Token Blacklisting

---

# Future Improvements

- AI Mock Interviews
- Video Interview Support
- Real-time Feedback
- Dashboard Analytics
- Dark Mode
- Admin Panel

---

# Author

Vinay Choudhary

---

# License

This project is licensed under the MIT License.
