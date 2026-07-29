# AI-Powered Digital Identity System

## Overview

The AI-Powered Digital Identity System is a smart document management platform that helps students and professionals organise their academic and professional documents in one place. Instead of manually searching through folders, users can upload documents and use AI-powered search to quickly find certificates, resumes, project reports, internship letters, and other important files.

The system automatically extracts document information, categorises files, and creates a searchable digital identity for each user.

---

## Problem Statement

Students and professionals often store important documents across multiple folders and devices. Finding the right document during placements, internships, higher studies, or job applications becomes difficult and time-consuming.

---

## Solution

This project uses Artificial Intelligence and Natural Language Processing (NLP) to automatically organise uploaded documents by extracting useful information such as:

- Document Title
- Category
- Issuing Organisation
- Skills
- Dates
- Keywords

The extracted information is stored in a structured database and can be searched using natural language queries.

---

## Features

- AI-powered document analysis
- Automatic metadata extraction
- Semantic document search
- Smart document categorisation
- Digital identity creation
- Timeline view of achievements
- Fast document retrieval
- User-friendly interface

---

## Technology Stack

### Frontend
- HTML
- CSS
- JavaScript

### Backend
- Python
- Flask

### AI & Machine Learning
- OpenAI API
- LangChain
- Sentence Transformers

### Database
- SQLite
- ChromaDB (Vector Database)

### Libraries
- PyPDF2
- Pandas
- NumPy

---

## Project Structure

```
AI-Digital-Identity-System/
│
├── app.py
├── requirements.txt
├── README.md
├── .gitignore
│
├── templates/
├── static/
├── uploads/
├── chroma_db/
├── database/
└── utils/
```

---

## Installation

### Clone the repository

```bash
git clone https://github.com/yourusername/AI-Digital-Identity-System.git
```

### Move into the project directory

```bash
cd AI-Digital-Identity-System
```

### Create a virtual environment

```bash
python -m venv venv
```

### Activate the virtual environment

Windows

```bash
venv\Scripts\activate
```

Mac/Linux

```bash
source venv/bin/activate
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Run the application

```bash
python app.py
```

---

## Usage

1. Upload academic or professional documents.
2. AI extracts important information.
3. Documents are automatically categorised.
4. Search using natural language.
5. View and download documents whenever needed.

---

## Future Improvements

- User authentication
- Cloud storage integration
- OCR support for scanned documents
- Multi-language document analysis
- Resume builder
- Mobile application
- AI career recommendations

---

## Applications

- College students
- Job seekers
- Professionals
- Recruiters
- Educational institutions

---

## Author

**Kaveri Dhatrak**

Final Year B.E. Artificial Intelligence & Data Science Student

---

## License

This project is developed for educational and hackathon purposes.
