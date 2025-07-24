🧠 Missing Data Imputation using KNN
This project demonstrates how to handle missing values in a dataset using KNN Imputer from scikit-learn, and then apply a Logistic Regression model for classification.

📌 Project Highlights
Identifies and visualizes missing values in the dataset.

Uses KNNImputer to fill in missing values based on feature similarity.

Splits the data into training and testing sets.

Fits a LogisticRegression model on the imputed data.

Evaluates model performance using accuracy_score.

🛠️ Tools and Libraries Used
Python 3

NumPy

Pandas

Matplotlib / Seaborn

scikit-learn (KNNImputer, LogisticRegression, train_test_split, accuracy_score)

🔄 Workflow
Data Loading and Exploration

Load dataset and check for missing values.

Perform initial data analysis.

Missing Value Handling

Apply KNNImputer to fill missing values.

Compare distributions before and after imputation.

Model Building

Split the dataset using train_test_split.

Train a LogisticRegression model on the imputed training data.

Model Evaluation

Predict on the test set.

Evaluate accuracy and visualize results.

