# CyberSecurity-Research-UROP-Project


Cyber Attack Detection Using Machine Learning
This project focuses on developing an effective system for detecting cyber attacks on network traffic using machine learning algorithms. The goal is to identify malicious activities such as intrusions, denial-of-service (DoS) attacks, and other threats by analyzing patterns in network data.

What was done
Implemented multiple machine learning algorithms including Random Forest, Support Vector Machine (SVM), K-Nearest Neighbors (KNN), Naive Bayes, and Decision Trees.

Used the well-known KDD Cup 1999 dataset, a benchmark dataset for network intrusion detection, consisting of both normal and attack network connection records.

Carried out comprehensive data preprocessing including cleaning, normalization, and feature selection to optimize model performance.

Trained, validated, and tested models on labeled datasets to evaluate accuracy, precision, recall, and F1-score as performance metrics.

Developed scripts using Python and popular ML libraries (e.g., scikit-learn) to automate the training and evaluation pipelines.

Compared the effectiveness of different algorithms in detecting various types of cyber attacks.

How it was done
The dataset was first loaded and cleaned to handle missing or inconsistent values.

Features relevant to attack detection were carefully selected based on domain knowledge and statistical analysis.

Models were trained using supervised learning approaches; hyperparameter tuning was performed using grid search and cross-validation to improve generalization.

A modular and reusable code structure was followed to allow scalability and ease of further improvements.

A detailed report was compiled summarizing methodology, results, and recommendations based on the findings.

Challenges faced
Handling imbalanced data: The dataset includes disproportionate numbers of normal and attack samples, which required techniques such as oversampling and undersampling to avoid model bias.

Feature selection complexity: Identifying which network attributes strongly correlate with attack types was challenging due to high dimensionality and multicollinearity.


Model generalization: Ensuring models did not overfit the training data and performed well on unseen data demanded rigorous validation and tuning.

Computational resource limitations: Some algorithms required significant computation time and memory, which constrained experimentation on limited hardware.

Interpretability: Explaining the decision-making process of complex models like Random Forests in cybersecurity context was difficult but crucial for practical deployment.


Note
All the results, performance metrics, datasets, and detailed simulations have been documented comprehensively in .docx format and are included in the project repository for reference.


