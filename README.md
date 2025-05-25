# fraud-detection-model-3mtt-ks
### 1. Problem Definition
Fraud detection involves identifying transactions that are potentially fraudulent, which is crucial in industries like banking and e-commerce. We'll build a binary classification model that predicts whether a transaction is fraudulent (1) or not (0). 

**LINK TO THE 3 MINUTES VIDEO EXPLAINING THE PROJECT**: https://vimeo.com/1087454252?share=copy#t=0

### 2. Dataset & Source
We'll use the popular "Credit Card Fraud Detection" dataset from Kaggle. It contains:

- 284,807 transactions
- 492 frauds (only ~0.17% --> high class imbalance) <br>

Features are anonymized using PCA (V1, V2, ..., V28), plus Time, Amount, and Class.

### 3. Tools and Libraries
For training of this model, we'll use:

- Python
- Pandas for data handling
- Scikit-learn for modeling
- Matplotlib/Seaborn for visualization
- RandomForest for predictive modeling

## Conclusion
As I wrap up this project, I just want to thank God for the opportunity to learn and apply machine learning to a real-world problem: fraud detection.

In this project, I built a predictive model using a Random Forest Classifier to identify fraudulent transactions in a dataset. The process involved several key steps:

- Cleaning and preparing the data.

- Standardizing features like transaction amount to improve model accuracy.

- Training and evaluating the model using precision, recall, F1-score, and ROC-AUC.

- Visualizing results with confusion matrix and ROC curve to show how well the model performs.

The results showed that the model was able to accurately identify frauds, even in an imbalanced dataset where fraudulent cases are very rare. By using Z-score standardization and stratified train-test splitting, I ensured that the model learned fairly and effectively.

This project has helped me understand not just the technical side of AI, but also its potential to solve real-life problems that affect people and businesses every day.

# THANK YOU!!!
