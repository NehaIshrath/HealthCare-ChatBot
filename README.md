# HealthCare-ChatBot
A Streamlit-based AI chatbot designed to provide healthcare-related assistance, including symptom analysis, medication guidance, and appointment scheduling. Built using Hugging Face Transformers and NLTK for natural language processing.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [How to Run the Code](#how-to-run-the-code)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)

## Introduction
This project is a healthcare chatbot built using **Streamlit**, **Hugging Face Transformers**, and **NLTK**. It provides immediate responses to common healthcare-related queries, such as symptoms, medications, and appointment scheduling.

## Features
- **Symptom Analysis:** Provides preliminary advice for common symptoms like sneezing, coughing, etc.
- **Medication Guidance:** Offers reminders and advice on taking prescribed medications.
- **Appointment Scheduling:** Helps users schedule appointments with healthcare providers.

## Technologies Used
- **Streamlit:** For building the user interface.
- **Hugging Face Transformers:** For natural language processing (NLP) using the BERT model.
- **NLTK:** For text preprocessing (tokenization, stopword removal, etc.).

## How to Run the Code
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/HealthCare-ChatBot.git
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
3. Run the Streamlit app:
   ```bash
   streamlit run app.py
  (or)
  ```bash
  python -m streamlit run app.py
