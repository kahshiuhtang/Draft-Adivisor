# DRAFT ADVISOR

## Purpose:

- Allow users to assess who to draft in fantasy football
  - Analyze Team Importance on Player Performance
  - Analyze Age Impact on Player Performance
  - Analyze Strength of Schedule and Impact on Player Performance
  - Predict Whether a Player Will Over/Under Perform their ADP

## Analysis

- Will be carried out with pandas, numpy, scikit-learn
- In scikit-learn, a DecisionTree and SVM models will be used to model data
- Code will be written in Python & Jupyter Notebook
- Implement Neural Netowrk (MUCH LATER)

## Data [SportsReference]:

- ### Team Stats Taken **[2015-2021 Season]**:
  - Team Offense
    - Passing Offense
    - Rushing Offense
    - Scoring Offense
    - Conversions
    - Drive Averages
  - Defense
    - Team Defense
    - Team Advanced Defense
    - Passing Defense
    - Rushing Defense
    - Scoring Defense
    - Conversions Against
    - Drive Averages Against
- ### Player Stats Taken **[2015-2021 Seasons]**:
  - **Passing**
    - Passing
    - Advanced Stats **[2018-2021 Season ONLY]**:
      - Air Yards
      - Accuracy
      - Pressure
      - Play Type **[2018-2021 Season ONLY]**
    - Player Fantasy Rankings
    - Red Zone Passing
  - **Rushing**
    - Rushing
    - Advanced Rushing **[2018-2021 Season ONLY]**
    - Player Fantasy Rankings
    - Red Zone Passing
  - **Receiving**
    - Receiving
    - Advanced Receiving **[2018-2021 Season ONLY]**
    - Player Fantasy Rankings
    - Red Zone Passing
