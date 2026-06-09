# 🎫 Support Ticket Classification & Prioritization System

## 📌 Project Overview

Customer support teams handle hundreds of tickets daily, making manual categorization and prioritization time-consuming and error-prone.

This project uses **Natural Language Processing (NLP)** and **Machine Learning** to automatically:

* Classify support tickets into categories
* Predict ticket priority levels
* Reduce manual effort in support operations
* Improve response times for critical issues

This project was developed as part of the **Future Interns Machine Learning Internship – Task 2 (2026)**.
---

## 🎯 Objectives

The system is designed to:

* Analyze customer support ticket descriptions
* Categorize tickets automatically
* Predict ticket priority (High, Medium, Low)
* Assist support teams in efficient ticket management

---

## 📂 Dataset

Dataset Used: **Customer Support Tickets Dataset**

### Features Used

| Column             | Description           |
| ------------------ | --------------------- |
| Ticket Description | Customer issue text   |
| Ticket Type        | Ticket category label |
| Ticket Priority    | Priority level label  |

---

## 🛠️ Technologies Used

### Programming Language

* Python

### Libraries

* Pandas
* NumPy
* NLTK
* Scikit-learn
* Matplotlib
* Seaborn

### Machine Learning Techniques

* Natural Language Processing (NLP)
* TF-IDF Vectorization
* Logistic Regression
* Naive Bayes (Optional Comparison)

---

## 🔄 Workflow

### 1. Data Loading

* Import dataset
* Select required columns
* Handle missing values

### 2. Text Preprocessing

* Convert text to lowercase
* Remove special characters
* Remove stopwords
* Clean ticket descriptions

### 3. Feature Engineering

* Transform text into numerical vectors using TF-IDF

### 4. Model Training

#### Category Classification

Predicts:

* Technical Issue
* Billing
* Account Access
* General Inquiry
* Other Categories

#### Priority Prediction

Predicts:

* High
* Medium
* Low

### 5. Model Evaluation

Evaluation Metrics:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

---

## 📊 Machine Learning Models

### Logistic Regression

Used for:

* Ticket Category Classification
* Ticket Priority Prediction

### Naive Bayes (Optional)

Used as a benchmark model for text classification.

---

## 🚀 Example Prediction

### Input Ticket

"My payment failed but money was deducted from my account."

### Output

Category: Billing

Priority: High

---

## 📈 Business Impact

This solution helps organizations:

* Automate ticket routing
* Reduce manual sorting efforts
* Improve response times
* Prioritize urgent customer issues
* Enhance customer satisfaction

---

## 📁 Project Structure

```text
support-ticket-classification/
│
├── data/
│   └── customer_support_tickets.csv
│
├── notebooks/
│   └── Support_Ticket_Classification.ipynb
│
├── screenshots/
│
├── README.md
│
├── requirements.txt
│
└── models/
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/dineshdabbera/support-ticket-classification.git
```

Move into the project folder:

```bash
cd support-ticket-classification
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run Jupyter Notebook:

```bash
jupyter notebook
```

---

## 📋 Requirements

```text
pandas
numpy
nltk
scikit-learn
matplotlib
seaborn
```

---

## 🎓 Learning Outcomes

Through this project, I gained experience in:

* Natural Language Processing (NLP)
* Text preprocessing
* Feature extraction using TF-IDF
* Machine Learning classification
* Model evaluation and analysis
* Real-world support automation systems

---

## 👨‍💻 Author

**Dabbera Dinesh**

B.Tech Computer Science and Engineering
VIT-AP University

LinkedIn:
https://www.linkedin.com/in/dinesh-dabbera

Email:
[dinesh07148@gmail.com](mailto:dinesh07148@gmail.com)

---

## 📜 License

This project is created for educational and internship purposes.
