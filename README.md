# Data Science Individual Project

## Introduction
I am very passionate about baseball and enjoy both watching and playing the sport. Because of my love for the game, I have been very invested in the MLB for some time. Statistics are an extremely important part of the game and can be very telling about a player or team's performance in certain areas, and statistics are oftenused to determine what needs to be focused on, whether it is for self-improvement or to take advantage of another team's weakness. The objective of this project is to determine what baseball statistics help lead MLB teams to more wins in a season. The statistics will focus on statistics as a team rather than individual players.

Topic questions:
- How does a team's left on-base (LOB) statistic correlate with the number of wins they achieve in a season?
- Does a team's earned run average (ERA) or its Defensive Efficiency Rating (DefEff) have a stronger correlation with the number of losses in a season?
- Does a higher team slugging percentage (SLG) or a higher team batting average (BA) have a stronger correlation with the number of wins in a season?

## Selection of Data
The model processing and training are conducted using Google Colab.

### Sources of Data
https://www.baseball-reference.com/
Baseball-Reference is a very popular baseball statistics website. It contains all standard statistics for every team and player throughout MLB history. The extensive data provided by this site can be cleaned to extract the specific metrics needed to answer the research questions.

https://www.teamrankings.com/
Used specifically to get the LOB metrics for the first research question.

## Methods
- NumPy and Pandas for data analysis and inference
- GitHub for development and hosting/version control
- Colab as IDE

## Results
Research Question 1: How does a team's left on-base (LOB) statistic correlate with the number of wins they achieve in a season?
  Based on the findings of comparing each MLB team's LOB statistics and their wins in a season, it can be determined that the LOB statistic does not matter much when it comes to winning games. In the graph it can be seen that the Baltimore Orioles, the team with the second most amount of wins in the 2023 season, and the Oakland Athletics, the worst team in the league for that year, have the same LOB average at 6.44, so it seems like other statistics are much more meaningful when it comes to winning games.

Research Question 2: Does a team's earned run average (ERA) or its Defensive Efficiency Rating (DefEff) have a stronger correlation with the number of losses in a season?
  After comparing both ERA vs. wins and DefEff vs. wins for the 2023 season, it can be seen that ERA is much a much more important statistic for teams to win games. Teams that won the most amount of games in 2023 generally have the lowest ERAs (having a lower ERA is better than a higher one) whereas the DeffEff graph is much more scattered, with the team with the most amount of wins in 2023 having a below-average DeffEff.

## Discussion
What might the answer imply and why does it matter? How does it fit in with what other researchers have found? What are the perspectives for future research?

## Summary
