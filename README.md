# Trending YouTube Video Statistics
This project is based on dataset for recording daily record of the top-trending YouTube videos, which is aiming to perform analysis, visualization, prediction and recommendation.
Based on the results, we could plan to be extracted about personal preferences of users from all over the world in this dataset, which will contribute to the training of several prediction models.
### Objectives
According to the conclusions of the analysis, several features are planned to be extracted about personal preferences of users from all over the world in this dataset, which will contribute to the training of several prediction models. The functionalities are as follows:
1. For a user, three possibilities of favorite kinds of video would be predicted according to the behaviors of other users who share the similar attributes among the dataset (e.g. residence in the same region, similar watching history, similar subscribing video channels, etc.).
2. For a video to be published or just published, the number of comments and likes for it would be predicted, as well as the attitudes of most comments according to its details, tags and the quality of content.
3. Even taking the stand of YouTube the company, a model would be established for recommendation of specific kinds of video towards the specific kinds of users (e.g.
2
region, age group, kind of business, etc.).
### Methodology
In order to achieve this project goals, obtain reliable conclusions and offering scientific recommendation, data science applications, programming tools and algorithms are significant necessary to our methodology. The following is the detailed method list to be shown in this project:
⚫ Programming language: Python
⚫ Basic tools: NumPy, pandas, seaborn, matplotlib, json, datetime, IPython, glob
⚫ Machine Learning tools: train_test_split, LinearRegression, PolynomialFeatures, r2_scores，，Polynomial Regression, Random Forest, K-means Cluster
⚫ Advanced Tools: nltk, WordCloud, spacy, TextBlob
⚫ Algorithm:
Machine Learning (Linear Regression, Polynomial Regression, Random Forest, K-fold training, K-means Cluster,r2_score)
Natural Language Processing:(Word frequency statistic, Sentiment recognition)
### Method Solving
Based on the data science methods, here are the specific ways to implement methodology and get analytical results:
⚫ Using pandas, NumPy and matplotlib processed a general visualization of data: e.g. The most influential video publisher; diverse topics; the videos with the most dislikes; the distribution of LIKES & DISLIKES and so on.
⚫ Using IPython and glob to display a Html-source dataset (photo grids).
⚫ After getting a view of dislikes, likes, comment-counts, and views, getting correlations and heatmap for the modified dataset. This relationship would be used in latter prediction model, by using Polynomial Regression and R2 score for evaluation.
⚫ Using wordcloud to count the frequency of words in description, tags, and title.
3
⚫ Using nltk to analyze the sentiments of words and getting a view of it.
### Task Description
Main tasks need to be identified to support the completion of this project and accuracy of the results. Several basic steps are listed below to guarantee our progress:
⚫ Distribution of attributes
⚫ Correlation between Views & Likes
⚫ Prediction about number of Likes
⚫ Recommendation system
⚫ Comment sentiment recognition