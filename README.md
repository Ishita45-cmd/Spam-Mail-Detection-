# 📧 Spam Email Detection using Machine Learning

##  Project Overview

Spam Email Detection is a Machine Learning and Natural Language Processing (NLP) project that classifies messages as **Spam** or **Ham (Non-Spam)**. The model learns patterns from labeled text messages and predicts whether a new message is unwanted or legitimate.

This project demonstrates the complete NLP pipeline, including text preprocessing, feature extraction, model training, and performance evaluation using supervised machine learning algorithms.

---

##  Objective

Build a machine learning classifier capable of accurately identifying spam messages based on their textual content.

---

## Dataset

* **SMS Spam Collection Dataset**
* **Enron Email Dataset** (Optional)

The dataset contains text messages labeled as:

* **Spam**
* **Ham (Non-Spam)**

---

##  Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* NLTK
* Matplotlib
* Seaborn

---

##  Project Workflow

### 1. Data Loading

* Import the dataset.
* Explore spam and ham message distribution.

### 2. Text Preprocessing

* Convert text to lowercase
* Remove punctuation
* Remove stopwords
* Tokenize text
* Clean unwanted characters

### 3. Feature Extraction

Convert text into numerical vectors using:

* Bag of Words (BoW)
* TF-IDF Vectorization

### 4. Model Training

Train machine learning models such as:

* Multinomial Naive Bayes
* Logistic Regression

### 5. Model Evaluation

Evaluate performance using:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

---

##  Results

The trained model successfully distinguishes spam and non-spam messages with high accuracy. Performance metrics demonstrate the effectiveness of text preprocessing and feature extraction techniques in building a reliable spam detection system.

---

##  Project Structure

```text
Spam-Email-Detection/
│
├── dataset/
│   └── spam.csv
│
├── notebooks/
│   └── Spam_Email_Detection.ipynb
│
├── models/
│
├── images/
│
├── requirements.txt
├── README.md
└── LICENSE
```

---

##  Skills Gained

* Natural Language Processing (NLP)
* Text Preprocessing
* Feature Extraction
* TF-IDF & Bag of Words
* Machine Learning Classification
* Model Evaluation
* Python Data Analysis

---

##  Future Improvements

* Deploy the model using Flask or Streamlit
* Integrate deep learning models (LSTM/BERT)
* Build a web interface for real-time spam prediction
* Improve accuracy with advanced preprocessing techniques

---

## How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/Spam-Email-Detection.git
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Run the Jupyter Notebook or Python script.

---

