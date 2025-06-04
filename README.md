Heart Disease Prediction Using Machine Learning
📘 Project Summary
This project applies supervised machine learning techniques — Decision Tree Classifier and Random Forest Classifier — to predict the presence of heart disease based on clinical attributes. The objective is to demonstrate practical model development, performance comparison, and interpretation of medical data for diagnostic assistance.

🎯 Problem Statement
Heart disease is a leading cause of death globally. Early prediction using patient data can assist healthcare providers in timely diagnosis and treatment. This project aims to build predictive models that can classify whether a patient is likely to have heart disease based on several input features.

📂 Dataset Overview
The dataset includes several medical parameters such as:

Feature	Description
age	Age of the patient
cp	Chest pain type
chol	Serum cholesterol level
thalach	Maximum heart rate achieved
oldpeak	ST depression induced by exercise
ca	Number of major vessels colored
...	Other clinical attributes

Target Variable:

0 = No heart disease

1 = Presence of heart disease

🔧 Methods Used
🧩 Step 1: Data Loading & Preprocessing
Loaded the dataset using Pandas.

Checked for null values and ensured data integrity.

Split data into input features (X) and target variable (y).

🌳 Step 2: Decision Tree Model
Trained a basic Decision Tree Classifier.

Visualized the tree structure using plot_tree().

Evaluated accuracy and identified overfitting issues.

🧠 Step 3: Overfitting Control
Limited tree depth using max_depth.

Compared model accuracy at different depths to balance bias and variance.

🌲 Step 4: Random Forest Classifier
Trained a Random Forest with multiple decision trees.

Improved accuracy and reduced overfitting.

Evaluated and compared model performance.

📌 Step 5: Feature Importance
Extracted and visualized the most influential features.

Annotated importance values to improve interpretability.

🔁 Step 6: Cross-Validation
Used k-fold cross-validation (k=5) for robust model evaluation.

Compared average cross-validated scores of both models.

📊 Performance Comparison
Metric	Decision Tree	Random Forest
Test Accuracy	~85%	~90%
CV Accuracy	~82%	~88%

📈 Visualizations
✔ Decision Tree Diagram

✔ Tree Depth vs Accuracy Line Plot

✔ Random Forest Feature Importance Bar Chart (with values)

🛠 Tools & Technologies
Programming Language: Python

Libraries:

pandas, numpy – data handling

matplotlib, seaborn – visualizations

scikit-learn – model building & evaluation
