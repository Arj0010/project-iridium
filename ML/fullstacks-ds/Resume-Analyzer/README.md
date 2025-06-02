# Resume Analyzer – Full Stack Data Science Project

## Objective
An interactive web app that accepts resumes (PDF/DOCX), extracts key information, and predicts job-fit using a machine learning model.

## Stack
- Backend: Flask
- Frontend: HTML/CSS (Flask templates)
- ML: Scikit-learn
- Parsing: pdfminer.six, python-docx, spaCy
- Deployment: To be decided (Heroku, AWS, etc.)

## Features
- Resume upload and parsing
- Named entity extraction (name, email, skills)
- ML-based prediction for job fit (TBD)
- Interactive dashboard (planned)

## Folder Structure
resume-analyzer/
├── app/ # Flask app and logic
├── models/ # Trained ML models
├── templates/ # HTML templates
├── static/ # CSS, JS
├── data/ # Resumes and training data
├── requirements.txt
├── README.md
└── .gitignore

## Setup
```bash
python -m venv .venv
source .venv/bin/activate  # or .venv\Scripts\activate on Windows
pip install -r requirements.txt

## License
Update progressively as features get implemented.
