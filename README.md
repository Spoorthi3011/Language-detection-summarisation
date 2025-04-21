# 🌐 Language Detection and Summarization for Multilingual Content

This project implements a dual-function NLP system that:  
1. Detects the language of any given input text.  
2. Summarizes multilingual content using advanced transformer-based models.

---

## 📌 Highlights

- 🧠 **Model Used:** Multinomial Naive Bayes (for language detection)  
- 🌍 **Supports 17 Languages**: English, Tamil, Hindi, Malayalam, Kannada, Spanish, French, German, Arabic, and more  
- 📝 **Summarization Techniques:** Transformer-based models (BERT, GPT-style)  
- 📊 **Accuracy Achieved:** > 95% on test data  
- 📎 Real-world Use Case: Social media, news, multilingual data analytics  

---

## 📂 Project Structure

| File | Description |
|------|-------------|
| `language_detection.py` | Python script implementing language detection using Naive Bayes |
| `summary.ipynb` | Jupyter Notebook with end-to-end code & analysis |
| `PPT.pptx` | Final presentation summarizing project flow, architecture, and results |

---

## 🧠 Datasets Used

- **Language Detection Dataset:** Texts labeled in 17 languages  
  Source: _Public Kaggle datasets / multilingual corpora_
- **Summarization Dataset:**  
  - `C4 (Colossal Clean Crawled Corpus)`  
  - `Open Parallel Corpus`

---

## 🧪 Models Compared

- Naive Bayes  
- K-Nearest Neighbors  
- Random Forest  

✅ **Best performing model:** Multinomial Naive Bayes  
✅ **Evaluation Metrics:** Accuracy, Confusion Matrix, F1-Score, Classification Report  

---

## 🧾 Results

- 📈 Accuracy: 95–97%  
- 🧩 Summarization performed well for English and Hindi  
- 📉 Low error rate in language detection across all classes  

---

## 🗺️ Flow Overview

1. **Preprocess Text:** Clean & normalize input text  
2. **Detect Language:** Use vectorized data + Naive Bayes  
3. **Summarize Content:** Use pretrained transformers  
4. **Visualize & Evaluate:** Confusion matrix + classification report  

---
