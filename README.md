# TalentFlow AI

## Smart AI-Powered Recruitment & Job Aggregation Platform

TalentFlow AI is a modern full-stack AI recruitment and job aggregation platform built to simplify hiring, resume analysis, job discovery, and candidate-employer interaction.

The platform combines AI-powered resume parsing, ATS analysis, semantic job matching, role-based dashboards, subscription systems, and intelligent job recommendations into one scalable SaaS ecosystem.

---

# Features

## Candidate Features

* AI Resume Upload & Parsing
* Automatic Profile Creation
* ATS Resume Analysis
* AI Profile Scoring
* Recommended Jobs System
* Saved Jobs
* Applied Jobs Tracking
* Skill Gap Analysis
* Personalized Dashboard
* Subscription Plans
* Responsive UI

---

## Employer Features

* Employer Dashboard
* Company Profile Management
* Post Jobs
* Manage Posted Jobs
* View Applicants
* Candidate Ranking System
* AI-Based Candidate Analysis
* Application Tracking
* Premium Employer UI

---

## Admin Features

* Manage Users
* Manage Employers
* Manage Jobs
* Monitor Platform Activity
* Subscription Management
* Payment Monitoring
* Platform Analytics

---

# AI Features

TalentFlow AI integrates advanced AI capabilities for intelligent recruitment.

### Resume Parsing

* PDF & DOCX Resume Extraction
* AI-Based Information Extraction
* Automatic Skill Detection
* Experience Analysis
* Education Detection

### ATS Analysis

* ATS Resume Score
* Resume Strength Detection
* Weakness Identification
* Missing Skills Analysis
* Improvement Suggestions

### Job Matching

* Semantic Job Matching
* Personalized Recommendations
* Skill-Based Ranking
* AI Match Percentage

### AI Models & Tools

* Google Gemini API
* Groq API
* Sentence Transformers
* Scikit-learn
* NLP Processing

---

# Tech Stack

## Frontend

* React.js
* Vite
* Tailwind CSS
* React Router
* Axios
* Lucide React
* Framer Motion

---

## Backend

* FastAPI
* Python
* JWT Authentication
* Cookie-Based Authentication
* Motor (Async MongoDB)
* APScheduler

---

## Database

* MongoDB Atlas

---

## AI & NLP

* Google Gemini
* Groq
* Sentence Transformers
* Scikit-learn
* PDFPlumber
* Python-Docx

---

# Project Architecture

```txt
TalentFlowAI/
│
├── job_aggregator_ai/
│   ├── src/
│   │   ├── api/
│   │   ├── ai/
│   │   ├── models/
│   │   ├── services/
│   │   ├── engine/
│   │   ├── middleware/
│   │   └── utils/
│   │
│   ├── main.py
│   ├── requirements.txt
│   └── .env
│
├── job_aggregator_frontend/
│   ├── src/
│   │   ├── pages/
│   │   ├── components/
│   │   ├── layouts/
│   │   ├── services/
│   │   ├── routes/
│   │   ├── hooks/
│   │   └── context/
│   │
│   ├── package.json
│   └── vite.config.js
│
└── README.md
```

---

# Authentication System

TalentFlow AI uses secure production-ready cookie-based authentication.

### Features

* HttpOnly Cookies
* JWT Authentication
* Role-Based Access
* Protected Routes
* Secure Login & Logout
* Backend Validation

---

# Subscription System

The platform supports multiple subscription tiers.

### Plans

* Free
* Pro
* Premium

### Premium Features

* Advanced AI Analysis
* Unlimited Resume Parsing
* Priority Recommendations
* Employer Insights
* Advanced Candidate Ranking

---

# Deployment

## Frontend Deployment

* Vercel

## Backend Deployment

* Render

## Database

* MongoDB Atlas

---

# Environment Variables

## Backend (.env)

```env
MONGO_URI=
DB_NAME=
JWT_SECRET=
JWT_ALGORITHM=HS256
ACCESS_TOKEN_EXPIRE_MINUTES=10080
GEMINI_API_KEY=
GROQ_API_KEY=
FRONTEND_URL=
```

---

## Frontend (.env)

```env
VITE_API_BASE_URL=
```

---

# Installation & Setup

## Backend Setup

```bash
cd job_aggregator_ai

python -m venv venv

# Windows
venv\Scripts\activate

pip install -r requirements.txt

uvicorn main:app --reload
```

---

## Frontend Setup

```bash
cd job_aggregator_frontend

npm install

npm run dev
```

---

# Future Scope

* AI Interview Preparation
* Real-Time Chat System
* Video Interview Integration
* AI Resume Builder
* AI Career Roadmaps
* Multi-Language Support
* Mobile Application
* Advanced Analytics Dashboard

---

# Screens Included

* Landing Page
* Login & Signup
* Candidate Dashboard
* Employer Dashboard
* Admin Dashboard
* Resume Upload
* AI Profile Analysis
* Recommended Jobs
* Subscription System

---

# Author

## DRASHTANTA SAXENA

AI & Full Stack Developer

Passionate about building AI-powered scalable SaaS platforms, intelligent automation systems, and modern web applications.

---

# License

This project is built for educational, research, and portfolio purposes.

---

# TalentFlow AI

### Transforming Recruitment with Artificial Intelligence
