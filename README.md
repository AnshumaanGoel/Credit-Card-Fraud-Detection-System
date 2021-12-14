Presently, the accuracy of fraud detection is poor with high number of false positive errors(correct transaction classified as fraud) or classification errors. Azure Machine Learning can be used to enhance accuracy of fraud detection. 
To solve this problem, we use Supervised learning algorithms to train the classifier for detecting anomalous credit card transaction. Once trained, we use test dataset to compare the new accuracy of fraud detection with old accuracy. The new accuracy would be higher than the old accuracy that would prove an enhanced fraud detection system.
Azure AI, ML, Data Analytics functionality and Python programming language would be employed to achieve the desired results. 

# Credit-Card-Fraud-Detection-System

In this kernel, we are going to predict whether a credit card transaction is fraud or not using Machine Learning.
The dataset contains transactions made by credit cards in September 2013 by european cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.
Due to confidentiality issues, the input variables are transformed into numerical using PCA transformations.

#Findings

We use Supervised Learning(Logistic Regression) to show an improvement in Accuracy Score by 0.1% in detecting credit card frauds.
We also use Azure Auto ML to apply various regression models and best fitting model was adopted that gave a reasonable accuracy of above 80%.

#Future Scope & Relevance in real world

Other supervised algorithms, unsupervised algorithms, Azure Cognitive Services(Anomaly detector etc) can be used to compare accuracy scores for each of them. Hence, we can find the best performing algorithm having highest accuracy in detecting credit card frauds. Such an algorithm can then be used by the banking industry in real world scenario. 
