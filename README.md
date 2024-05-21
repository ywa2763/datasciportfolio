# Yifei Wang's Data Science Portfolio
Welcome to my data science portfolio. Here, you will find a compilation of my work in various areas of data science, including code notebooks, slide decks, and reports. Each section is dedicated to a specific type of problem or analysis. Click on the links to explore my projects in detail.

 <br />

 ## Table of Contents
 1. [This is the link text](##Paramount-Practicum-Project-Showcase)
 
## Paramount Practicum Project Showcase 
**Description**: The practicum project for Paramount involved developing a systematic method to detect consistent interactions between shows to inform content exploitation decisions. The objective was to help inform decisions evolved around enhancing user engagement.

**Tools Used**: Python (for data processing and analysis), R (for network analysis), igraph (for network graph visualization)

**Techniques**: Anomaly detection (LOESS curve fitting, Facebook Prophet, z-score, seasonal decomposition), trend removal, similarity metric calculation (Jaccard similarity, KS statistic, slope of cumulative curve), clustering

**Presentation**: [Paramount Project Showcase Slide Deck](https://github.com/ywa2763/datasciportfolio/blob/4aba8f1c5a33138c0c606dd5c89416c366753434/Slides%20and%20Reports/Paramount%20Practicum%20Showcase.pdf)

 <br />
 
## Classification Problem
### Customer Characteristics Analysis
**Description**: This project focuses on analyzing customer characteristics to identify those most likely to respond to targeted marketing campaigns. The goal is to maximize the return on investment (ROI) by accurately targeting the right customers.

**Tools Used**: Python, scikit-learn (for machine learning models), pandas (for data manipulation), matplotlib (for data visualization)

**Techniques**: Decision trees, k-nearest neighbors (k-NN), logistic regression, SMOTE (Synthetic Minority Oversampling Technique) for handling class imbalance

**Presentation**: [Customer Characteristics Analysis Slide Deck](https://github.com/ywa2763/datasciportfolio/blob/24ccf3c99ee53f283cd0caf0b0f1dfe67b55bce6/Slides%20and%20Reports/Customer%20Characteristics%20Analysis%20Slide%20Deck.pdf)

**Code Notebook**: [Customer Characteristics Analysis Code Notebook](https://github.com/ywa2763/datasciportfolio/blob/24ccf3c99ee53f283cd0caf0b0f1dfe67b55bce6/Code%20Notebooks/Customer%20Characteristics%20Analysis%20Code.ipynb)

<br />
  
### Predicting Customer Churn
**Description**: This project addresses the issue of customer churn for a telecommunications company experiencing a loss of landline customers to cable competitors. The project involves two main tasks: 1) inference, understanding what kind of customers are churning, and 2) prediction, developing a predictive model with high accuracy to forecast customer churn.

**Tools Used**: R(caret, ModelMetrics, pROC, keras, tensorflow, dplyr, ggplot2, xgboost, glmnet, ISLR, gbm)

**Techniques**: Logistic regression, feature selection, neural networks, random forest, XGBoost, Adaboost

**Presentation**: [Predicting Customer Churn Slide Deck](https://github.com/ywa2763/datasciportfolio/blob/24ccf3c99ee53f283cd0caf0b0f1dfe67b55bce6/Slides%20and%20Reports/Predicting%20Customer%20Churn%20Slide%20Deck.pdf)

**Code Notebook**: [Predicting Customer Churn Code Notebook](https://github.com/ywa2763/datasciportfolio/blob/1afe7afa7dec97bd29fe871a526af82b0397e84b/Code%20Notebooks/Customer%20Characteristics%20Analysis%20Code.ipynb)

 <br />
 
## Recommender System
### Supermarket Generalized Beer Recommendation
**Description**: This project involved developing a recommender system for ACSE Supermarket to increase sales of Molson Coors products by targeting Budweiser customers. The system utilized transaction data to cluster customers based on their purchasing patterns and employed logistic regression models to predict the likelihood of customers switching to Molson Coors products.

**Tools Used**: Google BigQuery (for retrieving over 1 billion rows of data), Python, scikit-learn (for clustering and logistic regression), pandas (for data manipulation and preparation),  matplotlib/seaborn (for data visualization)

**Techniques**: K-means clustering, logistic regression, association rule mining (Apriori algorithm)

**Key Insights**: Identified 42,000 potential customers for Molson Coors with tailored recommendations to support targeted marketing strategies. Association rules revealed key sub-categories influencing beer purchases, which can inform business decisions.

**Report**: [Supermarket Generalized Beer Recommendation Report](https://github.com/ywa2763/datasciportfolio/blob/faf8e99e7f5c73f85cc0d1f1c77a0e69555d68a1/Slides%20and%20Reports/Supermarket%20Generalized%20Beer%20Recommendation%20Report.pdf)

 <br />
 
## Natural Language Processing
### Amazon Reviews Analysis
**Description**: This project analyzes 5.5 million Amazon reviews in the beauty category from 2000 to 2015 to identify trends and make recommendations for improving the user experience and optimizing product offerings for sellers. The goal is to advise Amazon on the types of reviews that customers find most useful and guide sellers on key topics that influence consumer behavior.

**Tools Used**: PySpark (for data processing, topic modeling, and sentiment analysis), AWS S3 and HDFS (for data storage and processing), Natural Language Toolkit NLTK (for text processing), Gensim (for topic modeling)

**Techniques**: Data wrangling, big data processing, topic modeling, sentiment analysis

**Key Insights**: Reviews participating in the Vine program were more helpful; non-verified purchases often had lower ratings but higher helpful ratios. Topic modeling revealed common themes such as product longevity, effectiveness, and value, with hair and skin products being particularly popular in the beauty industry. It is suggested to send post-purchase reminders for better consumer insights and focus on improving aspects highlighted in lower-rated reviews to enhance customer satisfaction.

**Presentation**: [Amazon Reviews Analysis Report](https://github.com/ywa2763/datasciportfolio/blob/9afe7ba3571fd44220b56f66da78b69b2eb25430/Slides%20and%20Reports/Amazon%20Reviews%20Analysis%20Report.pdf)

**Presentation Video**: [Amazon Reviews Analysis Presentation Video](https://youtu.be/6CKByXDGcu4) 


 <br />
 
## Prescriptive (Optimization) Analytics
### Linear Programming Optimization for Crispy Critters
**Description**: The objective of this project is to optimize the production process for Crispy Critters using linear programming techniques. The goal is to maximize profit while considering constraints such as resource availability, production capacity, and market demand.

**Tools Used**: Python, Gurobi, Pandas

**Techniques**: Linear programming formulation, optimization, sensitivity analysis

**Key Insights**: Determination of the optimal mix of products to maximize profit given the constraints, insights into how resources are allocated in the identified optimal solution, identification of bottlenecks, and analysis of how changes in market demand affect the production plan and overall profitability.

**Presentation**: [Linear Programming Optimization for Crispy Critters Slide Deck](https://github.com/ywa2763/datasciportfolio/blob/6f5c703d463bc359d6fa62eb3c56766e247cce6d/Slides%20and%20Reports/Linear%20Programming%20Optimization%20for%20Crispy%20Critters%20Slide%20Deck.pdf)

**Code Notebook**: [Linear Programming Optimization for Crispy Critters Code Notebook](https://github.com/ywa2763/datasciportfolio/blob/6f5c703d463bc359d6fa62eb3c56766e247cce6d/Code%20Notebooks/Linear%20Programming%20Optimization%20for%20Crispy%20Critters%20Code%20Notebook.ipynb)

 <br />
 
### Simulation Optimization for Regency Bank
**Description**: This project involves optimizing the migration strategy for Regency Bank's newly acquired client portfolio from Continental Bank. By using simulation and optimization techniques, the project aims to determine the best policies for migrating clients based on their risk, complexity, and annual spend to maximize net profits over a three-year period.

**Tools Used**: Python, NumPy, Pandas

**Techniques**: Simulation modeling, Monte Carlo simulation, optimization

**Key Insights**: Determination of optimal migration strategy (significantly increases profits compared to migrating all clients or using simpler risk-only criteria) and risk management.

**Presentation**: [Simulation Optimization for Regency Bank Slide Deck](https://github.com/ywa2763/datasciportfolio/blob/6f5c703d463bc359d6fa62eb3c56766e247cce6d/Slides%20and%20Reports/Simulation%20Optimization%20for%20Regency%20Bank%20Slide%20Deck.pdf)

**Code Notebook**: [Simulation Optimization for Regency Bank Code Notebook](https://github.com/ywa2763/datasciportfolio/blob/6f5c703d463bc359d6fa62eb3c56766e247cce6d/Code%20Notebooks/Simulation%20Optimization%20for%20Regency%20Bank%20Code%20Notebook.ipynb)

 <br />

## Network Analytics
### Twitch Network Analysis
**Description**: This project analyzes the network of English-speaking Twitch streamers to understand user connectivity, identify key influencers, and predict potential new connections. The analysis focuses on both the network structure and individual streamer characteristics to provide insights for improving user engagement and retention.

**Tools Used**: R, igraph, mclust, ergm, ggplot2

**Techniques**: Network analysis, centrality measures, clustering, link prediction

**Key Insights**: The Twitch streamer network is generally sparse, with a subset of highly interconnected streamers forming a core group. High closeness centrality streamers tend to form tight-knit communities, while high betweenness centrality streamers act as bridges across the network. Streamers using explicit language and those in the Twitch Partner Program are more likely to form new connections, particularly as initiators of ties.

**Report**: [Twitch Network Analysis Report](https://github.com/ywa2763/datasciportfolio/blob/7d9b284309941fe0cb6655052189d0345ced53be/Slides%20and%20Reports/Twitch%20Network%20Analysis%20Report.pdf)

**Code Notebook**: [Twitch Network Analysis Code Notebook](https://github.com/ywa2763/datasciportfolio/blob/edb40bf6519b182dc4bc0adab905052464fa345a/Code%20Notebooks/Twitch%20Network%20Analysis%20Code.Rmd)

<br />

## Data Visualization
### Global Food Demand and Production Dashboard
**Description**: This project explores global food demand and production trends to understand how to feed the world today. It uses data visualization techniques to analyze and display trends across regions and food categories, addressing key questions about market size, distribution, and production contributors.

**Tools Used**: R(caret, dplyr, ggplot2), Tableau

**Techniques**: Data cleaning, data preprocessing, EDA, data visualization (tree map, stacked bar chart, choropleth, etc.), dashboard creation

**Presentation**: [Global Food Demand and Production Slide Deck](https://github.com/ywa2763/datasciportfolio/blob/8ac8e8a79d15ce0b3fccdcd56524d0094f78bae8/Slides%20and%20Reports/Global%20Food%20Demand%20and%20Production%20Slide%20Deck.pdf)

**Tableau Dashboard**: [Global Food Demand and Production Dashboard](https://public.tableau.com/app/profile/yifei.wang7456/viz/GlobalFoodDemandsandProduction/MarketDashboard)
