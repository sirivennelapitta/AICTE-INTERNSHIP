# AI-Powered Resume Screening and Ranking System

## Project Overview

An AI-powered system that automates the resume screening process by ranking candidates based on job descriptions. It extracts text from resumes, matches skills using AI, generates a summary, and provides improvement suggestions.

## Features

- Resume Parsing (PDF/DOC)
- AI-based Resume Ranking
- AI-powered Resume Summarization
- AI-based Resume Improvement Suggestions
- HR Dashboard for viewing ranked resumes
- Database Integration (PostgreSQL)
- REST API (Flask Backend)
- Frontend (React.js)

## Technologies Used

### Backend:

- Flask (Python)
- PostgreSQL (Database)
- Transformers (AI Model for Resume Analysis)
- PyPDF2, pdfplumber (For Resume Parsing)

### Frontend:

- React.js
- Axios (API calls)

## Installation Guide

### 1. Clone the Repository

```bash
git clone https://github.com/your-repo/resume-screening.git
cd resume-screening
```

### 2. Set Up Backend

```bash
cd backend
pip install -r requirements.txt
python app.py
```

### 3. Set Up Database

```bash
psql -U postgres -d resume_db -f database/schema.sql
```

### 4. Set Up Frontend

```bash
cd frontend
npm install
npm start
```

## API Endpoints

- `POST /upload` - Upload a resume and receive a ranking, summary, and suggestions.
- `GET /ranked` - Get ranked resumes from the database.

## Future Enhancements

- Auto-generated Cover Letter Suggestions
- Interview Question Generator
- Integration with Job Portals

## License

This project is open-source under the MIT License.
