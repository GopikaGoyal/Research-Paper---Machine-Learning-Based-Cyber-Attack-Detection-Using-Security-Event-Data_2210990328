Machine Learning-Based Cyber Attack Detection Using Security Event Data - 2210990328


 Overview
This project presents a data-driven approach for detecting and classifying cyber attacks using Machine Learning techniques. The system analyzes structured cybersecurity event data to identify different types of attacks and evaluate model performance using standard metrics.


 Objectives
Analyze and preprocess cybersecurity event data
Apply Machine Learning algorithms for attack classification
Evaluate model performance using accuracy, precision, recall, and F1-score
Visualize data distribution and model results


 Technologies Used
Python
Pandas, NumPy
Scikit-learn
Matplotlib, Seaborn
Jupyter Notebook


 Dataset
The dataset used in this project contains cybersecurity event records, including features such as:

Attack Type
Attack Severity
Data Exfiltrated
Threat Intelligence
Response Action

 The dataset can be accessed at https://www.kaggle.com/datasets/hassaneskikri/ai-enhanced-cybersecurity-events-dataset/data


 Methodology
The system follows a structured workflow:

Data Collection
Data Preprocessing
Feature Selection
Data Encoding
Train-Test Split
Model Training (Logistic Regression, Random Forest)
Model Evaluation
Visualization


 Models Used
Logistic Regression
Random Forest Classifier


 Results
Logistic Regression Accuracy: ~19%
Random Forest Accuracy: ~20%

The results indicate that both models perform similarly, with Random Forest showing slightly better performance. However, low accuracy highlights limitations in dataset feature quality.


 Visualizations
The project includes:

Attack Type Distribution
Attack Severity Distribution
Correlation Heatmap
Model Accuracy Comparison
Confusion Matrix
Feature Importance Graph


 Key Observations
Weak feature correlations limit model performance
Balanced dataset increases classification complexity
No single feature strongly influences prediction
Model performance depends heavily on feature quality


 Future Improvements
Apply advanced models (SVM, XGBoost, Deep Learning)
Improve feature engineering
Use richer and more complex datasets
Implement real-time attack detection


 How to Run
Clone the repository
Install required libraries:
pip install pandas numpy scikit-learn matplotlib seaborn
Open the Jupyter Notebook
Run all cells
