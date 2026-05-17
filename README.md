🫀 Heart Disease Prediction & Diagnostic Analytics
An end-to-end Machine Learning pipeline designed to analyze clinical patient data and predict the likelihood of ischemic heart disease. This project demonstrates data engineering, comprehensive Exploratory Data Analysis (EDA), and a comparative performance study between parametric and non-parametric predictive models.

🎯 Project Objectives
The main objectives of this project are:

Automate Data Auditing: Detect and handle structural duplicates or missing value anomalies seamlessly.

Clinical Exploratory Data Analysis: Uncover correlations between biometric markers (age, chest pain type, max heart rate) and cardiac risks.

Train Diagnostic Classifiers: Build, optimize, and cross-validate predictive machine learning workflows.

Interpret Model Logic: Map structural feature weights and decision boundaries to keep predictive pipelines transparent.

Visualize Evaluation Dashboards: Output professional analytical charts for evaluation auditing.

🏗️ Project Architecture
📁 Heart-Disease-Prediction
│
├── 📄 heart.csv                # Clinical input dataset (Features & Target)
├── 📄 heart_predict.py         # Main automated training and evaluation script
├── 📄 requirements.txt         # Pre-requisite environment dependencies
│
└── 📊 Output Analytics
    ├── 📉 eda_overview.png      # Target distribution and feature correlations heatmap
    ├── 📉 model_evaluation.png  # Confusion matrices, ROC curves, and accuracy bars
    └── 📉 decision_tree.png     # Visual structure graph of the optimized decision path

📊 Results Summary
    ModelTest AccuracyCV Accuracy (5-Fold)ROC-AUC ScoreLogistic RegressionAuto-generatedAuto-generatedAuto-generatedDecision TreeAuto-generatedAuto-generatedAuto-generated.
