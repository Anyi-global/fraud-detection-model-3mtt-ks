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

![3mtt ks - explore dataset head](https://github.com/user-attachments/assets/700cf9b2-90fa-4e4e-a9ee-34bd3ee8d4c7)
![3mtt ks - evaluating dataset](https://github.com/user-attachments/assets/94ac0a25-f979-470f-ab03-15c4932e29ea)
![3mtt ks - data preprocessing](https://github.com/user-attachments/assets/161f7555-b12e-4681-b3b2-84466e178ea2)
![3mtt ks - confusion matrix plot](https://github.com/user-attachments/assets/1d119ef7-d694-42a5-ad8d-5aa1172ac60c)
![3mtt ks - conclusion](https://github.com/user-attachments/assets/603fed8f-6fb8-4438-9fc7-2f620723db98)
![3mtt ks - split dataset and Build model](https://github.com/user-attachments/assets/48e473d8-4790-4792-b0c7-5424e1f2ee8f)
![3mtt ks - plotting the ROC-AUC curve](https://github.com/user-attachments/assets/cac69f15-8735-4a55-9334-d87b797eb031)
![3mtt ks - Load dataset](https://github.com/user-attachments/assets/00e3430a-351f-489a-94aa-cbbf8309506b)
![3mtt ks - intro](https://github.com/user-attachments/assets/f64f808c-6172-4581-89bc-b7b1738bf532)
![3mtt ks - Explore the class balance](https://github.com/user-attachments/assets/78b951fe-61ef-41b1-9bbe-f42afacf09a1)
