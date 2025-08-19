# Ml-project2
📰 Fake News Detection (Machine Learning Project)

A machine learning project that classifies news articles as Real or Fake using TF-IDF Vectorization and Logistic Regression.

🚀 Features

Preprocesses text data with TF-IDF

Classifies news as REAL or FAKE

Achieves 90–95% accuracy on the Fake and Real News Dataset

📂 Project Structure
fake-news-detection/
│── data/
│   └── Fake.csv             # Fake news dataset
│   └── True.csv             # Real news dataset
│
│── src/
│   └── fake_news_classifier.py   # Main Python code
│
│── README.md                # Documentation
│── requirements.txt         # Dependencies

⚙️ Installation
# Clone the repository
git clone https://github.com/<your-username>/fake-news-detection.git
cd fake-news-detection

# Install dependencies
pip install -r requirements.txt

▶️ Usage
cd src
python fake_news_classifier.py

📊 Example Output
✅ Accuracy: 0.93

              precision    recall  f1-score   support
           0       0.94      0.93      0.93      2142
           1       0.92      0.93      0.93      2113

📜 Tech Stack

Python

Pandas

Scikit-learn

NumPy

🏆 Future Improvements

Use deep learning models (LSTM, BERT) for higher accuracy

Improve dataset cleaning (handling stopwords, punctuation, etc.)

Try other ML models (SVM, Random Forest, XGBoost)
