# 🐦 Twitter Sentiment Analysis using Machine Learning

This project focuses on analyzing sentiments expressed in tweets using a machine learning model. It classifies tweets into **Positive**, **Negative**, or **Neutral** categories based on the textual content.

## 📌 Project Features

- Preprocessing and cleaning of raw tweet text
- Vectorization using TF-IDF
- Training a sentiment classification model
- Saving and loading the trained model and vectorizer
- Predicting sentiment for new tweets
- Deployment-ready with a separate prediction notebook

---

## 🚀 Tech Stack

- **Python**
- **Scikit-learn**
- **Pandas / Numpy**
- **NLTK**
- **Pickle** for model serialization

---

## 📁 Project Structure

📦 Twitter_Sentiment_Analysis
                              ├── Twitter_Sentimental_Analysis_using_ML.ipynb # Model training and evaluation                                    
                              ├── model_to_predict_sentiment_of_tweet_.ipynb # Inference using saved model 
                              ├── trained_model.sav # Pickled ML model
                              ├── vectorizer.sav # Pickled TfidfVectorizer

                              
