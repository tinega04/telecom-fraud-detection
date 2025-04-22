# 📡 Telecom Fraud Detection with Machine Learning

> End-to-end fraud detection pipeline using telecom call detail records (CDRs).  
> Built with real-world ML workflows, feature engineering, and model evaluation for maximum industry relevance.

---

## 🚀 Project Overview

Fraudulent activity in the telecom industry costs billions annually. This project tackles the problem using supervised machine learning to identify suspicious customer behavior from raw call detail records (CDRs).

The goal: **build a data-driven system that detects telecom fraud using classification algorithms**.

---

## 🧠 Key Features

- ✅ Cleaned and processed raw CDR data for analysis  
- 📊 Explored patterns across time, call types, international activity, and customer service interactions  
- 🏗️ Engineered features for optimal model performance  
- 🤖 Trained a classification model to predict fraud  
- 📈 Evaluated performance using precision, recall, F1-score, and confusion matrix  
- 🔥 Visualized feature importance and model outcomes  

---

## 🛠️ Tech Stack

| Tool         | Purpose                            |
|--------------|-------------------------------------|
| Python       | Core programming language           |
| Pandas       | Data wrangling & preprocessing      |
| NumPy        | Numerical computing                 |
| Scikit-learn | Modeling & evaluation               |
| Matplotlib   | Data visualization                  |
| Seaborn      | Statistical plotting                |
| Jupyter      | Exploratory data analysis notebook  |

---

## 📂 Project Structure

---

## 📈 Results

The best model achieved:

- **Accuracy**: 94%  
- **Precision (Fraud Class)**: 75%  
- **Recall (Fraud Class)**: 72%  
- **F1-Score (Fraud Class)**: 73%

> 💡 These results highlight strong fraud detection capabilities, with balanced performance across classes — even for imbalanced datasets.

---

## 📊 Visual Insights

<p align="center">
  <img src="https://github.com/tinega04/telecom-fraud-detection/blob/main/notebooks/figures/confusion_matrix.png?raw=true" alt="Confusion Matrix" width="500">
  <br>
  <em>Confusion Matrix: Showing strong separation between fraud and non-fraud</em>
</p>

<p align="center">
  <img src="https://github.com/tinega04/telecom-fraud-detection/blob/main/notebooks/figures/feature_importance.png?raw=true" alt="Feature Importance" width="500">
  <br>
  <em>Feature Importance: Top drivers of fraud predictions</em>
</p>

---

## 📁 Dataset

- **Source**: Synthetic CDR dataset  
- **Attributes**: Day/Eve/Night mins & charges, Intl calls, VMail, Customer service interactions, etc.  
- **Target Variable**: `isFraud` (1 = Fraudulent behavior, 0 = Legit)

---

## 📌 How to Run

1. Clone the repo  
   `git clone https://github.com/tinega04/telecom-fraud-detection.git`

2. Create a virtual environment  
   `python -m venv venv && source venv/bin/activate`  
   *(On Windows: `venv\Scripts\activate`)*

3. Install dependencies  
   `pip install -r requirements.txt`

4. Launch notebook  
   `jupyter notebook notebooks/fraud_detection_cdr.ipynb`

---

## 🧠 What I Learned

- Real-world challenges of working with imbalanced datasets  
- Importance of feature selection and engineered signals  
- Model evaluation metrics beyond accuracy  
- How to structure a clean, reproducible ML project  

---

## 📣 Let’s Connect!

If you're hiring, collaborating, or just want to geek out about data —  
**[Let’s talk on LinkedIn](https://www.linkedin.com/in/stephen-tinega-580b09184/)**

---

## ⭐ Acknowledgements

Inspired by real-world telecom fraud detection challenges and academic projects in applied machine learning.

