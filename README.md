# SPAM-EMAIL-DETECTION_Soft-Grow-Tech
A Machine Learning project that detects whether an email is spam or not using TF-IDF and Naive Bayes. Built using Python and Scikit-learn as part of an ML internship project.
# Spam Email Detection using Machine Learning

## 📌 Project Overview

This project builds a **Machine Learning model** that detects whether an email is **Spam** or **Not Spam**.
The system uses **Natural Language Processing (NLP)** and **Machine Learning algorithms** to analyze email text and classify it accordingly.

This project was developed as part of a **Machine Learning Internship Project** to gain hands-on experience in data preprocessing, feature extraction, and predictive modeling.

---

## 🎯 Objectives

* Detect spam emails automatically
* Apply text preprocessing techniques
* Convert text into numerical features
* Train and evaluate machine learning models
* Understand real-world applications of ML

---

## 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* TF-IDF Vectorization
* Google Colab

---

## 📂 Dataset

The dataset contains email messages labeled as:

| Label | Description                    |
| ----- | ------------------------------ |
| spam  | Unwanted or promotional emails |
| ham   | Legitimate emails              |

Example:

| Label | Message                        |
| ----- | ------------------------------ |
| spam  | Congratulations! You won $1000 |
| ham   | Let's meet tomorrow            |

---

## ⚙️ Machine Learning Workflow

1. Data Collection
2. Data Preprocessing
3. Text Vectorization (TF-IDF)
4. Train/Test Split
5. Model Training (Naive Bayes)
6. Model Evaluation

---

## 🧠 Model Used

**Multinomial Naive Bayes**

This algorithm is widely used for **text classification problems** such as spam detection.

---

## 📊 Model Performance

Typical accuracy achieved:

```
Accuracy: ~96% - 98%
```

Evaluation Metrics:

* Accuracy
* Precision
* Recall
* F1 Score

---

## ▶️ How to Run the Project

1. Clone the repository

```
git clone https://github.com/yourusername/spam-email-detection-ml.git
```

2. Install required libraries

```
pip install pandas numpy scikit-learn
```

3. Run the Python file or Jupyter Notebook

---

## 📌 Example Prediction

Input Email:

```
Congratulations! You have won a free iPhone. Click here to claim.
```

Output:

```
Spam Email
```

## 🚀 Future Improvements

* Deep Learning (LSTM / Transformers)
* Web Application using Streamlit
* Real-time email filtering
* Larger datasets

---

## 👨‍💻 Author

**Saud Ahmed**
BS Artificial Intelligence
Machine Learning Internship Project

---

