# Credit-Card-Fraud-Detection-

Credit Card Fraud Detection with Machine Learning

This Python script leverages various libraries, including Pandas, NumPy, Matplotlib, Seaborn, and Plotly, to explore and analyze a credit card fraud dataset. Here's a breakdown of the script:

*  Importing Necessary Libraries: *
The script starts by importing essential libraries for data manipulation, visualization, and machine learning, including Pandas, NumPy, Matplotlib, Seaborn, and Plotly.

* Check for Missing Data: *
The code checks for missing data in the dataset using Pandas, displaying the total count and percentage of missing values for each column.

* Data Unbalance Visualization: *
Visualization using Plotly shows the distribution of classes in the dataset, highlighting the potential data unbalance between non-fraudulent (Class 0) and fraudulent (Class 1) transactions.

* Data Exploration: *
Time-related and transaction amount analyses are performed, providing insights into the temporal distribution of transactions and the amount distribution for both fraudulent and non-fraudulent transactions.

* Features Correlation and Visualization: *
The script calculates and visualizes the correlation matrix of features in the dataset. Scatter plots are used to illustrate the relationships between certain features and transaction amount, considering both fraud and non-fraud scenarios.

* Features Density Plot: *
Kernel Density Estimation (KDE) plots are generated for each feature, showcasing the distribution of legitimate (Class 0) and fraudulent (Class 1) transactions.

* Predictive Models: *
The script builds machine learning models, specifically using Random Forest Classifier and AdaBoost Classifier, to predict fraudulent transactions based on the available features.

* Features Importance: *
The importance of each feature in the predictive models is visualized through bar plots, offering insights into which features contribute most to the prediction.

* Area Under Curve (AUC) Calculation: *
The script calculates the area under the ROC curve, providing a metric to assess the performance of the machine learning models.

* Confusion Matrix Visualization: *
The confusion matrix is plotted to evaluate the performance of the machine learning models in terms of correctly and incorrectly classified instances.

This comprehensive script serves as a guide for credit card fraud detection using machine learning techniques, providing thorough data analysis, visualization, and model building steps.
