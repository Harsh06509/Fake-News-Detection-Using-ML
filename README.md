📰 Fake News Detection using Machine Learning

A complete end-to-end Machine Learning pipeline to classify news articles as Real or Fake using NLP techniques and models like Logistic Regression and SVM.

📌 Project Overview

This project builds a Fake News Classification System using:

NLP preprocessing

TF-IDF vectorization

ML models (LR, SVM, XGBoost)

Evaluation metrics

Visualizations

📊 Dataset

Use any Fake News dataset such as:

Kaggle Fake News Dataset
Dataset must contain:

text → news content

label → real/fake

Dataset is not included in this repo due to file size.

🧹 Preprocessing

Lowercasing

Punctuation removal

Stopword removal

Tokenization

Word count, char count

🧠 Feature Engineering

TF-IDF Vectorization

TfidfVectorizer(max_features=5000, stop_words='english')

🤖 Models Trained

Logistic Regression

Support Vector Machine

XGBoost (optional)

📈 Evaluation Metrics

Accuracy

Precision

Recall

F1 Score

Confusion matrix

🚀 How to Run
git clone https://github.com/yourusername/Fake-News-Detection-Using-ML.git
cd Fake-News-Detection-Using-ML
pip install -r requirements.txt


Run the notebook:

fake_news_detection_pipeline_1.ipynb

🔮 Future Improvements

Use BERT/LSTM

Deploy using Streamlit

Hyperparameter tuning

🙌 Author

Harsh Pratap Singh
Final-year CS Student | ML Enthusiast
