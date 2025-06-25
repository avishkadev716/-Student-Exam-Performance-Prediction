 -Student-Exam-Performance-Prediction-

Predict whether a student will pass or fail an exam based on demographic and academic features using machine learning.

 🎯 Project Goal

The objective of this project is to build a machine learning model that predicts student exam outcomes (pass/fail) using various academic and socio-demographic factors. This can help educators identify students at risk and provide early interventions.

 📁 Dataset

We use the publicly available [Student Performance Dataset](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams) . It includes:

- Gender, Race/Ethnicity
- Parental Level of Education
- Lunch Type
- Test Preparation Course
- Math Score, Reading Score, Writing Score

📊 Project Workflow
Load and explore the dataset

Create the Passed target column

Encode categorical variables

Split the data into training and testing sets

Train a logistic regression model

Evaluate model performance using accuracy, confusion matrix, and classification report

Visualize results with plots

📦 Libraries:
pandas, numpy, scikit-learn, matplotlib, seaborn

📈 Sample Output
Accuracy: 85% (varies with parameters)

Classification Report:

Precision, Recall, F1-score

Confusion Matrix Heatmap using seaborn
