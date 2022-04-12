# customer-analytics

# [Project 1: Measuring the Effect of Online Advertising](https://sandrahong.github.io/customer-analytics/Measuring-Online-Ads.html)
## Overview

The primary objective of the campaign is to target half a million online consumers with ads for a company's new product. The campaign must result in positive ROI to justify spend of advertising dollars.

## Experimental Design
To measure the effectiveness of the ads, a control group can be created and shown a public service announcement (PSA) instead of the ad, in the exact same size and position on the page. By randomly selecting which user is in the control group and which users are exposed to the real ad, the extent to which the advertising makes a difference can be measured.

## Results

* **Effectivness of ad campaign**: Based on the experiment and analysis, ad campaign has a positive effect on conversion rate. The ROI is 37.73%.    

* **Validity of experiment results**: The control and treatment groups is not statistically different - they have similar amount on average impressions per person. There was an opportunity cost to running the experiment, but now with the statistically significant results, they can move forward with the ad.

* **Other insights**: 
    + Advertising on Tuesday is more effective than other days.   
    + Customers are more responsive to the ads during 5-6 pm, 2 pm, and 8 pm-1 am. To maximize effectiveness, distribute more of marketing budget on those times of the day.  
    + Until further analysis on the group with over 200 impressions, it's best to stop advertising to this group because it's ineffective and the group does not respond well to the ads.  


# [Project 2: Scoring Exercise](https://sandrahong.github.io/customer-analytics/Scoring-Exercise.html)
## Overview
Lead scoring is a strategy that marketing and sales teams use to identify which prospects are most valuable to a company in their current sales funnel. In this example project, I leverage a logit model to score leads to help identify prospects who are more likely to convert. 

For each prospect, I calculate a score, the predicted response probability, predicted lift, and compare with the actual response to evaluate the accuracy of my model. Through this model, I improve average profit per name from -2 dollars to 0.26 dollars, and total profit per name from -600 dollars to 78 dollars.

<img src="https://github.com/sandrahong/customer-analytics/blob/master/images/expected-actual-results.png" width="550" height="400">


# [Project 3: Paid Search Ad Response](https://sandrahong.github.io/customer-analytics/Paid-Search-Ad-Response.html)

## Overview

For this example project, I investigated short-run and long-run response of clicks (i.e., visitors) to paid search advertising.

To get the results, I generated linear, concave logarithmic, and concave quadratic regression models and tested the significance of each model. Drawing on the fitted models, I computed the advertising elasticity implied by each model using July’s monthly clicks and the saturation level for advertising spending. Results are reported in terms of daily advertising spending. 

## Data
Dataset from Google Adwords that includes total daily visitors to the shop and daily spend ($) on paid search. The dataset spans 66 days from May 1st, 2019.
