# 🛍️ Sentiment-Analysis

# 🚀 Project Overview

This project focuses on performing Sentiment Analysis on customer reviews from Flipkart using PySpark in a distributed computing environment. The dataset, “Flipkart Product reviews with sentiment Dataset.csv”, contains product review texts along with associated sentiment labels, enabling supervised machine learning for classification.

The main objective of this project was to analyze customer opinions, classify sentiments (Positive, Negative, Neutral), and extract meaningful insights from large-scale textual data using Spark’s distributed processing capabilities.

The entire workflow was implemented in a PySpark Notebook, making it scalable and suitable for big data text analytics.

# 📂 Dataset Description

The dataset includes customer review information such as:

Product-related details

Customer review text

Sentiment label (Positive / Negative / Neutral)

Additional metadata related to product ratings or review characteristics (if available)

This dataset represents real-world e-commerce customer feedback, making it ideal for Natural Language Processing (NLP) tasks.

# 🎯 Objectives

Perform large-scale text preprocessing using PySpark.

Clean and transform raw review text data.

Convert textual data into numerical features using NLP techniques.

Build a machine learning model to classify customer sentiments.

Evaluate the performance of the sentiment classification model.

Generate actionable insights from customer feedback.

# ⚙️ Technologies Used

PySpark

Apache Spark MLlib

Spark NLP functions

Python

PySpark Notebook (Databricks / Jupyter Spark environment)

# 🔄 Project Workflow
1️⃣ Data Loading

Imported the CSV dataset into PySpark DataFrame.

Inspected schema and validated data structure.

Checked for missing or null values.

2️⃣ Data Cleaning & Text Preprocessing

Removed null or empty reviews.

Converted text to lowercase.

Removed punctuation, special characters, and stopwords.

Tokenized review text using Spark NLP functions.

Applied techniques like:

Tokenizer

StopWordsRemover

TF-IDF / CountVectorizer

3️⃣ Feature Engineering

Transformed cleaned text into feature vectors.

Encoded sentiment labels into numeric format.

Prepared data for machine learning classification.

4️⃣ Model Building

Implemented classification algorithms such as:

Logistic Regression

Naïve Bayes

Decision Tree (if applied)

Trained the model using training dataset.

Generated predictions on test dataset.

5️⃣ Model Evaluation

Evaluated performance using:

Accuracy

Precision

Recall

F1-Score

Analyzed confusion matrix to assess classification performance.

# 📊 Key Insights

Majority of reviews reflected positive customer sentiment.

Negative reviews highlighted recurring product/service issues.

Neutral reviews often lacked descriptive language.

Text preprocessing significantly improved classification accuracy.

Distributed processing with PySpark enhanced performance for large text datasets.

# 🧠 Learning Outcomes

Hands-on experience with Big Data text analytics.

Practical understanding of NLP using Spark MLlib.

Implementation of end-to-end machine learning pipeline.

Improved skills in feature extraction and sentiment classification.

Exposure to scalable machine learning workflows.

# 📌 Conclusion

This project successfully demonstrates the implementation of Sentiment Analysis using PySpark on real-world e-commerce review data. By leveraging Spark’s distributed computing framework, the system efficiently processes large volumes of textual data and accurately classifies customer sentiment.

The project highlights practical skills in Natural Language Processing, Machine Learning, and Big Data Analytics, making it highly relevant for Data Science and Big Data Engineering roles.



