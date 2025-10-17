# Language-Detection-Model

### 🎓 Mini Project – B.Tech Artificial Intelligence and Data Science  
**Rajalakshmi Institute of Technology, Chennai**  
**Developed by:** *Sarah S V*

---

## 📖 Overview

**Language Identification Using Logistic Regression** is a classic NLP mini-project for automatically detecting the language of text headlines using character-level features and machine learning.  
This solution employs scikit-learn’s `CountVectorizer`, `LabelEncoder`, and `LogisticRegression` to classify sentences into multiple languages based on labeled news headlines. The model is simple, fast, and suitable for real-time text language classification.

---

## 🎯 Objectives

- Classify short headlines or sentences into multiple languages with high accuracy.  
- Demonstrate practical use of scikit-learn’s feature extraction and classification pipeline.  
- Build an interactive command-line interface for live predictions.  
- Highlight preprocessing and model training steps for reproducibility.

---

## 🧩 Features

✅ Multi-language classification  
✅ Character-level n-gram feature extraction  
✅ Fast training and prediction  
✅ Command-line interactive predictor  
✅ Handles missing and noisy data with robust preprocessing  
✅ Clean, reproducible code

---

## 🧠 Dataset Details

| Spec            | Description                                |
|-----------------|--------------------------------------------|
| Dataset Name    | Language Identification V2 (Hugging Face/Parquet) |
| Format          | Parquet table with fields: "Headline", "Language" |
| Example Size    | ~ N headlines per language (customizable)  |
| Languages       | Multilingual (details from dataset)        |
| Split           | Single training file used                  |

---

## ⚙️ Technologies Used

| Category                | Tools & Libraries               |
|-------------------------|---------------------------------|
| Programming Language    | Python 3.7+                     |
| Machine Learning        | scikit-learn                    |
| Data Handling           | pandas                          |
| File Format             | Parquet, Hugging Face datasets  |
| Environment             | Google Colab / Jupyter Notebook |

---

## 🏗️ System Pipeline

1. **Data Loading:** Read Parquet data table, extract relevant columns.  
2. **Preprocessing:** Remove missing entries, encode language labels.  
3. **Feature Extraction:** Convert text headlines to character n-gram matrix (unigram, bigram, trigram).  
4. **Model Training:** Fit `LogisticRegression` on extracted feature matrix and label vector.  
5. **Prediction:** Provide a live interactive prompt for real-time language detection.

---

## 📊 Results

| Metric            | Description                      |
|-------------------|----------------------------------|
| Feature matrix    | (n_samples, max_features=5000)   |
| Supported langs   | List from label encoder          |
| Training time     | Fast (few seconds for <100K rows)|
| Prediction speed  | Instant, real-time               |

---

## 🚀 Future Enhancements

- Add token-level or word-level features  
- Support more languages or dialects  
- Compare with deep learning models (LSTM, transformers)  
- Deploy as a web or API service  
- Visualizations for model interpretability  

---

## 🤝 Contribution

Contributions are welcome!  
1. Fork the repository  
2. Create a feature branch:  
  ```bash
  git checkout -b feature-name
  ```
3. Commit your changes:
  ```
  git commit -m "Add new feature"
  ```

4. Push the branch:
  ```
  git push origin feature-name
  ```
5. Submit a Pull Request

## 👩‍💻 Author

**Sarah S V**  
B.Tech – Artificial Intelligence and Data Science  
Rajalakshmi Institute of Technology, Chennai  
📧 [sarahsv.codes@gmail.com]

---

## 📚 References

- Hugging Face Language Identification Datasets  
- scikit-learn Documentation  
- Python pandas Documentation  

---

## 💬 Closing Note

This project demonstrates a fast and accessible solution for automatic text language detection using classic machine learning.  
**Fun, fast, practical language AI! 🚀**
