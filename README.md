### this is my network security projects for phising data
# Network Security Project - Phishing Website Detection

## Overview
This project is designed to classify websites as *authentic or phishing* based on phishing data using a trained machine learning model. The model is integrated into a *FastAPI* web application where users can upload a dataset containing website details and get predictions.

## Features
- *Phishing Detection:* Predicts whether a website is legitimate or a phishing attempt.
- *FastAPI Integration:* Provides a user-friendly interface for dataset uploads and predictions.
- *Modular Code Structure:* Includes separate components for data ingestion, validation, transformation, model training, and pipeline execution.
- *Custom Logging and Exception Handling:* Ensures smooth debugging and execution tracking.

## Project Structure

📂 network_security
│── 📂 components
│   │── data_ingestion.py
│   │── data_validation.py
│   │── transformation.py
│   │── trainer.py
│
│── 📂 constant
│   │── training_pipeline.py
│   │── common_constants.py
│
│── 📂 entity
│   │── artifact_entity.py
│   │── config_entity.py
│
│── 📂 exception
│   │── exception.py
│
│── 📂 logging
│   │── logger.py
│
│── 📂 pipeline
│   │── training_pipeline.py
│
│── 📂 utils
│   │── 📂 main_utils
│   │   │── utils.py
│   │── 📂 ml_utils
│   │   │── classification_matrix.py
│
│── 📂 model
│   │── estimator.py
│
│── 📂 templates
│   │── table.html
│
│── app.py
│── requirements.txt
│── setup.py


## Installation

### Prerequisites
- Python 3.8+
- FastAPI
- Required libraries from requirements.txt

### Steps to Install
bash
# Clone the repository
git clone https://github.com/your-repo/network_security.git
cd network_security

# Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt


## Running the Application
bash
# Run the FastAPI server
python app.py

After running app.py, FastAPI will launch a *prebuilt webpage* where you can upload a dataset containing phishing data for prediction.

Open your browser and visit:

http://127.0.0.1:8000/docs


## Demo Video
For a detailed walkthrough, watch the demo video here:
[![Watch the video](https://img.youtube.com/vi/YOUR_VIDEO_ID/maxresdefault.jpg)](https://www.youtube.com/watch?v=YOUR_VIDEO_ID)

## Contributing
Feel free to fork this repository and create pull requests with improvements or bug fixes.

## License
This project is licensed under the *MIT License*.

---
🚀 *Happy Coding!
