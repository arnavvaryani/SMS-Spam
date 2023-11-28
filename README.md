# SMS Spam Detection

## Introduction
This project is a web-based application for detecting SMS spam. It utilizes machine learning algorithms to classify SMS messages as either 'spam' or 'ham' (not spam). The application is built using Python's Flask framework and uses pre-trained models for the classification task.

## Features
- Web interface for real-time SMS spam detection.
- Utilizes a pre-trained machine learning model for accurate classification.
- Simple and user-friendly UI.

## Prerequisites
- Python 3.x
- Flask
- Joblib
- NLTK

## Installation

### Clone the Repository
```
git clone [repository-url]
cd SMS-Spam-Detection
```
Replace `[repository-url]` with the URL of your Git repository.

### Setting Up the Environment
It is recommended to use a virtual environment:
```
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

### Install Required Packages
Install the necessary Python packages:
```
pip install -r requirements.txt
```

### Run the Application
```
export FLASK_APP=app.py  # On Windows use `set FLASK_APP=app.py`
flask run
```
Access the web application at `http://127.0.0.1:5000/` in your browser.

## Usage
- Enter an SMS message into the provided text field on the web interface.
- Submit the message to see if it is classified as 'spam' or 'ham'.
