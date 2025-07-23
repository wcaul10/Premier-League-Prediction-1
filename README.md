# Premier League Match Outcome Predictor ⚽

This project uses Premier League data from the 2014/15 to 2018/19 seasons to train a Decision Tree model that predicts match results (Home Win, Away Win, Draw).

## 📌 Project Overview

- **Goal**: Predict full-time results (FTR) using historical match stats
- **Model**: Decision Tree Classifier (`sklearn`)
- **Features Used**:
  - Shots, shots on target, corners
  - Home & away teams (one-hot encoded)
  - Season, cards, fouls, betting odds, half-time result

## 📊 Accuracy Comparison

I tested how adding more features affected accuracy. Here's the result:

<img width="1000" height="500" alt="feature_accuracy" src="https://github.com/user-attachments/assets/b25b98fb-6ce7-4b45-9950-b9dffb74ed5a" />


## 🔧 Technologies

- Python
- Pandas
- Scikit-learn
- Matplotlib
- Jupyter Notebook

## 📁 Files

- `PLModel.ipynb` — Jupyter Notebook with all code, cleaning steps, training, and chart
- CSVs — historical data from 2014 to 2019

## 🚀 Future Ideas

- Try other models (Random Forest, Logistic Regression)
- Predict goal counts instead of just match outcome
- Include ELO ratings or form
- Create a more accurate model

---

## 🤔 Why this project?

As a football fan and AI student, I wanted to combine machine learning with real-world data. This helped me practice:
- Data cleaning and merging
- Feature engineering
- Model training and evaluation
Overall, football is a very unpredictable game, hence the low percentages.

