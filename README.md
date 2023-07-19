# Handling Imbalanced Datasets with ML Models: Hypothyroid Case Study

Description:
In this project, I worked on a Hypothyroid dataset, aiming to build and evaluate various machine learning classification models while addressing the challenge of an imbalanced dataset. To achieve this, I utilized Python with popular data analysis and visualization libraries, including Pandas, NumPy, Matplotlib, Seaborn, and Missingno.

The project involved the following steps:

1. Data Preprocessing:
   - Loaded the Hypothyroid dataset from a CSV file and created backup copies for safekeeping.
   - Handled missing values using imputation techniques: SimpleImputer for categorical 'sex' column and KNNImputer for numerical features such as 'TSH', 'T3', 'TT4', 'T4U', and 'FTI'.
   - Transformed categorical features into numerical values using LabelEncoder.

2. Addressing Imbalanced Dataset:
   - Checked the class distribution of the target variable 'binaryClass' to confirm an imbalanced dataset.
   - Employed Random Oversampling to balance the classes with a 15% sampling strategy.

3. Classification Model Evaluation:
   - Utilized several classification algorithms with default hyperparameters, including Logistic Regression, Decision Tree, Random Forest, Extra Trees, K-Nearest Neighbors, Support Vector Machine (SVM), Bagging Classifier, Gradient Boosting, LightGBM, and Gaussian Naive Bayes.
   - Split the dataset into training and testing sets (70% training, 30% testing).
   - Evaluated each model's performance using metrics such as accuracy, precision, recall, F1 score, specificity (true negative rate), balanced accuracy, and Matthews Correlation Coefficient (MCC).
   - Plotted the Receiver Operating Characteristic (ROC) curve for each model and calculated the Area Under the Curve (AUC) score to assess their performance.

4. Correlation Analysis:
   - Conducted correlation analysis between features to understand the relationships and identify potential patterns.

5. Data Visualization:
   - Created a bar plot to visualize the status of patients (target variable 'binaryClass').
   - Generated a heatmap to visualize feature correlations using Seaborn.

Overall, the project aimed to evaluate various machine learning models' performance on an imbalanced dataset and explore methods to handle class imbalance. The insights gained from this project can be valuable in real-world applications where dealing with imbalanced data is a common challenge in classification tasks.
