🧠 Task 5: Decision Trees and Random Forests
📌 Objective
This task aims to learn and apply tree-based models (Decision Trees and Random Forests) for classification and regression, with a focus on:

Model training

Overfitting control

Visualization

Feature importance interpretation

Cross-validation evaluation

🛠️ Tools & Libraries
Language: Python 3.x

Libraries:

pandas, numpy – Data manipulation

matplotlib, seaborn – Visualization

scikit-learn – Machine learning models

graphviz – Tree visualization (optional)

📂 Dataset
Dataset Used: Heart Disease Dataset

You can also download the dataset directly:
📥 Click here to download dataset

Rows: 1025 patients

Features: 13 clinical attributes (e.g., age, cholesterol, chest pain)

Target: 0 = No disease, 1 = Disease

✅ Tasks Completed
1. Train a Decision Tree Classifier and Visualize It
Used DecisionTreeClassifier from scikit-learn

Controlled max_depth to avoid overfitting

Visualized the tree using plot_tree

2. Analyze Overfitting and Control Tree Depth
Compared shallow (max_depth=3) and deep trees

Observed accuracy and generalization effects

3. Train a Random Forest and Compare Accuracy
Used RandomForestClassifier with 100 trees

Compared performance with decision tree

Achieved higher accuracy and better generalization

4. Interpret Feature Importances
Used .feature_importances_ attribute

Visualized with horizontal bar plots

Top features: ca, thal, cp, oldpeak

5. Evaluate Using Cross-Validation
Used cross_val_score with 5-fold CV

Decision Tree Avg Accuracy: ~83%

Random Forest Avg Accuracy: ~99%

📈 Results Summary
Model	Test Accuracy	Cross-Validation Accuracy
Decision Tree	78.05%	83.02%
Random Forest	98.54%	99.41%

📊 Visualizations
Confusion Matrices

Classification Reports

Decision Tree Diagram

Feature Importance Graphs
