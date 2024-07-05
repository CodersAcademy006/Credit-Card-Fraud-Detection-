Credit card fraud detection
Using Logstic RegressionClassification for Credit Card Fraud Detection

Steps and some points to note
Feature Engineering
Solution to sample imbalance problem ( two methods: downsampling and oversampling )
Downsampling strategy
Cross-validation (make full use of data to make the model more convincing)
Model evaluation method (classification accuracy, precision, recall, F1 value)
Regularization penalty (prevent model overfitting, introduce L2 regularization )
The impact of logistic regression threshold on the results (visualized by confusion matrix and recall)
Oversampling strategy ( SMOTE algorithm )
How does it work?
The credit card dataset is "creditcard.csv", the address is: https://myblogs-photos-1256941622.cos.ap-chengdu.myqcloud.com/%E4%BF%A1%E7%94%A8%E5%8D%A1%E6%AC%BA%E8%AF%88%E6%A3%80%E6%B5%8B/creditcard.csv (can be downloaded as needed)
 python Creditcard_fraud_detection.pyJust run the file in the same storage directory as the dataset
Configuration Environment
Python 3.6.5
numpy 1.15.4
pandas 0.23.4
matplotlib 3.0.2
scikit-learn 0.20.0
imbalanced-learn 0.4.3
