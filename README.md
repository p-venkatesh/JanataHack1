# Problem Statement

The provided dataset summarizes a heterogeneous set of features about articles published by Mashable in a period of two years. These articles were published by Mashable (www.mashable.com) and their content as the rights to reproduce it belongs to them. Hence, this dataset does not share the original content but some statistics associated with it. The provided features were extracted as it is done with any NLP use case. The goal is to predict the news article's popularity as close as possible. The noise in the extracted features makes it difficult to just use the provided attributes and reach a good score. This dataset also provides huge scope to feature engineering




# Data ScreenShot

<img src="Screenshot 2020-08-10 at 12.21.24 PM.png">



# A Description of my Methodology


   ### Feature Engineering & Approach


1. All were converted to numeric.
2. PreProcessed all of the data.
3. Filled all of the Nan Values.
4. Understanding the Data using descriptive statistics.
5. All the categorical features were Encoded to the numeric.
6. Handling the outliers in the data.
7. Created two new features.
8. I have used XGBoost which it has gave me 99.86561, and Light GBM also given the same level of accuracy to me.


### Tools used


1. Python for programming.
2. sklearn and numpy libraries for methodology.
3. LightGBM and XGBoost for the final model.
4. matplotlib and seaborn was used for plotting and analyzing the data.


## Evaluation Metric
The evaluation metric for this competition is MAE.


# Competition Result


1. Rank: 31rd on public LB.

<img src = "Screenshot 2020-08-10 at 11.51.52 AM.png">


2. Rank: 31rd on private LB.

<img src = "Screenshot 2020-08-10 at 11.51.52 AM.png">


3. [Link to LeaderBoard](https://www.machinehack.com/hackathons/news_popularity_prediction_weekend_hackathon_14)
