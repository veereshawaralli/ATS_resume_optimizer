
# ATS Resume Optimizer (Flask + ML)

This project analyzes your resume against a job description, extracts top keywords,
computes an ATS match score, and generates improved bullet points.

## Features
- ATS score calculation
- Keyword extraction using TF-IDF
- Missing keyword detection
- Automatic bullet-point generation
- Simple Flask web interface

## How to Run
```bash
pip install flask scikit-learn numpy
python app.py
```

Then open: `http://127.0.0.1:5000`

## Files
- `app.py` – main application
- `README.md` – project documentation
