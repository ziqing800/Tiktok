# Tiktok Data Analysis project 
This project is part of the data project practices of the Google Advanced Data Analytics course 

## Overview
This project aims to build a logistic regression to predict the user's verification status. This project utilized the dataset provided by Tiktok companies and the dataset is used to identify variables associated with the user's verification status and understand how video characteristics relate to whether a user is verified. The final logistic model performed with a precision score of 61%, a recall score of 85%, and an accuracy of 66% in determining which features were most important in determining the user's verification status. 

## Business understanding 
With the number of submissions and interactions on TikTok each day, it is a challenge for TikTok's moderators to review each video, user comment, and other video characteristics in a timely manner. Therefore, it is important to build a machine learning model with the capability to reliably classify user interaction data as a verified account or not for TikTok to be able to classify users effectively.\

## Data Understanding 
The dataset consisted of 19382 unique video data and 12 features. The features included information on video duration, view count, like count, comment count, share count, and comment count. The pie chart below shows a breakdown of the number of verified users versus unverified users that exist in the dataset. Approximately 93.6% of the users are verified and 6.4% of the users are not verified.

## Modelling and Evaluation
A hypothesis testing was first conducted to determine whether there is a statistically significant difference in the average view counts between videos from verified accounts and videos from unverified accounts. Results of the testing suggest that there is a statistically significant difference and hence there might be fundamental behavioral differences between these two groups of accounts.

<img width="468" alt="image" src="https://github.com/user-attachments/assets/c2f9c66d-c84d-4bdd-9405-e489305018d2">

The heatmap below shows the correlation between variables to help in determining which features to involve in building the model. A logistic regression model was then built to determine which variables to choose in predicting the user's verification status. The overall model performed with 61% precision, 85% recall, and 66% accuracy.

<img width="501" alt="image" src="https://github.com/user-attachments/assets/db313f44-92ca-4c30-9de4-e80d7780582c">


## Conclusion 
This model can benefit TikTok company in determining whether this user should be verified or not. Providing more information on video characteristics may be beneficial in helping to address the business problem.







