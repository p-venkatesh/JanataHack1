# Problem Statement

An automobile company has plans to enter new markets with their existing products (P1, P2, P3, P4 and P5). After intensive market research, they’ve deduced that the behavior of new market is similar to their existing market. 

In their existing market, the sales team has classified all customers into 4 segments (A, B, C, D ). Then, they performed segmented outreach and communication for different segment of customers. This strategy has work exceptionally well for them. They plan to use the same strategy on new markets and have identified 2627 new potential customers. 

You are required to help the manager to predict the right group of the new customers.



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
The evaluation metric for this competition is Accuracy Score.


# Competition Result


1. Rank: 110th on public LB.

<img src = "Screenshot 2020-08-10 at 12.19.07 PM.png">


2. Rank: 110th on private LB.

<img src = "Screenshot 2020-08-10 at 12.19.07 PM.png
">


3. [Link to LeaderBoard](https://datahack.analyticsvidhya.com/contest/janatahack-customer-segmentation/#LeaderBoard)
