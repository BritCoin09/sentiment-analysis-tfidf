📘 Sentiment Analysis with TF‑IDF & Logistic Regression

This project builds a sentiment analysis model that classifies IMDB movie reviews as positive (1) or negative (0) using TF‑IDF features and Logistic Regression.
It was completed as part of an optional NLP task focusing on classical machine learning techniques for text classification.

🔍 Project Overview
The goal of this project is to:

- Convert lemmatized movie reviews into TF‑IDF vectors

- Train a Logistic Regression classifier

- **Achieve at least 0.82 accuracy**

- Generate predictions for a separate test dataset

- Save the predictions in the required format (pos column)

**The final model achieved a training accuracy of 0.9443**, significantly exceeding the requirement.

🧠 Methods Used

- TF‑IDF Vectorization

- Logistic Regression

- Text preprocessing (lemmatized text provided)

- Model evaluation using accuracy score

📂 Repository Contents

sentiment_analysis_tfidf.ipynb — Full Colab notebook with code, explanations, and results

imdb_reviews_small_lemm_test_with_preds.tsv — Test dataset with predicted sentiment labels

🚀 How to Run This Project

- Open the notebook in Google Colab or Jupyter

- Upload the training and test .tsv files

- Run all cells to reproduce the model and predictions

The final .tsv file will be generated automatically

📈 Model Performance

- **Training Accuracy: 0.9443**

- **Exceeds the required threshold of 0.82**

- **Demonstrates strong performance for a classical ML approach**

📝 Conclusion

This project shows how effective TF‑IDF and Logistic Regression can be for sentiment analysis tasks, even without deep learning.
The workflow is simple, fast, and produces high‑quality results suitable for real‑world text classification.
