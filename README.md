# Recipe Rating

## Overview

This repository was part of the Recipe Ratings Prediction Challenge, a competition aimed at predicting users' ratings of recipes. Participants were provided with a dataset that included recipe names, user reviews, and other relevant attributes. The goal was to build predictive models capable of accurately forecasting the ratings each recipe received, transforming raw culinary data into actionable insights.

## Dataset Overview

- RecipeNumber: Placement of the recipe on the top 100 recipes list
- RecipeCode: Unique ID of the recipe used by the site
- RecipeName: Name of the recipe the comment was posted on
- CommentID: Unique ID of the comment
- UserID: Unique ID of the user who left the comment
- UserName: Name of the user
- UserReputation: Internal score of the site, roughly quantifying the past behavior of the user
- CreationTimestamp: Time at which the comment was posted as a Unix timestamp
- ReplyCount: Number of replies to the comment
- ThumbsUpCount: Number of up-votes the comment has received
- ThumbsDownCount: Number of down-votes the comment has received
- Rating: The score on a 1 to 5 scale that the user gave to the recipe. A score of 0 means that no score was given (Target Variable)
- BestScore: Score of the comment, likely used by the site to help determine the order comments appear in
- Recipe_Review: Text content of the comment
