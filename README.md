🚨 Note: The complete source code for this project is accessible via the README. The development was carried out on Google Colab, as the XGBoost classifier is not directly compatible with local execution environments.

🌐 Project Overview
In today's digitally connected era, cybersecurity threats are a growing concern for both individuals and organizations. A key defense strategy involves promptly identifying and addressing unauthorized intrusions. Network Intrusion Detection Systems (NIDS) are essential tools that monitor network traffic, detect anomalies, and alert security teams about potential breaches.

This project aims to develop a NIDS using the NSL-KDD dataset, a standard benchmark in intrusion detection research. The dataset includes extensive network activity data—covering both benign and malicious behavior—with roughly 150,000 instances and 23 distinct attack labels. This makes it a realistic and challenging dataset for intrusion detection model training and evaluation.

🛠️ Data Preprocessing
Applied label encoding and one-hot encoding for handling categorical variables

Used Recursive Feature Elimination (RFE) with a Random Forest classifier for feature selection

🤖 Machine Learning Models Used
Random Forest

K-Nearest Neighbors (KNN)

Support Vector Machine (SVM)

Principal Component Analysis (PCA)

Ensemble Voting Classifier

Gaussian Naive Bayes

XGBoost

📝 Implementation Details
All models were implemented using Python and libraries such as scikit-learn, XGBoost, and Matplotlib. Due to the limitations of local environments with XGBoost, the project was developed in a Google Colab notebook.

📄 Project Documentation
The documentation includes detailed explanations of the methods, analysis, and results obtained during the creation of the NIDS. It also provides insights into how machine learning techniques can be applied to cybersecurity challenges.
[Click here to view the documentation]

💻 Source Code
Access the full code in the following Google Colab notebook: [Link to Source Code]

📬 Contact
For feedback or queries, feel free to reach out to Koushik S.

🤝 Contributions Welcome!
You can contribute by:

Enhancing model performance

Improving data preprocessing techniques

Optimizing feature selection

Suggesting ideas or improvements
