## Intelligent Enterprise Assistant
Enhancing Organizational Efficiency through AI-driven Chatbot Integration

An AI-powered chatbot platform designed to assist employees in large public sector organizations by answering queries related to HR policies, IT support, company events, and internal procedures.

The system integrates Deep Learning, Natural Language Processing (NLP), and Document Processing to provide fast and accurate responses while ensuring secure access through Two-Factor Authentication (2FA).

## Problem Statement

Problem ID: SIH1706

Develop a chatbot using deep learning and natural language processing that can:

Answer employee queries related to HR, IT support, and company policies

Process uploaded documents to extract text, summarize content, and identify keywords

Support multiple users simultaneously

Provide responses within 5 seconds

Implement 2-factor authentication for secure access
## Objectives

* Improve organizational efficiency through automated assistance

* Provide instant responses to employee queries

* Reduce workload on HR and IT support teams

* Enable intelligent document analysis

* Ensure secure chatbot interaction using authentication mechanisms

 * Key Features
 * AI Chatbot

* Natural Language Processing for query understanding

* Context-aware responses

* Supports HR, IT, and organizational queries

* Chat history storage

## Document Processing

* Upload PDF or DOCX documents

* Extract text from documents

* Generate document summaries

* Keyword extraction

## Security

* Email-based Two-Factor Authentication (2FA)

* Password hashing

* Secure login system

## Performance

Handles minimum 5 concurrent users

Response time under 5 seconds

## Admin Dashboard

* Manage uploaded documents

* View chatbot logs

* Monitor frequently asked 




## System Architecture



User Interface (React.js)
        │
        ▼
Backend API (FastAPI / Node.js)
        │
        ▼
AI Processing Layer
(NLP Model + Document Processing)
        │
        ▼
Database
(PostgreSQL / MongoDB)


# Tech Stack

### Frontend

* **HTML5** – Structure of the website
* **CSS3** – Styling and responsive design
* **JavaScript (Vanilla JS)** – Interactive chatbot interface and UI functionality

### Backend

* **Python (Flask / FastAPI)** – API handling and chatbot logic

### AI & NLP

* **Natural Language Processing (NLP)**
* **Machine Learning / Deep Learning models** for understanding employee queries

### Document Processing

* **Python Libraries**

  * PyPDF2 – Extract text from documents
  * NLTK / SpaCy – Text processing
  * Summarization algorithms

### Database

* **MySQL / SQLite** – Store users, chat history, and documents

### Authentication

* **Email OTP based Two-Factor Authentication (2FA)**

---

# Project Structure

Intelligent-Enterprise-Assistant
│
├── index.html
├── login.html
├── chatbot.html
│
├── css
│   └── styles.css
│
├── js
│   ├── chatbot.js
│   ├── auth.js
│   └── document.js
│
├── backend
│   └── app.py
│
└── README.md


## OUTPUT:




