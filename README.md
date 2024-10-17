# Fake_news
Fake News Detection System-
This project focuses on building a system that detects fake news using machine learning and Natural Language Processing (NLP) techniques. The system helps identify misleading or false news articles by analyzing textual content.

Technology Used-
We applied the following methods for data preprocessing and model training:

-Text Preprocessing: A custom function was created to clean and prepare the text data. This involved:

-Converting text to lowercase.

-Removing URLs, punctuation, special characters, and numbers.

-Removing any unnecessary symbols or content in square brackets. This cleaning ensures that the text is in a consistent and analyzable form.

-TF-IDF Vectorization: After preprocessing the text, we used Term Frequency-Inverse Document Frequency (TF-IDF) to convert the cleaned text into numerical 
 representations. This technique captures the importance of words in each document relative to the overall dataset.


Model Training and Prediction
We trained multiple machine learning models on the processed data, including:

-Logistic Regression

-Decision Tree Classifier

-Gradient Boosting Classifier

-Random Forest Classifier


Each model was trained to classify news articles as either fake or real. The results were predicted using all models, allowing us to compare their performance and accuracy
