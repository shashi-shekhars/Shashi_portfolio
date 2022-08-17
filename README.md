# [Project 1 : Customer Analysis in Retail Business](https://github.com/shashi-shekhars/shashi_portfolio/tree/main/Customer%20Analysis)

# Project Overview
This project aims to support a retail or FMCG (fast-moving consumer goods) company to formulate marketing and pricing strategies that could maximize revenues on each brand of a product. To reach the fullest potential of bringing up revenues, a company should find a good spot for price to maximize customer behaviours namely purchase probability, brand choice probability, and purchase quantity.

Data from customer purchase history were used for training the regression models to predict those three customer behaviours in a preconceived price range. The results were then converted into price elasticities so that we can examine the effects of changing price on each of the behaviours. Hence, they will be able to find the suitable marketing and pricing strategies.

To better position the products, we will firstly perform segmentation on our customers to support our analysis on customer behaviours, allowing us to customize marketing strategies for customers with different backgrounds.

## Resources Used
• Python Version: 3.9.7
<br/>• Packages: pandas, numpy, sklearn, scipy, matplotlib, seaborn, pickle
<br/>• Algorithms: Clustering(Hierarchical,K-means, PCA), Regression(logistic, linear)

![](https://github.com/shashi-shekhars/shashi_portfolio/blob/main/Images/seg_features_correlation.png)
![](https://github.com/shashi-shekhars/shashi_portfolio/blob/main/Images/K-means_pca.png)
![](https://github.com/shashi-shekhars/shashi_portfolio/blob/main/Images/average_pur_seg.png)
![](https://github.com/shashi-shekhars/shashi_portfolio/blob/main/Images/brand_5.png)

# [Project 2 : Duplicate Question Pairs](https://github.com/shashi-shekhars/shashi_portfolio/tree/main/Duplicate%20Question%20Pairs)

## Project Overview
Social media platforms like Quora, Reddit etc are places to gain and share knowledge—about anything. These platforms connect users across the globe to ask questions and connect with people who contribute unique insights and quality answers. This empowers people to learn from each other and to better understand the world.

Over 100 million people visit these sites every month, so it's no surprise that many people ask similarly worded questions. Multiple questions with the same intent can cause seekers to spend more time finding the best answer to their question, and make writers feel they need to answer multiple versions of the same question. Quora values canonical questions because they provide a better experience to active seekers and writers, and offer more value to both of these groups in the long term.

## Problem Statement
• Identify which questions asked on these sites are duplicates of questions that have already been asked.
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

# [Project 3 : Non invasive measurement of human physiological parameters](https://github.com/shashi-shekhars/Shashi_portfolio/tree/main/(ANN)%20Non-Invasive)

## Project Overview
The main objective of this project is to design a non-invasive method based device to monitor blood glucose measurement which is utilising the near-infrared region. There are some devices that are based on various non-invasive techniques but this project proposed a device based on artificial neural network for regression analysis to predict the blood glucose levels, which is absent from any other such device.

## Resources Used
• Softwares : MATLAB 2018a, NI Multisim
<br/>• Packages : NNTool, Artificial Neural Network
<br/>• Algorithm : Regression based Levenberg-Marquardt algorithm

![](https://github.com/shashi-shekhars/shashi_portfolio/blob/main/Images/sensor_simu.png)
![](https://github.com/shashi-shekhars/shashi_portfolio/blob/main/Images/Regression.png)

