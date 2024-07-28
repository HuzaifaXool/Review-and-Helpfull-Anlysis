# Review-and-Helpfull-Anlysis
Reviews Analysis Project

This project involves analyzing product reviews to extract insights on various aspects such as review length, review scores, helpfulness, and trends over time.

## Table of Contents
## Introduction
## Data Description
## Analyses

# Introduction
The aim of this project is to perform various analyses on product reviews to gain insights into the patterns and trends in the data. The analyses cover a wide range of questions, such as the distribution of review scores, the relationship between review length and score, and trends in review details over time.

# Data Description
The data used in this project includes the following key columns:

## Id: Unique identifier or s.no
## ProductId: Unique identifier for products
## UserId: Unique Identifier for user
## ProfileName: User Name 
## HelpfulnessNumerator: Number of users who found the review helpful
## HelpfulnessDenominator: Total number of users who rated the review's helpfulness
## Score: Rating given to the product
## Time: Date when the review was posted
## Summary: Summary of the Review
## ReviewText: Text of the review

# Analyses
Distribution of Review Scores
The distribution of review scores shows that the majority of reviews are positive, with a mean score of 4.18 and a median score of 5.

Helpfulness of Reviews
We analyzed the helpfulness numerator (number of helpful votes) and the helpfulness denominator (total votes) across reviews. The average helpfulness ratio (helpfulness numerator / helpfulness denominator) is approximately 78.26%.

Average Review Scores by Product
We calculated the average review scores for different products. Products with more reviews tend to have higher average scores, but the correlation is very weak (0.0046).

Correlation Between Review Length and Score
The correlation analysis between the length of the review text and the review score shows a weak negative correlation (-0.077), suggesting that longer reviews do not necessarily correlate with higher scores.

Review Counts by User
We grouped the reviews by UserId and calculated the number of reviews per user. This helps identify prolific reviewers.

High-Rated Reviews and Helpfulness
High-rated reviews (scores of 4 and 5) receive more helpfulness votes on average compared to lower-rated reviews. However, the trend is not strictly linear.

Reviews and Average Scores
There is a very weak positive correlation between the number of reviews a product has and its average score (correlation coefficient: 0.0046).

Review Length by Sentiment
Negative reviews (scores of 1 and 2) are generally longer on average (482.64 characters) compared to positive reviews (scores of 4 and 5, averaging 428.39 characters).

Review Scores and Helpfulness Ratios
We calculated the average review scores and helpfulness ratios for the top 10 products by the number of reviews. This helps understand how the perceived helpfulness of reviews varies across different products.

# Conclusion
The analyses reveal several interesting patterns in the review data:

Reviews are generally positive.
Negative reviews are often longer than positive reviews.
High-rated reviews tend to receive more helpfulness votes, but the relationship is not strong.
The average length of reviews has increased over time, suggesting that users are providing more detailed feedback.

# Requirements
Python 3.x
Pandas
NumPy
