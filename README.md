#  Fake News Detector

A Machine Learning project that detects Fake vs Real news using text classification.  
Trains multiple models (Logistic Regression, Random Forest, Naive Bayes) on a dataset of news articles and evaluates their performance.  
Includes model saving/loading so predictions can be made on new unseen news articles.

---

# Features

~ Load and label Fake/True news datasets  
~ Clean text (lowercase, remove punctuation, stopwords, URLs, numbers)  
~ Convert text into numbers using **TF-IDF (top 5000 words)**  
~ Train/test split for fair evaluation  
~ Models trained:
   - Logistic Regression  
   - Random Forest  
   - Multinomial Naive Bayes  
~ Evaluation:
   - Accuracy  
   - Precision, Recall, F1 (classification report)  
   - Confusion matrix  
~ Hyperparameter tuning for Random Forest with **GridSearchCV**  
~ Save & load trained models and vectorizer using **pickle**  
~ Predict on new text with `predict_news(text)` function  

---



