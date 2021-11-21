#Football Analysis (Mchezopesa Ltd company)
This project is aimed at  predicting the result of a game between team 1 and team 2, based on who's home and who's away,
and on whether or not the game is friendly (include rank in your training).
Two approaches are used in making the predictions, with *Home team*, *Away team*, *Tournament type (World cup, Friendly, Other)* as Input

##Approach 1: Polynomial approach

What to train given:

Rank of home team
Rank of away team
Tournament type

Model 1: Predict how many goals the home team scores.

Model 2: Predict how many goals the away team scores.

##Approach 2: Logistic approach

Feature Engineering: Figure out from the home team’s perspective if the game is a Win, Lose or Draw (W, L, D)

In order to work on the above problem, you need to do the following:

# Success Metrics

##For the project to be successful, the following was done:

1. Define the question, the metric for success, the context, experimental design taken and the appropriateness of the available data to answer the given question
2. Expected flow for the assessment:
3. Perform your EDA
4. Perform any necessary feature engineering 
5. Check of multicollinearity
6. Start building the model
7. Cross-validate the model
8. Compute RMSE
9. Create residual plots for your models, and assess their heteroscedasticity using Bartlett’s test
10. Perform appropriate regressions on the data including your justification
11. Challenge your solution by providing insights on how you can make improvements

#Dataset
The dataset and glossary used for this project can be found here. [https://drive.google.com/open?id=1BYUqaEEnFtAe5lvzJh9lpVpR2MAvERUc] 
