# Cybersecurity_Threat_Detection-DDoS_Detection

->Built an intelligent Denial-of-Service (DoS) attack detection and classification system as part of a broader cybersecurity initiative. This project leveraged data science techniques to identify malicious patterns in network traffic, aiming to enhance web security through early detection of DoS threats.
->Utilized the Intrusion detection evaluation dataset (CIC-IDS2017), (https://www.unb.ca/cic/datasets/ids-2017.html), which contains labeled network traffic data representing both normal and attack behaviors.
->Performed data preprocessing, feature selection, and exploratory data analysis using Pandas, NumPy, Matplotlib, and Seaborn.
->Implemented and compared three classification models: Random Forest, Logistic Regression, and a Neural Network.
->Evaluated model performance using metrics such as accuracy, precision, recall, F1-score, and confusion matrix.
->Conducted comparative analysis to determine the most effective algorithm for detecting and classifying DoS attacks.
->Tools & Libraries: Python, Scikit-learn,Pandas, NumPy, Matplotlib, Seaborn.

Table of content
1- Importing libraries
2- Data Pre-processing
3- Data Exploring
4- Data Splitting
   A.Split the data
5- Model training
   A.Random Forest
   B.Logistic regression
   C.Neural Network
6- Model Evaluation
   A.Accuracy
   B.F1 Score
   C.Recall
   D.Precision
   E.Confusion Matrix
7- Model Comparison

RESULTS:

Random Forest Metrices:-
Accuracy: 0.9995
F1 Score: 0.9995
Precision: 1.0000
Recall: 0.9990

Random Forest Confusion Matrix
![Screenshot 2025-04-15 214301](https://github.com/user-attachments/assets/22bb4294-fe71-4f7a-98ad-2f573c09dfa2)


Logistic Regression Metrices:-
Accuracy: 0.9440
F1 Score: 0.9492
Precision: 0.9087
Recall: 0.9936

Logistic Regression Confusion Matrix
![Screenshot 2025-04-15 214327](https://github.com/user-attachments/assets/28022efe-063b-475d-be76-98c67bfb5461)


Neural Network Metrices:-
Accuracy: 0.9754
F1 Score: 0.9771
Precision: 0.9597
Recall: 0.9952

Neural Network Confusion Matrix 
![Screenshot 2025-04-15 214347](https://github.com/user-attachments/assets/b0f0cf1d-749f-4caf-9245-b8d40c0c3591)  

=>>Model Comparison
-----------------------
Reciever Operating Characteristic(ROC) Curve for all models:
![Screenshot 2025-04-15 214412](https://github.com/user-attachments/assets/4593c5ea-4f1f-4f90-9774-7745586504fa)

Research paper link:
https://drive.google.com/file/d/1n960CRyZOSJfCSDMNWiNiG4eghnFTFkq/view?usp=drive_link



