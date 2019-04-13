# Readme

This is the work for our final paper for w266 Natural Language Process using Deep Learning.

Contributors:

Shahbakht Hamdani
Luis Villlarreal
Ashesh Choudhury

## Causal Analysis between Public and Market Sentiment: a Predictive Model for Individual Stock Performance.

In this paper, we tackle one of the most pursued task by hedge fund and asset managers: predicting stock prices. It's been long said by economists that markets are efficient and follow a random path, therefore undermining any possibility of prices being predictable. Prices, indeed, discount all the information available for a particular stock, or index in real-time, and after major financial data is available to the public, Stocks and Indices are fed by positive, neutral and negative sentiment creating this "random" fluctuation in price until a major announcement or, typically, the next earnings report creates a new trend.
Until recent years, this "sentiment" was un-quantifiable (Thank you Twitter!). Our approach takes on sentiment analysis on Twitter and apply Deep Learning principles to find a correlation with the Top 50 Stocks in Market Cap. We will analyze our results from a Neural Network fed with a lag in prices and a lag of sentiment scores from March 2019. Unlike Bollen et al's [1] paper, our work is applied directly to Stocks instead of Dow Jones Index. Apart from the predictive model, we will establish Granger-Causality and build a multivariate time-series regression equation between stock prices and sentiment scores.

[1] J. Bollen and H. Mao. Twitter mood as a stock market
predictor. IEEE Computer, 44(10):91–94.
