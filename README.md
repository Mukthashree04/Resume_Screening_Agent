# AI_Resume_Analyser_withJD
The Resume and Job Description Analyzer allows users to upload their resumes in PDF format and job descriptions in TXT format. The application extracts key information from the resume, analyzes the content, and provides insights on how well the resume aligns with the job description.

# Features

1) Upload resume (PDF) and job description (TXT)

2) Extracts text from resume using PyPDF2

3) Reads job description from a text file

4) Computes simple word-overlap similarity

5) Displays JSON-like extracted entities and text results

# Requirements

Python 3.8+

pip (for installing dependencies)

Python dependencies
gradio
PyPDF2

# Install with:

pip install -r requirements.txt
# or
pip install gradio PyPDF2

# How to run (local)

Create a virtual environment (recommended):

python -m venv venv
source venv/bin/activate   # Linux/macOS
venv\Scripts\activate    # Windows

# Install dependencies:

pip install -r requirements.txt

Run the app:

python app.py

Open the URL printed by Gradio (usually http://127.0.0.1:7860) in your browser and upload files.

# How to use

Upload a PDF for the resume and a TXT file for the job description.

The app will show JSON with top overlapping words, a similarity percentage, and the first 300 characters of the JD.
