# Stock-Prediction-Using-Twitter-Sentiment-Analysis

In this project, we have applied sentiment analysis and two statistical machine learning
models, Random Forest and Support Vector Regression. These models are used to depict the
correlation between the tweets which are extracted from twitter and stock market movements of a
company. We have performed sentiment analysis of the twitter data based on a whole day as well
as based on an hourly basis to analyze the effect it has on stock market prediction. The models are
evaluated and compared using RMSE (root mean squared error) values.

An overview of the process flow of our project is as follows:
1. Data Collection & Parsing: The stock market data is collected using yfinance API and
tweets are fetched from twitter using GetOldTweets API. In this step the preprocessing of
the tweets such as removing stop words, hyperlink and other steps are carried out.
2. Sentiment Analysis: The sentiment analysis of the tweet is carried out using VADER. Here
each tweet is given a sentiment score which determines if the tweet is positive, negative or
neutral.
3. Processing: The rows which have missing values such as price values are further processed.
The data along with the sentiment scores is divided into train and test data and is fed to the
model.
4. Applying Regression Models: To predict stock Market prices, we have used Random
Forest and Support vector regression models in this project. We will be then using RMSE
scores to validate the efficiency of our models and to analyze which model works better
for the used dataset.

