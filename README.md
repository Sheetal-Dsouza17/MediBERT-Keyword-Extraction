# MediBERT-Keyword-Extraction
AI-Powered Medical Diagnosis Classifier

# Keyword Extraction and Disease Prediction

This project involves developing a system to extract keywords from medical records and use them to predict diseases. The system utilizes pretrained model for keyword extraction and leverages machine learning models for disease prediction.

## Features
- Extracts medical keywords from input text records.
- Stores extracted keywords in an Excel file for analysis.
- Predicts diseases based on extracted keywords.

## Technologies Used
- **Programming Language:** Python
- **Libraries:** pandas, streamlit, NumPy, docx (python-docx) ,re, transformers, torch, joblib
- **Tools:** Excel for data storage, vscode as IDE

## Setup Instructions

### Prerequisites
1. Python 3.8 or later.
2. Virtual environment tools (e.g., `venv` or `conda`).
3. Required Python libraries (specified below).

## Project Structure
```
Keyword-Extraction-Model/
│
├── main.py                 # Main script to run the application
├── keyword_extraction.py   # Module for extracting keywords
├── disease_prediction.py   # Module for disease prediction
├── requirements.txt        # Python dependencies
├── README.md               # Project documentation
└── data/                   # Directory for storing input/output files
    ├── input/              # Input medical records
    └── output/             # Extracted keywords and results
```

## How It Works
1. **Keyword Extraction:**
   - Uses Hugging Face distilBERT pretrained model to extract medical keywords from unstructured text.

2. **Data Storage:**
   - Stores the extracted keywords into an Excel file using pandas and openpyxl.

3. **Disease Prediction:**
   - Maps extracted keywords to predefined disease categories and predicts potential diagnoses.

Feel free to contact me for any questions or suggestions!
