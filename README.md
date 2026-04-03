# Mental Health Emotion Classification using RoBERTa 🚀

## 👨‍💻 Author
**Samyak Rawat**

---

## 🌟 Project Overview

This project focuses on building an end-to-end NLP system to classify mental health-related text into **7 emotional categories** — `Anxiety`, `Bipolar`, `Depression`, `Normal`, `Personality Disorder`, `Stress`, and `Suicidal`.

The system leverages both traditional machine learning techniques and transformer-based deep learning models (RoBERTa) to enable early detection of mental health signals from textual data.

---

## 🧠 Key Highlights

- Fine-tuned **RoBERTa-base (125M parameters)** for multi-class classification  
- Processed and trained on **50,000+ labeled samples**  
- Built complete **data preprocessing pipeline** (cleaning, lemmatization, tokenization)  
- Achieved strong performance with optimized class balancing  
- Compared traditional ML vs transformer-based models  

---

## 🔍 Dataset

- Source: Kaggle (Mental Health Sentiment Dataset)  
- Size: 50,000+ samples  
- Classes: Anxiety, Bipolar, Depression, Normal, Personality Disorder, Stress, Suicidal  

---

## ⚙️ Methodology

### Data Preprocessing
- Text cleaning (URLs, mentions, punctuation removal)  
- Stopword removal and lemmatization  
- Tokenization using HuggingFace tokenizer  

### Models Used

#### 1. Logistic Regression (Baseline)
- TF-IDF vectorization  
- Hyperparameter tuning using GridSearchCV  

#### 2. RoBERTa (Deep Learning)
- Fine-tuned `roberta-base`  
- Optimizer: AdamW  
- Loss: CrossEntropy with class weights  
- Scheduler: Linear warmup  
- Training with validation monitoring  

---

## 📊 Results

| Model                | Accuracy |
|---------------------|----------|
| Logistic Regression | ~70%     |
| RoBERTa             | ~72.25%     |

---

## 🚀 How to Run

```bash
git clone https://github.com/SmykRwt/Mental-Health-Emotion-Classification-using-RoBERTa.git
cd Mental-Health-Emotion-Classification-using-RoBERTa
pip install -r requirements.txt
jupyter notebook
