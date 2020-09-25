# NFL_Spread_Win_Prediction

This repository provides a Jupyter Notebook that creates models for threem aspects of NFL prediction: spread, whether the away or home team wins, and whether the away or home team beats the spread. Provided in NFL_Spread_Prediction.ipynb is the notebook containing the process for generating these models and predicting new games. 

The test data RMSE for the model predicting spread was 11.3 points, the test data accuracy for the model predicting whether a team will win was 75%, and the test data accuracy for the model predicting whether the away team will beat the spread was 64%.

These models were created using year-end per game statistics, so the accuracy should improve as more data is available in the season. An alternate dataset was previously created based on boxscores of the past five games, but the models did not perform nearly as well on this dataset, so the current methodology was used.

The performance of these models in predicting results of the 2020 season is being tracked and is publicly viewable using the link below to the Google Sheets document.
https://docs.google.com/spreadsheets/d/1oKzjGUAT-V9WGUYUuwgZZI4dKZicwhVgaDZ3TPhJdW4/edit?usp=sharing
