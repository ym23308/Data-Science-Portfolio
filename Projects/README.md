# 📰 Fake News Detection using Machine Learning

**Objective:**  
Build a machine learning model to detect whether a news article is fake or real using text data.

**Dataset:**  
[Fake and Real News Dataset (Kaggle)](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset)

---

## 🧠 Project Overview
This project aims to identify fake news articles based on their textual content.  
By training a logistic regression model on labeled news data, the system learns to distinguish between fake and real news using natural language processing techniques.

---

## ⚙️ Steps Involved

1. **Data Loading** – Load the dataset and combine fake and real news into one DataFrame.  
2. **Text Preprocessing** – Clean text by removing punctuation, stopwords, and converting to lowercase.  
3. **Vectorization** – Convert text into numerical features using TF-IDF Vectorizer.  
4. **Model Training** – Train a Logistic Regression model on the processed data.  
5. **Model Evaluation** – Measure accuracy, F1 score, and visualize results with a confusion matrix.

---

## 📈 Results

- **Accuracy:** ~99%  
- **F1 Score:** ~0.98  
- The confusion matrix shows that the model correctly classified most news articles:
  - 4,580 fake articles were correctly identified as fake.  
  - 4,264 real articles were correctly identified as real.  
  - Only 82 fake and 54 real articles were misclassified.  

✅ **Conclusion:**  
The model demonstrates high reliability in detecting fake news and can be applied as a baseline system for content verification.

---

## 🧰 Skills Used
- Python (Pandas, Scikit-learn, Matplotlib)
- Natural Language Processing (NLP)
- Logistic Regression
- Text Preprocessing (Stopword Removal, TF-IDF)
- Data Visualization

---

## 🔗 Notebook Link
[View on Google Colab]((https://colab.research.google.com/drive/16J9iwYoYfMLSSVvi-KwrlaJAwVuDsf4t?usp=sharing))
