# customer-analytics

# [Project 1: Scoring Exercise](https://sandrahong.github.io/customer-analytics/Scoring-Exercise.html)
## Overview
Lead scoring is a strategy that marketing and sales teams use to identify which prospects are most valuable to a company in their current sales funnel. In this example project, I leverage a logit model to score leads to help identify prospects who are more likely to convert. 

For each prospect, I calculate a score, the predicted response probability, predicted lift, and compare with the actual response to evaluate the accuracy of my model. Through this model, I improve average profit per name from -2 dollars to 0.26 dollars, and total profit per name from -600 dollars to 78 dollars.

<img src="https://github.com/sandrahong/customer-analytics/blob/master/images/expected-actual-results.png" width="550" height="400">


# [Project 2: Paid Search Ad Response](https://sandrahong.github.io/customer-analytics/Paid-Search-Ad-Response.html)

## Overview

For this example project, I investigated short-run and long-run response to paid search advertising.

To get the results, I generated linear, concave logarithmic, and concave quadratic regression models and tested the significance of each model. Drawing on the fitted models, I computed the advertising elasticity implied by each model using July’s monthly clicks and the saturation level for advertising spending. Results are reported in terms of daily advertising spending. 

## Data
Dataset from Google Adwords that includes total daily visitors to the shop and daily spend ($) on paid search. The dataset spans 66 days from May 1st, 2019.
