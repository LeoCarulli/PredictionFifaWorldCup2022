![fifaworldcup](https://user-images.githubusercontent.com/111923298/206928761-378f136c-d3a8-47d8-a093-c9d761fa65a7.jpeg)


# FIFA World Cup 2022

The aim of this project is to predict the FIFA 2020 World Cup held in Qatar. For this analysis, we will grab information from two main sites.
- FIFA 23 Videogame dataset, from where we obtained player statistics.
- FIFA Nations ranking and historical international matches.

## There are 4 Python Scripts present on this repository, as below:

### Fifa 23 Data Preparation

Aims to determine the potential of the teams qualified for the QATAR 2022 World Cup based on the FIFA 22 player statistics.

### EDA & Training set

Determines the potential of the teams qualified for the QATAR 2022 World Cup based on FIFA Ranking and also does some relevant analysis with the information.

### Model creation Official

This notebook consists of gathering all the data created from the 2 following scripts:

- Fifa 23 DataPreparation
- EDA & training set

Also, here we will proceed with the creation of the Machine Learning Model we will use on our FIFA World Cup Predictions. We opted for a RandomForest model with hyperparameter tuning and exported the information with a pipeline to perform easy inferences.

![image](https://user-images.githubusercontent.com/111923298/206928587-5338e762-e85b-4ff0-949d-2ea54367fc14.png)

Please consider that for this analysis, we only considered two results: Win or Lose. Further details present on notebooks.

### Predictions

Aims to predict the results of the FIFA Qatar 2022 Group Stage and Knockouts.

Final Outcome:

![image](https://user-images.githubusercontent.com/111923298/206928729-1bb72963-389c-4c67-8096-180d5b6d1558.png)


# Datasets

- Fifa 23 Players Data - The datasets provided include the player data for FIFA 23.
- fifa_rankings - takes the FIFA world rankings from the Official FIFA World Men Ranking. 
- international_matches - Provides a complete overview of all international soccer matches played since the 90s. On top of that, the strength of each team is provided by incorporating actual FIFA rankings as well as player strengths based on the EA Sport FIFA video game.
- group_stage & Qatar2022-teams - have information about the FIFA world cup matches to be disputed.
- team_scores - file created on "EDA & Training set" file. It provides stats for all teams present on world cup.
- squadstats11 & squadstats26 - files created on "Fifa 23 Data Preparation". It includes all the players that should have been called for the World Cup, for each team.
- training_set - file created on "EDA & Training set". It has the training information for the ML model to be used on "Model creation Official"

# Resources

- Python Version: 3.7
- Main Packages: Pandas, Numpy, Sklearn, Tensorflor, MatplotLib and Seaborn.
