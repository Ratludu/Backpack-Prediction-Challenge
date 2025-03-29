# Backpack Prediction Challenge - Kaggle Playground S5E2  

## Results
My final model "Backpack_Prices_Final_Notebook_Config.ipynb" had a private leaderboard score of 38.64204, which placed me at 15th out of 3,393 teams. Thats a top 1% solution! 

## Final Solution
My final solution consisted of a single cat boost model with a whole heap of feature engineering. The data had very little signal so I used target encoding with aggregation stats like mean, std, median, min, max and skew to help capture as much signal as possible. I also wrote a function that would recursivly add features if they improved the overall cross validation. This was done in batches of 10 features. 

I used weights and biases to track model performance and configurations. The models would take a couple of hours to run at 25 folds, this helped greatly when tuning the model parameters.

## Competition Overview  
The **Backpack Prediction Challenge** is part of Kaggle’s **Playground Series (Season 5, Episode 2)**, designed to provide a practical machine learning challenge for participants of all levels. This competition focuses on developing predictive models using structured tabular data related to backpacks.  

## Objective  
Participants are tasked with building a machine learning model to accurately predict **Backpack Prices** based on a set of given features. 

A detailed dataset description is available on the [**Kaggle Data Page**](https://www.kaggle.com/competitions/playground-series-s5e2/data).  

## Evaluation Metric  
Submissions are assessed based on the Root Mean Squared Error (RMSE).

## Key Resources  
- [**Competition Page**](https://www.kaggle.com/competitions/playground-series-s5e2/)  
- [**Discussion Forum**](https://www.kaggle.com/c/playground-series-s5e2/discussion)  
- [**Leaderboard**](https://www.kaggle.com/competitions/playground-series-s5e2/leaderboard)  
