# NBA Player Longevity Prediction

## Dataset Source
NBA rookie statistics dataset.

## Prediction Goal
Predict whether a player will remain in the NBA for at least five years (`target_5yrs`).

## Feature Engineering Workflow

1. Define `target_5yrs` as the target variable.
2. Remove non-predictive columns such as player names and IDs.
3. Perform correlation analysis to identify redundant features.
4. Create new features:
   - Points Per Minute
   - Efficiency Rating
5. Handle missing values using median imputation.
6. Produce a clean dataset suitable for machine learning.

The notebook contains executed code and markdown explanations describing all feature engineering decisions.
