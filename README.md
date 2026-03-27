# comment-category-prediction

Description
In this competition, you'll analyze a dataset containing information about short textual entries submitted to an online discussion system. The dataset includes the content of each entry, engagement signals from other users, and outputs from automated analysis components.

Your goal is to use this information to predict how each entry was ultimately categorized by the system.

Workflow
Data Preprocessing
Text cleaning (stopwords, punctuation removal)
Tokenization / Vectorization (TF-IDF / Embeddings)
Handling missing values

Feature Engineering
Combine text + engagement features
Normalize numerical features

Model Training
Tried multiple models:
Logistic Regression
Naive Bayes
LightGBM / XGBoost
Random Forest
MLP

Evaluation
Accuracy
Precision, Recall, F1-score
Confusion Matrix
