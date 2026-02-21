# Sentiment-Analysis

*Company Name :- CODTECH IT SOLUTIONS

*Name :- DOBARIYA HETVI RAMESHBHAI

*Intern ID :- CTIS4315

*Domain Name :- Data Analytics

*Duration :- 4 Weeks

*Mentor :- NEELA SANTHOSH

Description :-
               "This project focuses on performing Sentiment Analysis on a Flipkart Product Reviews dataset using Natural Language Processing (NLP) techniques and Machine Learning. Sentiment analysis is a text classification task that determines whether a given piece of text expresses a positive, negative, or neutral opinion. In this project, customer reviews from Flipkart were analyzed to identify the overall sentiment expressed in each review.The dataset consists of product-related information such as product name, price, rating, review text, summary, and a sentiment label (positive, negative, or neutral). For the purpose of this analysis, only the “Review” and “Sentiment” columns were selected. This ensures the model focuses purely on textual opinion data and its corresponding sentiment classification. After loading the dataset into a Jupyter Notebook, initial data exploration was performed to understand its structure, shape, and class distribution.A key observation from the dataset was that it is highly imbalanced, with the majority of reviews labeled as positive, followed by negative and a smaller portion of neutral reviews. A bar chart visualization was created to clearly show the sentiment distribution. This helped in understanding the data characteristics before model building.Data preprocessing is a crucial step in NLP tasks. The review text was cleaned by converting all characters to lowercase, removing special characters, numbers, and extra spaces. This standardization process helps reduce noise and improves model performance. After cleaning the text, feature extraction was performed using the TF-IDF (Term Frequency–Inverse Document Frequency) vectorization technique. TF-IDF converts textual data into numerical format by assigning weights to words based on their importance in the document and across the dataset. The maximum number of features was limited to 5000 to optimize computational efficiency.The dataset was then divided into training and testing sets using an 80:20 split ratio. Logistic Regression was selected as the classification algorithm due to its effectiveness and simplicity in text classification tasks. The model was trained on the TF-IDF transformed training data and later evaluated using the test dataset.Model evaluation was performed using accuracy score, classification report, and confusion matrix. The model achieved an accuracy of approximately 91%, indicating strong performance in predicting sentiments correctly. The confusion matrix provided further insights into how well the model classified each sentiment category. It was observed that the model performed exceptionally well for positive reviews, while performance for neutral reviews was comparatively lower due to class imbalance.The results demonstrate that Logistic Regression combined with TF-IDF is an effective baseline model for sentiment analysis tasks. The analysis also provides useful business insights, such as the dominance of positive customer feedback, which indicates overall customer satisfaction. However, future improvements can include handling class imbalance using techniques like SMOTE, experimenting with advanced models such as Random Forest or XGBoost, or implementing deep learning approaches like LSTM for better performance."




🔹 Technical documentation version for submission

Tell me what you need next 😊
