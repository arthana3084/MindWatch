# 🧠 MindWatch

A machine learning-based web application that analyzes user-provided social media text to identify potential signs of anxiety and depression using Natural Language Processing (NLP) and TF-IDF feature extraction.

---

## 📖 Overview

MindWatch is a web application developed to assist in the early identification of potential mental health concerns through text analysis. Users provide text describing their thoughts or feelings, and the system analyzes it using a trained machine learning model. Based on the prediction, a dynamic questionnaire is presented to provide a more comprehensive assessment of the user's mental well-being. The application also generates a downloadable PDF report summarizing the analysis.

> **Disclaimer:** This project is intended for educational and awareness purposes only. It is not a substitute for professional medical advice, diagnosis, or treatment.

---

## ✨ Features

- Analyze user-provided text using Machine Learning
- Detect potential signs of Depression, Anxiety, or Normal mental state
- Dynamic questionnaire based on initial text analysis
- Overall mental well-being assessment
- Downloadable PDF report
- Mental health support resources
- Simple and responsive web interface

---

## 🛠️ Technologies Used

### Frontend
- HTML
- CSS

### Backend
- Python
- Flask

### Machine Learning
- Scikit-learn
- Pandas
- TF-IDF Vectorizer
- Logistic Regression

---

## 🧠 Machine Learning Workflow

1. User enters text.
2. Text is preprocessed.
3. TF-IDF converts text into feature vectors.
4. Logistic Regression predicts the mental health category.
5. A questionnaire is generated based on the prediction.
6. Questionnaire responses are evaluated.
7. Overall assessment and PDF report are generated.

---

## 📂 Project Structure

```text
MindWatch/
│
├── static/
├── templates/
├── app.py
├── model.pkl
├── train_model.py
├── requirements.txt
├── dataset.csv
├── .gitignore
└── README.md
```

---

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/arthana3084/MindWatch.git
```

Navigate to the project folder

```bash
cd MindWatch
```

Install the required packages

```bash
pip install -r requirements.txt
```

Run the application

```bash
python app.py
```

Open your browser and visit

```
http://localhost:5000
```

---

## 📊 Dataset

The machine learning model was trained using a publicly available mental health dataset from Kaggle. The dataset was filtered to include three categories:

- Depression
- Anxiety
- Normal

---

## 📸 Screenshots

Screenshots of the application are available in the **Screenshots** folder.

- Home Page
- User Details
- Text Input
- Dynamic Questionnaire
- Analysis Result
- PDF Report

---

## 🔮 Future Enhancements

- User authentication
- Cloud database integration
- Deep learning-based text classification
- Multi-language support
- Personalized recommendations
- Mobile application

---

## 👥 Team

**Team Lead**
- Arthana Sreekesh

**Team Members**
- Arsha Biju Thottathil
- Hridhya Sara Sunil

---

## 📄 License

This project was developed as part of a B.Tech Mini Project for educational purposes.
