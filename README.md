# Machine-Learning

Text Mining

# Lie Detection using Sentiment Analysis

Scenario: 

 Machine learning algorithms can figure out whether a person is lying or not.
 To test this claim, we have collected a collection of customer reviews, some are true some are fake, and you are going to test
 how well you can use the algorithms we’ve covered for fake review detection.
 
Note:
The data set also has sentiment label for each review and you should try to predict that as well.

Algorithms used:
# Naïve Bayes and SVM

1.	Different preprocessing methods – e.g., with or without stop-words, lemmatization, reducing the specific tokens you’ve used to maximize information gain.
2.	With either category (lie / sentiment) does it help to include the other category as a feature?  For the lie feature
3.	Use a topic model & sentiment analysis module to generate additional features and use these in combination with / instead of raw tokens.

Try to get the best results you can.

1. General Strategy
2. Parameter settings
3. F1 score for Sentiment & Lie
4. Precision and Recall

Parameter tuning approach for every attempted strategy is used. Reported how much of a difference did parameter tuning make?

# Additional Tasks that can be performed
For each task and feature set (sentiment classification / lie detection), use the Rank module (Gini and Information Gain Ratio) to rank the features
and list top 10 features from each method. Based on these top features, can you understand what patterns the classifiers have learned from the data? 

Compare performance difference in sentiment classification and lie detection, and tell us which task is harder, and try to explain why.
