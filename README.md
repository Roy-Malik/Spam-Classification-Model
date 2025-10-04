# 📩 Spam Classification using Machine Learning

This project implements a **Spam Detection System** that classifies SMS messages as either **spam** or **ham (not spam)**.  
It covers the full pipeline: dataset preprocessing, feature extraction, model training, evaluation, and saving the trained model.

---

## 🚀 Project Overview

Spam messages are a common cyber threat. Building an automated spam classifier helps in filtering malicious or unwanted content.  
In this project, I trained a machine learning model on the **SMSSpamCollection dataset** to accurately classify text messages.

---

## 📂 Repository Contents

- `Spam-classification.ipynb` → Jupyter Notebook with the complete workflow  
- `SMSSpamCollection` → Raw dataset used for training  
- `spam_detection_model.joblib` → Trained model file (can be loaded directly for predictions)  
- `README.md` → Project description & usage guide  

---

## 🛠️ Workflow Steps

1. **Dataset Loading**  
   - Used the `SMSSpamCollection` dataset (labeled SMS messages).  
   - Explored class distribution (spam vs ham).  

2. **Preprocessing**  
   - Text cleaning (lowercasing, punctuation removal, stopword removal).  
   - Tokenization and vectorization.  

3. **Feature Extraction**  
   - Implemented `TF-IDF` (Term Frequency – Inverse Document Frequency).  

4. **Model Training & Evaluation**  
   - Tried classifiers (Naive Bayes / Logistic Regression).  
   - Evaluated with metrics like **accuracy, precision, recall, F1-score**.  

5. **Model Saving**  
   - Exported trained model using `joblib` for reusability.  

---

## 📊 Results

- Achieved high accuracy (~98–99%).  
- Precision/Recall balanced — effective in catching spam without misclassifying legitimate texts.  

---

## 🔧 How to Run the Project

### 1. Clone the repository
```bash
git clone https://github.com/<your-username>/spam-classification.git
cd spam-classification
