# Mental Health Prediction Using Machine Learning
A machine learning project using AutoGluon to predict depression based on mental health survey data. The goal is to leverage automated ML to identify key features affecting mental health and evaluate predictive models for accuracy and interpretability.


## Dataset
Dataset: [kaggle.com]
📊 Dataset: Includes various psychological and demographic features.
🧪 Task: Binary classification — Predict if an individual is likely to experience depression
Target Feature: Depression
Rows: 27901, Columns: 20
Features include: Age, Gender, Stress, Sleep, Exercise, etc.


## Features
📊 Data Visualization: Heatmaps, bar plots, and confusion matrix
🧹 Feature Engineering: Handling missing values, encoding, etc.
⚙️ AutoML with AutoGluon: Fast model training and tuning
📈 Model Evaluation: Accuracy, feature importance, leaderboard
🧪 Confusion Matrix: Visual check of prediction performance

**Top Features:**  
  ![Feature Importance](confusionmatrix_depression.png)
- **Confusion Matrix:**  
  ![Confusion Matrix](featureimport_depress.png)


## 📌 How to Run
Clone this repo:
git clone https://github.com/yourusername/Mentalhealth_ML.git
cd Mentalhealth_ML

Install dependencies:
pip install -r requirements.txt

Run the notebook:
Open Mentalhealth_ML.ipynb in Jupyter or VSCode
Run all cells step by step

## Key Outcomes:
Accuracy: 90%
Most important features: Have you ever had suicidal thoughts?, Academic Pressure, Financial Stress, Age, Dietary Habits

## 🔍 Visualizations
Confusion Matrix
Feature Importance

## 💡 Future Improvements
Improve feature engineering with more external data
Use Explainable AI (e.g., SHAP values) for deeper insights
Convert the model into an API/web app

##  📚 Requirements:
pandas
matplotlib
seaborn
scikit-learn
autogluon

##  👩🏾‍💻 Author
Mary Eyeson
Data Analysis & Machine Learning Enthusiast
📍 Dallas, TX
