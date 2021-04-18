# Sentiment_analysis_of_product_reviews
Sentiment Analysis of Amazon product reviews using Decision Tree and Logistic Regression Algorithms

Data Set :
https://www.kaggle.com/datafiniti/consumer-reviews-of-amazon-products/

• The 2 classifiers used :- Logistic Regression, Decision Tree
• Stop word Removal → lemmatization → Vectorization → Model Training → Hyper Parameter Tuning → Evaluation Metrics
• Hyper_parameter_tuning :- Using Random Search we did hyperparameter tuning for both decision Trees and logistic Regression.

# F1 SCORES FOR ALL CLASSIFIERS:
Decision Tree with bag of words        0.981902871105681
Decision Tree with tfidf               0.9823194714934891
Logistic Regression with bag of words  0.9780486863932718
Logistic Regression with tfidf         0.9761730063718863

# ROC AUC SCORES FOR ALL CLASSIFIERS:
Decision Tree with bag of words        0.7722832722832724
Decision Tree with tfidf               0.645107503778098
Logistic Regression with bag of words  0.8777568700084069
Logistic Regression with tfidf         0.8629180615604796

# Conclusion :
Used Logistic Regression and Decision Tree classifiers to evaluate the result, able to find the top 10
words for classification and Logistic Regression with tfidf features. 
# Logistic Regression performed better compared to Decision Trees
