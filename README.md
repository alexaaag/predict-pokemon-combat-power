# Predicting Pokemon Combat Power

This is a class project for MATH158 Statistical Linear Models at Pomona College.

In this project we experimented with different linear models to predict a pokemon's combat power after evolution based on their previous combat features.

You can read our progress throughout the semester under the folder "Progress Report"
* part I: Exploratory analysis
* part II: Simple Linear Regression
* part III: Multiple Linear Regression
* Final: Ridge, LASSO, Principal Component Analysis and Summary Graph. 

** Read the exploratory analysis and the final write-up for a high level analysis and really cool visualizations :) **

---
### Background and Data Description
In July 2016, Pokemon Go became an overnight sensation with hundreds of millions of people downloading the mobile game. For most players, this game represents a nice coffee break. However, for more serious players, the objective is to try to obtain the strongest Pokemon possible available, which is indicated by the highest combat power, abbreviated cp, so that you can battle other players' pokemon and win. Usually players can catch weaker forms of Pokemon that, through training, can evolve into stronger forms, so an evolved Pokemon will generally always have a higher cp than a non-evolved Pokemon. In the search for the strongest Pokemon, players have wished to determine what characteristics would indicate that the pokemon they have is stronger relative to other players' pokemon. For instance, if a player had pokemon X and trained it to its maximum potential but pokemon X was still weaker than pokemon Y, the player would want to know why pokemon Y was still stronger. A number of people have tried to generate models in an attempt to predict the best way to maximize cp for their Pokemon. This is what we will attempt to do ourselves: create a model to predict combat power for an evolved Pokemon. 

The dataset we are using to build our model is an original data set collected by OpenIntro. The dataset contains 75 observations across 26 variables, with each observation representing a randomly generated Pokemon that the gamer caught. Four species are represented in this data, so the conclusions drawn from this modeling process can only be inferred onto the population of these 4 particular species: Eevee, Pidgey, Caterpie, and Weedle. 
