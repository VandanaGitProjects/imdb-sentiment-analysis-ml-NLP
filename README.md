# IMDb Movie Review Sentiment Analysis (Machine Learning Project)

## 📌 Overview
This project builds a machine learning system to classify IMDb movie reviews as **Positive** or **Negative**. The goal is to demonstrate text preprocessing, feature engineering, and classification model development for sentiment analysis.

## 🎯 Problem Statement
Movie reviews contain valuable insights into audience perception. Manually analyzing thousands of reviews is inefficient. This project develops ML models to automatically classify reviews, helping businesses and platforms understand sentiment trends.

## ⚙️ Project Workflow
1. **Data Exploration & Cleaning**
   - Removed duplicates, HTML tags, punctuation, digits, and extra spaces.
   - Converted text to lowercase and removed stopwords.
2. **Text Preprocessing**
   - Tokenization, Lemmatization, and Stemming.
   - Word count, character count, and average word length features.
3. **Feature Engineering**
   - TF‑IDF Vectorization (max_features=5000).
   - Bag of Words representation.
4. **Model Development**
   - Logistic Regression  
   - Naive Bayes (MultinomialNB)  
   - Support Vector Machine (LinearSVC)  
   - Random Forest Classifier
5. **Model Evaluation**
   - Metrics: Accuracy, Precision, Recall, F1 Score, ROC‑AUC.
   - Confusion Matrix visualization.
   - WordClouds for positive and negative reviews.

## 🛠️ Tech Stack
- **Languages & Libraries:** Python, Pandas, NumPy, Scikit‑Learn, NLTK, Matplotlib, Seaborn, WordCloud
- **Tools:** Jupyter Notebook / Google Colab

## 📊 Results
- **Logistic Regression:** Accuracy ≈ 87%, ROC‑AUC ≈ 0.875 (best balanced performance)  
- **Linear SVC:** Accuracy ≈ 86%, ROC‑AUC ≈ 0.859  
- **Naive Bayes:** Accuracy ≈ 85% (fast baseline model)  
- **Random Forest:** Accuracy ≈ 84% (less effective for text data)  

## 📂 Dataset Link : [Google Drive](https://docs.google.com/spreadsheets/d/1KbfDuAybIZ-t8jxckdN6Z4KR2p-hd27E/edit?usp=drive_link&ouid=105917977639559840330&rtpof=true&sd=true)
