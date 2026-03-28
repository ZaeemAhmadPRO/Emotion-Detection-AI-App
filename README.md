# Emotion Detection Web Application

## Overview
This project is a web-based application that analyzes user input text and detects emotions using a cloud-based Natural Language Processing (NLP) model.

The system identifies five emotions — anger, disgust, fear, joy, and sadness — and determines the dominant emotion in the input text.

---

## Features
- Detects multiple emotions from user input text
- Identifies the dominant emotion
- Handles invalid or blank input gracefully
- Web-based interface using Flask
- Modular Python package design
- Unit tested for correctness
- Static code analysis with 10/10 PyLint score

---

## Technologies Used
- Python
- Flask (Web Framework)
- REST API (IBM Watson NLP)
- JSON Parsing
- Unit Testing (unittest)
- PyLint (Code Quality)
- Git & GitHub

---

---

## How to Run the Project

### 1. Clone the repository
git clone https://github.com/YOUR_USERNAME/emotion-detection-webapp.git
cd emotion-detection-webapp


### 2. Install dependencies
pip install -r requirements.txt

### 3. Run the application
python server.py


### 4. Open in browser
http://localhost:5000


---

## Example Usage

### Input:
I think I am having fun


### Output:
For the given statement, the system response is 'anger': X, 'disgust': X, 'fear': X, 'joy': X and 'sadness': X. The dominant emotion is joy.


---

## Error Handling
- Displays an error message for empty input:
Invalid text! Please try again!


---

## Key Highlights
- Integrated external NLP service via REST API
- Designed modular and reusable Python package
- Implemented error handling for API responses
- Achieved 10/10 code quality score using PyLint
- Deployed as a web application using Flask

---

## Future Improvements
- Deploy on cloud platforms (Render / Heroku)
- Improve UI/UX of the frontend
- Add support for more languages
- Enhance model accuracy with custom ML models

---

## Author
Zaeem Ahmad
