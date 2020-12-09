# Machine Learning Final Project - Predicting MLB Player's Positions

### Question to answer: Using the statistics of MLB players every season (To qualify, a player must have 3.1 PA per team game played), can we predict their position that they play?

 ## Process

### 1. I used the data on MLB's stats website and pulled in each year from 1990-2020 and the statistics of each player.
### 2. Using Regular Expressions, I cleaned up the data I was working with and grabbed their positions that they play.
### 3. Then I tried fitting lots of different Classification models. A few that I fit to my data was KNN, Decision Tree, Random Forest, Gradient Boost, Logisitic Regression, LinearSVC, and Gaussian Bayes
### 4. After looking at the accuracy of each model in predicting the correct player position, I ended up choosing a Random Forest Classifier model.

 ## Conclusion
### I found that my Random Forest model was 67% accurate on predicting the player to be in one of the 10 positions that it had to choose from. The statistics that helped my model most in predicting the players position was the number of walks the player had, the number of stolen bases he had, and the number of runs batted in he had.
