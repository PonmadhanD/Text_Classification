__*****🎵 Synthetic Music Genre Classification using CatBoost*****__<br>
**📌 Project Overview**<br>
This project demonstrates an end-to-end machine learning pipeline for multi-class music genre classification using a synthetic dataset.
Instead of relying on real-world data, the project generates a fully reproducible dataset simulating audio metadata and numerical features, making it ideal for learning, experimentation, and demonstration purposes.

**📂 Features**<br>
Synthetic dataset generation with realistic audio-related features

11 music genres classification

Feature engineering with aggregated artist & track statistics

CatBoostClassifier for high-performance, native categorical handling

Stratified K-Fold Cross Validation for robust model evaluation

Log-loss scoring for probabilistic accuracy

Confusion matrix visualization for fold analysis

CSV output with predicted probabilities

**🎯 Problem Statement**<br>
Given a dataset of artist names, track metadata, and audio features, predict the genre of a song from the following classes:

Acoustic/Folk

Alt Music

Blues

Bollywood

Country

HipHop

Indie Alt

Instrumental

Metal

Pop

Rock

**🛠️ Tech Stack**<br>
Language: Python 3.x

Libraries:

pandas, numpy – Data handling

scikit-learn – Model evaluation & utilities

catboost – Classifier

matplotlib, seaborn – Visualization

**📊 Workflow**<br>
Generate synthetic dataset simulating audio features

Preprocess data & engineer aggregated features

Split dataset using Stratified K-Fold

Train CatBoost model on each fold

Evaluate using log-loss and visualize results

Save predictions to CSV

**📈 Model Evaluation**<br>
Metric: Log-loss (multi-class)

Output: Confusion matrix, classification report per fold

**📜 License**<br>
This project is licensed under the MIT License – feel free to use and modify for educational purposes.
