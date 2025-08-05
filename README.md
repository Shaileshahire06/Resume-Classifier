# Resume-Classifier

## Introduction
Resume Classifier is a backend-focused NLP project that categorizes resumes into relevant job fields using GRU architecture for sequence classification. It’s designed to streamline resume sorting and assist recruiters in identifying suitable candidates by analyzing textual content.

## Project Type
Backend

## Deplolyed App
Frontend: Not Applicable
Backend: Jupyter Notebook
Database: Local CSV dataset

## Directory Structure
ResumeClassifier/                
│                     
├── data/                         
│   └── Resume.csv           
├── notebooks/                              
│   └── Resume Classifier.ipynb                  
├── Visuals/                         
├── README.md              


## Video Walkthrough of the project


## Video Walkthrough of the codebase


## Features
- Resume text preprocessing pipeline
- GRU model for job category classification
- Model evaluation using accuracy and confusion matrix

## design decisions or assumptions
- GRU selected for handling sequential resume text due to efficient memory usage
- Labels encoded based on job category
- CSV format used for data due to project scope
- No database connectivity; data loaded directly into memory

## Installation & Getting started
Clone the repo and install required packages:

```bash
git clone https://github.com/Shaileshahire06/Resume-Classifier.git
cd Resume-Classifier
```

## Usage
Example Jupyter notebook usage:

```bash
# Open notebook
jupyter notebook notebooks/resume_preprocessing.ipynb
```

Include screenshots as necessary.

## Credentials
No authentication required in current version.

## APIs Used
No external APIs used — purely self-contained text classification pipeline using Hugging Face and TensorFlow.

## API Endpoints
Not applicable for this version.


## Technology Stack

- Python 3.10
- TensorFlow / Keras
- Hugging Face Transformers
- Jupyter Notebooks
- Pandas & NumPy
