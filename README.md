# Credit-Card-Fraud-Detection
This repo is the work done on a Credit Card Fraud Dataset, where we tested various models and then used a voting classifier for the final prediction.
This is part of the project where the goal was to develop a working Transaction Fraud Detection Software.
In this part, the goal was to test and select various models which would be appropriate for the Dataset, and then predict correctly if real time transaction are fraud, suspicious or not fraud.
What we  did:
1. Did an exploratory analysis(only essential) on the dataset.
2. Then we saw that the dataset was imbalanced, and used SMOTE to balance the dataset
3. Then tested how various models performed on the new dataset.
4. Based on the best performance and considering which are the best for tabular data, three models were selected for a voting classifier
5. After 3 models were selected and a voting classifier was designed.
6. After that the threshold was adjusted for the best F1 score.
