# IPL_SCORE_PREDICTOR

## Overview
This project focuses on predicting IPL first-inning scores using machine learning regression models. The dataset consists of ball-by-ball data from various IPL matches, and the model is trained to predict the total score based on match conditions.

## Dataset: `ipl_data.csv`

### Description
The dataset contains ball-by-ball details of IPL matches, including batting and bowling teams, players, and real-time match statistics.

### Columns
- `mid`: Match ID
- `date`: Date of the match
- `venue`: Stadium where the match was played
- `bat_team`: Batting team name
- `bowl_team`: Bowling team name
- `batsman`: Batsman currently playing
- `bowler`: Bowler currently bowling
- `runs`: Runs scored on the ball
- `wickets`: Total wickets lost till that ball
- `overs`: Completed overs in the match
- `runs_last_5`: Runs scored in the last 5 overs
- `wickets_last_5`: Wickets lost in the last 5 overs
- `striker`: Current batsman's ID
- `non-striker`: Non-striker's ID
- `total`: Final first-inning score

## Jupyter Notebook: `IPL_Score_Predictor.ipynb`

### Steps Covered
1. **Data Loading & Cleaning**
   - Importing the dataset and handling missing values.
2. **Exploratory Data Analysis (EDA)**
   - Understanding data distribution, trends, and visualizations.
3. **Feature Engineering**
   - Selecting relevant features for prediction.
4. **Model Training**
   - Using regression models like Linear Regression, Decision Tree, or Random Forest.
5. **Prediction & Evaluation**
   - Evaluating model performance using RMSE and R-squared metrics.

## How to Run
1. Install dependencies using:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook IPL_Score_Predictor.ipynb
   ```
3. Run the notebook cells sequentially to train and evaluate the model.

## Future Enhancements
- Implementing deep learning models for better accuracy.
- Integrating real-time match data for live predictions.
