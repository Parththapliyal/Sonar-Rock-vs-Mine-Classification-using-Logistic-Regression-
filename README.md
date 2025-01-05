Sonar Rock vs Mine Classification using Logistic Regression
📄 Overview
This project involves classifying objects as either Rock or Mine using a Logistic Regression model. The dataset contains sonar signal attributes to distinguish between the two classes. The primary objective is to build a predictive system with high accuracy for real-world application in sonar signal classification.

🛠️ Workflow
Data Preprocessing:

Loaded the dataset (sonar_data.csv) and analyzed its structure.
Checked for missing values (none were found).
Dataset contained 208 samples and 61 columns.
Exploratory Data Analysis:

Described the dataset using statistical summaries (df.describe()).
Examined class distribution:
111 Mine samples (M).
97 Rock samples (R).
Feature Engineering:

Dropped the target column (60) from features.
Split the dataset into:
Features (X) and Target (y).
Applied stratified splitting to balance the classes during training and testing.
Model Training:

Split data into training (90%) and testing (10%) sets.
Trained a Logistic Regression model using sklearn.
Achieved:
Training Accuracy: 83.42%.
Testing Accuracy: 76.19%.
Prediction System:

Built a prediction pipeline to classify new sonar signals based on input data.
Example Input: (0.0262, 0.0582, ..., 0.6473)
Output Prediction: ['M'] (Mine).
🧰 Technologies Used
Python Libraries:
pandas for data manipulation.
numpy for numerical computations.
matplotlib and seaborn for visualization.
scikit-learn for model training and evaluation.
📊 Results
Training Set:
Logistic Regression achieved an accuracy of 83.42%.
Test Set:
Logistic Regression achieved an accuracy of 76.19%.
Visualizations helped understand the dataset's distribution and class separation.
🔍 Key Insights
Logistic Regression is effective in sonar signal classification with acceptable accuracy.
The dataset is balanced, with no missing values, making it suitable for logistic regression.
Prediction pipeline can be extended to classify real-time sonar data for practical use.
