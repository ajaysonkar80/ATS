# ATS using PyPDF2 Gemini Pro 1.0

## Smart ATS (Applicant Tracking System)

Welcome to the Smart ATS project! This application leverages AI to evaluate resumes based on a given job description, providing valuable feedback on matching percentage and missing keywords. It's designed to help job seekers improve their resumes for a better chance in a competitive job market.

## Features

- **Resume Parsing:** Upload a PDF resume and extract its text.
- **Job Description Analysis:** Input the job description you want to match.
- **AI Evaluation:** Uses Google's Gemini AI to analyze and provide a match percentage, missing keywords, and a profile summary.
- **User-Friendly Interface:** Built with Streamlit for a simple and interactive experience.

## Install requirements.txt 
1. Install requirements.txt `pip install -r requirements.txt`

## Add your api key
2. create a .env file and store the gemini api key as `GOOGLE_API_KEY="your api key"`

## Create a virtual enviorment
3. Install virtual environment `python -m pip install virtualenv`
4. Create a virtual enviorment  `python -m venv venv`
5. Start the virtual enviorment `venv\Scripts\activate.ps1` 

## Run app using streamlit
5. Run the app usigng `streamlit run app.py`
