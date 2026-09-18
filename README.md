# EPL Pythagorean Win Predictor

Notebook.ipynb
Applies the Pythagorean expectation formula to English Premier League
data to test whether goal difference predicts win percentage, and whether
early-season form predicts late-season results.

## What this does
- Builds Pythagorean win% from goals for/against, home and away, 2017-18 EPL season
- Regresses actual win% on Pythagorean win% for two split periods within the season
- Tests correlation between early-season and late-season win%

## Results
- Pythagorean win% is a strong predictor of actual win%

## Tech
Python, pandas, statsmodels (OLS), seaborn

## Data
EPL match results, 2017-18 season
