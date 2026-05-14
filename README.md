# nlp-customer-feedback-analysis
NLP-based customer feedback analysis system using TF-IDF, Logistic Regression, Naïve Bayes, and NMF for sentiment, intent, and topic analysis.
# NLP-Based Customer Feedback Analysis System

## Introduction
This project analyzes e-commerce customer feedback using NLP techniques.

The system performs:
- Sentiment Analysis
- Intent Classification
- Topic Modeling

It supports mixed English and Roman Urdu customer reviews.

---

## Features
- Text preprocessing
- TF-IDF feature extraction
- Logistic Regression sentiment analysis
- Naïve Bayes intent classification
- NMF topic modeling
- Gradio interactive interface

---

## Technologies Used
- Python
- Scikit-learn
- NLTK
- Pandas
- Gradio

---

## Models Used
- Logistic Regression
- Naïve Bayes
- NMF

---

## Dataset
Customer reviews dataset containing:
- Positive reviews
- Complaints
- Refund requests
- Delivery issues

---

## How to Run

Install requirements:

```bash
pip install -r requirements.txt
```

Run Gradio app:

```bash
python gradio_app.py
```

---

## Example Input

```text
product damaged hai refund chahiye
```

## Example Output

- Sentiment: Negative
- Intent: Refund Request
- Topic: refund, damaged, return

---

## Project Structure

```text
NLP-Customer-Feedback-Analysis/
│
├── dataset/
├── notebooks/
├── app/
├── models/
├── screenshots/
├── requirements.txt
├── README.md
└── report.pdf
```

---

## Author

Ayesha Imran  
23F-0012  
FAST University
