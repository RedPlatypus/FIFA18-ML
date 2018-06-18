# FIFA 2018 World Cup Predictions

This was my attempt at getting a machine learning algorithm to predict the 2018 FIFA World Cup Results. This projects includes 3 datasets. 

1. data/player_features.csv -> Player Features. Ranking of 17k players, by over 50 attributes
1. data/players_by_team.csv -> Players on each FIFA 2018 team by country.
1. data/team_results.csv -> A list of matches going back to the early 1900's

The goal is to predict Win Loss & Draw for teams in the 2018 FIFA WORLD CUP

## Setup

`Install Python3`

`Install Juypter Notebook`

Install `Tensorflow, Pandas, XGBoost, SKlearn` (Sci Kit Learn)

run `$ Jupyter notebook` from the folder this project is installed in.

You can run the cells then from 1-whatever inspecting as you go.

## Contribution

Feel free to fork & if you have a fix for the current errors, that would be greatly appreciated.

## Strategy

The traing data would set teams against one another, with their players features & show it the results.

Players features (skill, ranking, agressiveness, preffered position, foot skill, defense skill etc...) were summed up for each game going back to 2009, and the team win, lose or draw should show some coorelation to the players playing that game.

## Drawbacks

Ideally, we would have another dataset. One that ties players to each of their historical games. Becuase this information was lacking, teams were 'joined' with their national teams who were led to compete with one another. Of course this is wrong because due to recent hires, trading, and injuries, the same players wouldn't have played every game for their national team back to 2009.

Even though the player_features.csv tracks over 17,000 players, there is no player on Saudi Arabia. More data is needed for them. Other intersting teams include Korea, which has data for only 2 of the team.

In reverse circumstance, the Brazil team has 27 players, because the dataset player_features.csv, contains multiple players with the same name.

## Status

The current status is an error, and predictions were made based on the average skill of each team manually. 

