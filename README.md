# Quora Question Pairs
Kaggle competition to identify duplicate questions: https://www.kaggle.com/c/quora-question-pairs

## Process
### #1 Cosine Similarity with TF-IDF with the default tokenizer
### #2 Cosine Similarity with TF-IDF with a custome tokenizer
Each question is tokenized into sentences. Each sentence is tokenized into words. Each word is lemmatized.
### #3 Add some features and use the default settings of:
1. scikit-learn's Decision Tree Classifier
2. scikit-learn's AdaBoost Classifier
3. scikit-learn's Logistic Regression
4. dmlc's XGBoost

