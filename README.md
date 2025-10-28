README - AI Lab Test Project
Group Information

- Group Name: AI_Lab_Team
- Course Code: CSC 315 – Artificial Intelligence
- Institution: Veritas University Abuja
- Supervisor: Mr. Uloko Felix
- Submission Date: October 2025

Group Members
Name	Matric No.	Role
Abubakar Hannatu	VUG/CSC/23/8831	Model Training & Evaluation
Paulic Esther	VUG/CSC/23/9271	Data Cleaning & Feature Engineering
Akande Oreoluwa	VUG/CSC/23/8839	Explainability & Visualization
Nwachukwu Ugochuwku Collins	VUG/CSC/23/10710	Documentation & Report Writing

Project Overview
This project focuses on sports analytics using Artificial Intelligence techniques.
The task involves data preparation, model training, explainability, and visualization
for a predictive sports dataset.

Objectives
1. To clean and preprocess a real-world dataset for model readiness.
2. To create new meaningful features that enhance prediction accuracy.
3. To train, evaluate, and tune at least two ML algorithms.
4. To apply model explainability (e.g., SHAP) to interpret results.
5. To visualize model performance with clear metrics and plots.

Dataset Description
- The dataset represents student’s performance in a classroom.
- Original dataset: data/studentperformance.csv
- Cleaned dataset: data/processed_data.csv
- Target Variable: target (binary classification: 1 = Success, 0 = Fail)

Project Structure
AI_Lab_Group H
 ┣   data/
 ┃ ┣ studentperformance.csv
 ┃ ┗ processed_data.csv
 ┣ notebooks/
 ┃ ┗ main_notebook.ipynb
 ┣ reports/
 ┃ ┗ AI_Lab_Report.pdf
 ┣ requirements.txt
 ┗ README.md


How to Run the Project
•	Setup Environment:
Ensure Python 3.8+ is installed, then run:
    pip install -r requirements.txt
•	Run the Jupyter Notebook:
    jupyter notebook notebooks/main_notebook.ipynb
•	 Outputs Generated:
- Processed dataset (data/processed_data.csv)
- Model comparison table (accuracy, F1, precision, recall)
- SHAP visualizations
- 5–6 performance graphs
- Final report (reports/NLP_Lab_Report.pdf)

Models Used
Model Key Parameters	Notes
Logistic Regression	max_iter=1000	Baseline linear model
Random Forest	n_estimators=300, tuned max_depth	Best performing model
KNN (optional)	n_neighbors=5	For comparison


Explainability
- Used SHAP (SHapley Additive exPlanations) to interpret predictions.
- Top 3 most influential features were identified.
- Visuals included SHAP summary plot, dependence plots, and feature importance charts.
Evaluation Metrics


Metric	Description
Accuracy	Overall correctness |
Precision	% of correct positive predictions |
Recall	% of actual positives detected
F1 Score	Harmonic mean of precision & recall |
ROC-AUC	Ability to separate classes

Visualizations Included
1. Model Accuracy Comparison (bar chart)
2. Confusion Matrix (heatmap)
3. ROC Curve
4. Feature Importance (barh)
5. SHAP Summary & Dependence Plots

Report Summary
- Total features engineered: 3
- Missing data handling: Median + mode imputation
- Best model: Random Forest (highest F1 & AUC)
- Explainability tool: SHAP
- Visuals generated: 3 total
- Conclusion: Feature engineering and tuning significantly improved model performance.

Submission Instructions
- Upload all project files to GitHub under the correct group repository.
- Repository name format: AI_Lab_Group H
- The group leader should email the repository link to:
    ulokof@veritas.edu.ng

Acknowledgements
Special thanks to Mr. Uloko Felix for guidance during the AI Laboratory sessions
and for providing the framework for this lab assessment.

