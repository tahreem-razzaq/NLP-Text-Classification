🧠 NLP Text Classification Project

This Natural Language Processing (NLP) project focuses on building and evaluating models for binary text classification using real-world user reviews. The workflow includes rigorous data preprocessing, tokenization, vectorization, model training, and performance visualization to determine the most effective approach for classifying textual data.


---

🔍 Project Overview

The goal of this project is to clean and transform raw textual data into a format suitable for machine learning algorithms, then apply and compare multiple classification models. Throughout the process, special care has been taken to handle common preprocessing challenges and ensure high-quality input to the models.


---

🛠 Features & Workflow

✅ Data Preprocessing

-A robust and multi-step text cleaning pipeline was applied:
-Removed HTML tags
-Removed punctuation and special symbols
-Spaced out words before punctuation removal to prevent word merging
-Expanded contractions (e.g., "can't" → "cannot")
-Identified misspelled or unrecognized words
-Converted text to lowercase
-Removed extra whitespaces

✂ Tokenization & Vectorization

-Performed tokenization using appropriate NLP tools.
-Transformed text using TF-IDF Vectorization to capture word importance across the dataset.

🤖 Model Building

Three machine learning models were built and trained:
-Logistic Regression
-Linear Support Vector Machine (SVM)
-Naive Bayes

Each model was trained on the vectorized data and evaluated based on key performance metrics.

📊 Model Evaluation & Visualization

-Accuracy, precision, recall, and F1 score were calculated for each model.
-Performance comparisons were visualized using bar charts and classification reports.
A- word cloud was generated to illustrate the most frequent words in the corpus.
