#Introduction
This project focuses on analysis of a football player dataset. The dataset used is sourced form the popular video game ‘FIFA 19’ which contains an extensive collection of data on various professional football players around the world.

Problem statement 1
We will be taking a look at the data and try to find the best players that money can buy you and some young prospects that you can invest in right away for a relatively small amount but who will go on to become superstars in the future. We will also try to construct the best possible team for specific formations of the game.

Data Source
Data source - https://www.kaggle.com/karangadiya/fifa19

The dataset is sourced from kaggle.com and has the data from the popular video game “FIFA 19”

The dataset contains informations of real life football players and their playing attributes.

Problem statement 2
The world of professional football picks up a frentic pace during the 2 transfer windows of the year where players are allowed to move between different clubs. Clubs are often required to pay a premium transfer fees to secure a player that fits their needs.

Owing to the disparity in the financial strength of the clubs and also the players’ desire to move to a bigger club, it is often seen that big clubs are able to poach away talent from the smaller clubs or even their rivals.

To make sure that the selling club gets their profit for the player that they are selling, it has become commonplace to insert ‘Release Clauses’ in player contracts.

Release clauses for a player specify a certain amount that the buying club will have to pay to the selling club if they are to buy that particular player. They give a player the peace of mind knowing that a bigger club can trigger the clause by payying the specified amount allowing the player to move, while at the same time the selling club can be assured that they will be getting their profit for the time and money invested in the player and will have the funds to reinvest in other players.

The amount specified on a Release clauses can vary on different variables such as the player’s ability, their percieved market value, their age etc. For example - If a player’s perceived market value is $10000000 and their age is 18, then it would make sense for the selling club to have the player on a 5 year contract and keep the amount on release clause above their market value so as to deter other clubs from poaching their talent. Often more than not, release clauses for top players are always higher than their market value. This of course can change as player’s market value keeps on fluctuating as per their performance on the pitch week in-week out while release clause amount stays the same for the length of the contract.

We will be using regression models to predict the players release clause values based on the predictor variables available in the dataset.

As release clause figures are often not disclosed to the public, a predictor model would help the club determine an actual realistic transfer sum they will have to pay to get a player.
