# baseball_of_fame_predictions
Baseball analytics such as Sabermetrics play a key role and is widely used to predict a player’s performance, salaries. Such baseball analytics not only aids team managers to evaluate players for selection but also to help a player identify his strengths and areas of improvement. Moreover, such analytics helps the team general managers to decide whether a player deserves the salary he is being paid and evaluate whether he will be able to deliver the expected performance based on the results provided by analytical models.  Considering the widespread adoption of Analytics in baseball, I have decided to pursue my case on baseball analytics to predict whether a player will get inducted into hall of fame or not.
I approached the problem by identifying relevant data sets from the original Lahman dataset, joined the identified tables and followed SEMMA approach in the newly merged data set. Besides developing the models using Neural Networks, Decision Trees, Logistic Regression, etc., I also attempted Text Mining/Sentiment Analysis and Time Series Forecasting.
 
My business problem deals with predicting whether a player will be inducted into Hall Of Fame or not based on the player’s career accomplishments. For this case, I gathered data and the data dictionary from Lahman baseball database in CSV format.
http://www.seanlahman.com/baseball-archive/statistics/
Data Dictionary
https://en.wikipedia.org/wiki/Baseball_statistics

I had 26 .csv files in the original data set from which I identified 8 files which are relevant to finding solution for our problem statement. After identifying the 8 files, we joined those tables to obtain a unified data set. The integrated data set consists of 18590 players’ records from 1871 to 2014.

The merged file will have summarized player level baseball data with his batting, pitching, fielding, awards, appearances and salaries.
 
   Some tables had multi-valued attributes such as Awards for each player, where we had to decompose those values into multiple columns to get meaningful information that could be used in our prediction.
   
   
KEY RESULTS:

From my model results and further analysis using text mining, I could infer that our model does provide fairly accurate results. I considered the case of a single player Mike Piazza and performed sentiment analysis and text mining which confirmed our logistic model results of Mike being selected for Hall of Fame. However, in the interest of time, I could not perform sentiment analysis for all the players. I also attempted to perform Time series analysis to forecast the performance of Mike Piazza based on his pitching statistics.

NEXT STEPS:
1.            Perform Sentiment Analysis/Text Mining for all the players.
2.            Time Series Forecasting techniques other than Moving Averages to predict the player’s performance.
3.            Develop models to predict the below.
a)  Which School/College is most likely to produce good batters/pitchers?
b)  Which player will have the best batting/pitching statistics for the next season?
c)  Will a manager/player win an award or not? 
