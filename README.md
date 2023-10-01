# Semantic-and-Sentiment-Analysis


This repository contains a Semantic and Sentiment analysis model developed using the Random Forest Classifier from Scikit-Learn. The dataset ("https://osf.io/zwhm8/") consists of various sentences/phrases labeled as 'negative', 'neutral', or 'positive'. The aim is to predict the sentiment of a given sentence/phrase.

Overview:
The data was split into training, validation, and test sets.
Text data was vectorized using the TF-IDF (Term Frequency-Inverse Document Frequency) method.

Modeling:

A Random Forest Classifier was trained on the dataset.
Hyperparameter tuning was performed using GridSearchCV to identify the best parameters for the classifier.

Evaluation:
Performance metrics such as accuracy, precision, recall, and F1-score were calculated before and after hyperparameter tuning.

Interpretation:
Before hyperparameter tuning, the model was proficient at identifying the 'negative' samples but struggled with the 'neutral' and 'positive' classes. After hyperparameter tuning, the precision for the 'neutral' class improved, but its recall dropped significantly. The model's overall performance did not see significant improvement after tuning.
