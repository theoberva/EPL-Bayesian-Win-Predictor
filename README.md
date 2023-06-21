# Bayesian Analysis of English Premier League Performance

This project aims to predict outcomes in the English Premier League (EPL) using historical data of team performance. The approach adopted in this project involves the use of Bayesian statistics to adjust win percentages and estimate a "true" win percentage.

## Project Overview

The project involves several steps, including:

1. **Calculation of Cumulative Wins Percentage:** The cumulative win percentage is calculated for each team. This involves grouping by team and calculating the cumulative sum of win percentages, wins, and games. A running average is also calculated for each team to track their performance over time.

2. **Estimating True Win Percentage:** We estimate the true win percentage for each team using the beta distribution, which is used to model continuous random variables whose range is between 0 and 1. This process includes calculating the mean and standard deviation of the population, and estimating the beta parameters (alpha and beta).

3. **Creating a Bayesian Adjustment:** To adjust for the inherent uncertainty in the calculated win percentage, we perform a Bayesian adjustment. This involves adding our estimated alpha and beta to the cumulative wins and games, respectively, to calculate an adjusted win percentage.
