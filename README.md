# Lexify ⚖️

*Empowering anyone to understand their contracts by instantly translating dense legal jargon into plain English.*

---

[![Built with Google Gemini](https://img.shields.io/badge/Built%20with-Google%20Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white)](https://ai.google.dev/)
[![Powered by Google Cloud](https://img.shields.io/badge/Powered%20by-Google%20Cloud-FBBC05?style=for-the-badge&logo=google-cloud&logoColor=white)](https://cloud.google.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

## The Problem

Legal documents are a barrier for millions, filled with confusing language that creates risk and uncertainty. Lexify is an AI-powered web application designed to break down this barrier, making legal understanding accessible, instant, and free.

## Core Features

* **📄 One-Click Analysis**: Upload or paste any legal document (PDF, DOCX, text).
* **✨ Plain English Summary**: Instantly receive a structured summary highlighting key financial terms, dates, and obligations.
* **❓ Interactive Q&A**: Ask specific questions about the document in natural language and get clear answers.
* **🔍 Jargon Buster**: Click on any confusing legal term to get a simple, contextual explanation.

## Tech Stack

* **AI Core**: Google Gemini 1.5 Pro via Google Cloud AI Platform
* **Backend**: Python (Flask / FastAPI)
* **Frontend**: React (Next.js) / Streamlit
* **Deployment**: Google Cloud Run

## Getting Started

### Prerequisites

* Python 3.9+
* Node.js 18+ (if using a React/Next.js frontend)
* A Google Cloud account with the AI Platform API enabled.

### Installation & Setup

1.  **Clone the repository:**
    ```sh
    git clone <your-repo-url>
    cd Lexify
    ```

2.  **Setup Backend (Python):**
    ```sh
    # Create and activate a virtual environment
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`

    # Install dependencies
    pip install -r requirements.txt
    ```

3.  **Setup Frontend (if applicable):**
    ```sh
    # Navigate to frontend directory
    cd frontend

    # Install dependencies
    npm install
    ```

4.  **Run the application:**
    ```sh
    # Run backend server
    python app.py

    # Run frontend dev server
    npm run dev
    ```

---
*This project was built for the Google Cloud Gen AI Exchange Hackathon 2025.*
