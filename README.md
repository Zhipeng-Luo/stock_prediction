# Sentiment Analysis and Stock Prediction

## Background

This is a team project we do for the course MADS694/695 for the Master of Applied Data Science Program in University of Michigan - Ann Arbor. 

**Team Member**
- Zhipeng Luo (brianluo@umich.edu)
- Chihshen Hsu (cshsu@umich.edu)
- Qi Zhang (qizhan@umich.edu)

Our team select the topic **Sentiment Analysis and Stock Prediction** as the project of the course MADS694/695 - MileStone2. The reason we choose this topic is that the debate about whether stock movement can be predicted or not has been existing for a long time. We explore the topic and understand further about deep learning model architecture for time-series data prediction. In addition, we are so interested in sentiment analysis for the news and its impact for stock movement prediction.

In this project, we target to explore stock prediction in three aspects, including price movement direction, close price value and stock volatility. The models we tried includes Logistic Regression, SVM, Random Forest, LSTM, BiLSTM, ARIMA. 



## Data Source

- The financial data is collected by [yfinance API](https://pypi.org/project/yfinance/)).
- The news data is collected by the library [finpie](https://github.com/peterlacour/finpie)
 
## Conclusion

- Stock market volatility is more predictable than stock price or price movement direction.
- By combining emotional data, it is surprised that the volatility prediction performance by BiLSTM improved a lot and binary classification by LSTM improved 4%, while no impact for Logistic Regression, SVM or Random Forest model. 

## Ethical Statement

Stock market prices are highly unpredictable and volatile. This means that there are no consistent patterns in the data that allow you to model stock prices over time near-perfectly. The predictive models are statistical in nature. It doesn’t provide any guarantees. In the unsupervised machine learning section, we find that the semantic approach is effective for analyzing volatility, but this does not mean that it works for all other stocks, nor does it mean that it will guide stock investment. All the studies models here can’t be used blindly without any human-in-the-loop for stock exchange or other investment.
