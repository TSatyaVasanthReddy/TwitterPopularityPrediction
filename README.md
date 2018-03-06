# TwitterPopularityPrediction
 Twitter, with its public discussion model, is a good platform to perform such analysis. With Twitter’s topic structure in mind, the problem can be stated as: knowing current (and previous) tweet activity for a hashtag, can we predict its tweet activity in the future? More specifically, can we predict if it will become more popular and if so by how much? In this project, we will try to formulate and solve an instance of such problems.

The available Twitter data is collected by querying popular hashtags related to the
2015 Super Bowl spanning a period starting from 2 weeks before the game to a week after
the game. We will use data from some of the related hashtags to train a regression model
and then use the model to make predictions for other hashtags. To train the model, we
need to prepare training sets out of the data, extract features for them, and then fit a
regression model on it. The regression model will try to fit a curve through observed
values of features and outcomes to create a predictor for new samples. Designing and
choosing good features is one of the most important steps in this process and is essential to
getting a more accurate system. There are examples of such analysis and useful features
in literature. 
