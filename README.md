# Credit Card Fraud Detection
**Detecting credit card fraud using supervised machine learning algorithms**

This notebook tries out several classification techniques, including:
* KNN
* Decision Tree
* Random Forest
* XGBoost Classifier 

In order to classify a dataset of transactions as either fraudulent or real. The dataset used in training the model is a synthetic dataset that has generated a more balanced number of fraudulent and real transactions, as the original dataset only has 492 fraudulent transactions out of over 200k+ total transaction records. 

# Results 
The results of the classification found that for the synthetic dataset, the classification models worked well (in particular, XGBoost, which was taken to be the chosen model). However, when applied to the real dataset that only contains 492 fraudulent transactions, the classification model had poor accuracy overall due to a very high false positive rate. 
