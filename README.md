# Sport-Data-Analytics
For the Module Sport Data Analytics this Group worked with the Data from the E-Sport Game Dota2.
Here follows a short description of each task completed. Detailed evaluation of the task is found in each Jupyter Notebook.
## Task 1 Skill vs Luck
There are a few rules, which define if an activity is considered a sport or not.
An important factor is that the factor luck to win a game is decreased to a minimum. In the Jupyter Notebook Skill vs. Luck we explain how the Game Dota2 works and compute the Skill vs. Luck Ratio of Dota2.
Also there is a short introduction video explaining the most important rules of the Game Dota2.


## Descriptive Analysis
Befor starting with any Prediction, we explored and visualized the data in the Jupyter Notebook "Descriptive_Analysis".

## Predicting which Team wins the Game

Our goal was to create a Machine Learning Model which is able to predict a Dota2 games outcome.
In the Jupyter Notebook "Prediction" we started training a model with multiple features, which some of them are generated during the game.
So it was not surprising, that the accuracy of our model was really high. But there's no need to predict the games outcome after it was already played. It is interesting before it even started or than during the game.
So in the Jupyter Notebook "Prediction_minute_0" we computed a model which predicts the game outcome only by the Heros chosen by each team. There we can see, that with only this information it isn't possible to make a good prediction.

## Team Preparation
Because we did not manage to create an accurate model to predict a Dota2 games outcome, we also worked at the "Coaching Task". The Jupyter Notebook "Team_Preparation" can be used as a Dota2 Team Coach. You can see the statistics of each team and see how to prepare best for the next game with a known opposite team.

## Event Detection
For the event detection task we used the given badminton dataset. We explored and visualized the data.


