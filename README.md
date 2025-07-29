This project predicts the genre of a movie based on its plot summary using Natural Language Processing (NLP) and Machine Learning.

📂 Dataset

Source: Kaggle - Genre Classification Dataset IMDb

Columns:

Title: Movie name

Overview: Plot summary

Genre: Target label

🛠️ Technologies Used

Python

pandas, numpy

scikit-learn

nltk

TF-IDF Vectorizer

Logistic Regression, Naive Bayes, SVM

🧹 Preprocessing Steps

Text lowercasing

Stopword removal

Punctuation removal

TF-IDF vectorization

Label encoding of genres

🤖 Model Training

Train-Test Split: 80-20

Models Tried:

Logistic Regression ✅ Best

Naive Bayes

Support Vector Machine

Evaluation Metrics:

Accuracy

Precision, Recall

Confusion Matrix

📊 Results

Best Model: Logistic Regression

Accuracy: ~83%

Observations:

Strong performance for common genres like Drama, Comedy

🚀 Future Enhancements

Multi-label classification

Deep learning models (LSTM, BERT)

Web deployment using Streamlit or Flask
