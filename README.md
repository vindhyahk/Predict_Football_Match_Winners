# EPL Football Match Winner Prediction ⚽🌟

This project uses **Machine Learning** to predict the outcome of **English Premier League (EPL)** matches.  
We clean and prepare match data, create predictive features, and train a **Random Forest** model to forecast winners.  
A **heatmap** is also generated using **Seaborn** to visualize model evaluation.

## Project Overview 📖
- Load EPL match data into a pandas dataframe.
- Investigate and handle missing data.
- Engineer useful features like goal differences and rolling averages.
- Train a **Random Forest Classifier** to predict match outcomes (Home Win / Draw / Away Win).
- Improve prediction accuracy using rolling averages of team performance.
- Visualize model performance with a confusion matrix heatmap.

## Technologies Used 🛠
- Python 3
- Pandas
- NumPy
- Scikit-learn
- Seaborn (for heatmap)

## Dataset 📄
- Historical EPL match results (Home Team, Away Team, Goals, Full-Time Result).
- Features like goal differences, rolling averages over previous matches, and team stats were created to enhance model performance.

## Key Machine Learning Techniques 📚
- **RandomForestClassifier** (scikit-learn)
- Handling missing values
- Rolling averages for feature engineering
- Model evaluation with accuracy score and confusion matrix heatmap

## Confusion matrix

<img width="473" alt="Image" src="https://github.com/user-attachments/assets/3af56116-d63e-47e6-9ac5-2f5078a2ef2b" />

