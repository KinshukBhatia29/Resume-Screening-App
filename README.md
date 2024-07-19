# Resume-Screening-App
Flask-based resume parser and job recommendation app using ML models for text categorization. Extracts contact info, skills, education, and predicts job fit from uploaded resumes. Interactive UI included
## Features

- Upload a resume (PDF or TXT format)
- Parse the resume to extract text content
- Clean and preprocess the text
- Predict the job category of the resume
- Recommend suitable job roles
- Extract contact information (phone number and email)
- Extract skills and education information
- Display extracted information on the web interface

## Requirements

- Python 3.6+
- Flask
- PyPDF2
- scikit-learn
- pandas
- numpy
- re
- pickle
  
  ## Project Structure

- `app.py`: Main application script
- `templates/resume.html`: HTML template for the web interface
- `models/`: Directory to store the machine learning models

  ## Ensure the models are in the `models` directory:

- `rf_classifier_categorization.pkl`
- `tfidf_vectorizer_categorization.pkl`
- `rf_classifier_job_recommendation.pkl`
- `tfidf_vectorizer_job_recommendation.pkl`
