# Credit-card-fraud-detection
Problem Statement: Given a set of real bank transactions made by users, the goal is to identify fraudulent transactions which have not been made by the users.

The primary objective of this project is to identify fraudulent transactions that were not initiated by users. The dataset encompasses transactions spanning two days, comprising 57,116 instances and featuring 30 distinct attributes. Within this dataset, 142 instances are labeled as frauds, indicating a highly unbalanced distribution as shown in Figure \ref{fig1}. The nature of the problem is a two-class classification, with the target variable taking on values of 1 for fraud transactions and 0 for non-fraudulent transactions.

To tackle this classification challenge, various classifiers have been trained and assessed using metrics such as the confusion matrix, precision, recall, and F-score. Given the specific focus on minimizing instances where fraudulent transactions go undetected, recall emerges as a particularly crucial metric for the evaluation process. The emphasis lies in reducing the chances of overlooking or missing transactions classified as fraudulent.
