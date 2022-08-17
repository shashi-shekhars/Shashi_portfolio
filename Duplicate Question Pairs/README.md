# [Project 2 : Duplicate Question Pairs](https://github.com/shashi-shekhars/shashi_portfolio/tree/main/Duplicate%20Question%20Pairs)

## Project Overview
Social media platforms like Quora, Reddit etc are places to gain and share knowledge—about anything. These platforms connect users across the globe to ask questions and connect with people who contribute unique insights and quality answers. This empowers people to learn from each other and to better understand the world.

Over 100 million people visit Quora every month, so it's no surprise that many people ask similarly worded questions. Multiple questions with the same intent can cause seekers to spend more time finding the best answer to their question, and make writers feel they need to answer multiple versions of the same question. Quora values canonical questions because they provide a better experience to active seekers and writers, and offer more value to both of these groups in the long term.

## Problem Statement
• Identify which questions asked on Quora are duplicates of questions that have already been asked.
<br/>• This could be useful to instantly provide answers to questions that have already been answered.
<br/>• We are tasked with predicting whether a pair of questions are duplicates or not.

## Constraints
• The cost of a mis-classification can be very high.
<br/>• We would want a probability of a pair of questions to be duplicates so that we can choose any threshold of choice.
<br/>• No strict latency concerns.
<br/>• Interpretability is partially important.

## Resources Used
• Python Version: 3.9.7 
<br/>• Packages : pandas, numpy, os, matplotlib, seaborn, distance, wordcloud, sklearn, xgboost, bs4, nltk 
<br/>• Algorithms : Random Forest Classifier, XGBoost Classifier

![](https://github.com/shashi-shekhars/shashi_portfolio/blob/main/Images/word_share.png)
![](https://github.com/shashi-shekhars/shashi_portfolio/blob/main/Images/word_cloud_d.png)
![](https://github.com/shashi-shekhars/shashi_portfolio/blob/main/Images/bivariate_analysis.png)
![](https://github.com/shashi-shekhars/shashi_portfolio/blob/main/Images/2D_t-SNE.png)
