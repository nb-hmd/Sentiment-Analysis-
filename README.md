# Sentiment Analysis API with TF-IDF and Logistic Regression

## 📌 Project Overview
A lightweight sentiment analysis system that classifies text as positive/negative using:

- TF-IDF for text vectorization
  
- Logistic Regression for classification
  
- Flask for API deployment

## 🛠️ Technical Stack
- Python 3.9+
  
- Scikit-learn (TF-IDF + Logistic Regression)
  
- Flask (API framework)
  
- Pandas (data processing)

## 📂 Project Structure
sentiment_analysis/
├── 1_data_preprocessing.py    # Cleans raw Twitter data

├── 2_tfidf_training.py       # Trains classification model

├── app.py                    # Flask API server

├── models/                   # Saved models

│   ├── tfidf_vectorizer.pkl  # TF-IDF vectorizer

│   └── logistic_model.pkl    # Trained classifier

├── data/
│   ├── twitter_data.csv      # Raw input data

│   └── cleaned_twitter_data.csv # Processed data

└── requirements.txt          # Dependencies

## 🚀 Installation
1. Clone repository:
   ```bash
   git clone [your-repo-url]
   cd sentiment_analysis

📊 Performance
Training time: ~30 seconds (CPU)

Accuracy: ~80% on test set

Prediction speed: <10ms per request


✉️ Contact
For questions or support:

Email: xyzz05@outlook.com

GitHub: nb-hmd
