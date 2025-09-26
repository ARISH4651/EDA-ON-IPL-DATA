IPL Overwise EDA Analysis

---
Overview
This repository contains an IPython notebook (EDA_ANALYSIS.ipynb) for performing Exploratory Data Analysis (EDA) on Indian Premier League (IPL) match data. The analysis focuses on over-by-over statistics from IPL matches, excluding super overs. The dataset provides insights into runs scored, wickets taken, batting and bowling teams, and match outcomes.
Key objectives:
---
Load and preprocess IPL data.
Perform basic EDA to understand patterns in runs, wickets, and team performance.
Prepare features (X) and target (y) for potential machine learning tasks, such as predicting the winner.
---
The notebook demonstrates data loading, cleaning, label encoding for categorical variables (e.g., team names), and initial data splitting.
Dataset
The analysis uses the dataset: Overwise statistics without super over.csv.

---
Columns:

match_id: Unique identifier for the match.
inning: Inning number (1 or 2).
batting_team: Name of the batting team (label encoded in the notebook).
bowling_team: Name of the bowling team (label encoded in the notebook).
over: Over number in the inning.
runs: Runs scored in that over.
wickets: Wickets taken in that over.
winner: Winning team (target variable).

---









match_idinningbatting_teambowling_teamoverrunswicketswinner1.01.0Sunrisers HyderabadRoyal Challengers Bangalore1.07.00.0Sunrisers Hyderabad1.01.0Sunrisers HyderabadRoyal Challengers Bangalore2.016.01.0Sunrisers Hyderabad........................
The dataset contains 28,952 rows covering multiple IPL matches.
