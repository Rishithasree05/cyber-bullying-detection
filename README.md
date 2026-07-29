# 🛡️ Cyber Bullying Detection using Machine Learning

## 📌 Project Overview

Cyberbullying has become a major concern on social media platforms. This project uses **Machine Learning** and **Natural Language Processing (NLP)** techniques to automatically detect and classify cyberbullying text into different categories.

The system analyzes user-entered text and predicts whether it contains cyberbullying content. It also provides a confidence score and a severity level to assist with moderation decisions.

---

## 🚀 Features

- Detects cyberbullying in text
- Classifies text into multiple categories:
  - Age
  - Gender
  - Religion
  - Ethnicity
  - Other Cyberbullying
  - Not Cyberbullying
- Text preprocessing using NLP
- TF-IDF feature extraction
- Machine Learning classification
- Real-time text prediction
- Confidence score generation
- Severity level prediction
- Suggests moderation actions

---

## 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- NLTK
- Scikit-learn
- Imbalanced-learn
- Joblib

---

## 📂 Dataset

The project uses the **Cyberbullying Tweets Dataset**, containing tweets categorized into six classes.

### Classes

- Not Cyberbullying
- Age
- Gender
- Religion
- Ethnicity
- Other Cyberbullying

The dataset is cleaned and preprocessed before training the model. :contentReference[oaicite:0]{index=0}

---

## 🔄 Project Workflow

1. Load Dataset
2. Data Preprocessing
3. Text Cleaning
4. Tokenization
5. Stopword Removal
6. Lemmatization
7. Label Encoding
8. Dataset Balancing
9. TF-IDF Vectorization
10. Model Training
11. Model Evaluation
12. Real-Time Prediction

---

## 🧠 Machine Learning Model

- Logistic Regression
- TF-IDF Vectorizer
- RandomOverSampler
- Label Encoder

The trained model, vectorizer, and label encoder are saved using Joblib for later use. :contentReference[oaicite:1]{index=1}

---

## 📊 Model Performance

**Accuracy:** Approximately **83%**

The model is evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Classification Report

The reported evaluation achieved an overall accuracy of about **83%** on the test dataset. :contentReference[oaicite:2]{index=2}

---

## 💬 Example Prediction

Input:

```
People of that religion are disgusting.
```

Output:

```
Predicted Category: Religion
Confidence: 0.41
Severity: LOW
Suggested Action: Log and monitor.
```

The notebook also demonstrates predictions for several sample inputs with confidence scores and suggested moderation actions. :contentReference[oaicite:3]{index=3}

---

## 📁 Project Structure

```
Cyber-Bullying-Detection/
│
├── Bullying.ipynb
├── cyber_model.pkl
├── tfidf_vectorizer.pkl
├── label_encoder.pkl
├── README.md
└── Dataset/
```

---

## ▶️ How to Run

1. Clone this repository

```bash
git clone https://github.com/Rishithasree05/cyber-bullying-detection.git
```

2. Install dependencies

```bash
pip install pandas numpy nltk scikit-learn imbalanced-learn joblib
```

3. Open the notebook in Google Colab or Jupyter Notebook.

4. Upload the dataset.

5. Run all cells.

6. Enter text to detect cyberbullying.

---

## 🎯 Future Improvements

- Deep Learning (LSTM/BERT)
- Larger real-world datasets
- Web application using Flask or Streamlit
- REST API integration
- Real-time social media monitoring
- Multilingual cyberbullying detection

---

## 👩‍💻 Author

**Rishitha Sree**

B.Tech – Artificial Intelligence & Data Science

GitHub: https://github.com/Rishithasree05

---

## ⭐ If you found this project useful, consider giving it a Star!
