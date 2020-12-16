# ADS Project 5: 

Term: Fall 2020

+ Team # 2
+ Projec title: Relationship between Trump's Tweets and stock returns 
+ Team members
	+ Elise Nguyen
	+ Natalie Williams
	+ Yue Liang 
	+ Luyao Sun 
+ Project summary: Used two LSTM models (sklearn LSTM and TextBlob), to classify the sentiment of Donald Trump's tweets during the peak of the trade war (January 2018- December 2019). We filtered his tweets for content related to the trade war, then regressed the polarity of his tweets against the Shanghai Stock Exchange, and the ETF's FXI and S&P 500 which track the largest companies in China and US respectively. First, we used intra-day 30 minute intervals from the stock exchanges and regressed this against Trump's tweets thoughout the day. These results proved poor, so we changed our approach and aggregated the sentiment of Trump's trade war related tweets into two sections: while the stock market was open and closed (time zones were accounted for). This yielded better results, with a Point-biserial correlation coefficient of 0.XX for sklearn LSTM and 0.XX for TextBlob LSTM. After this regression, we decided to randomly sample and check the results of the Sentiment Analysis. We found that, the LSTM and TextBlob results greatly differed from the team member's personal evaluations. Sklearn's LSTM agreed with team members evaluates 46% of the time, whereas, Textblob had a 59% similarity. Due to this, our recommendation to improve on this work would be to refine the NLP models and try to imbude context into the Sentiment Analysis. 
	
**Contribution statement**: 
	+ Elise Nguyen
	
	+ Natalie Williams made the preliminary Sentiment Analysis model to determine the feasibility of the project. She acquired the data sets that would be used for training and testing the LSTM Natural Language Processing Models. She implemented two different LSTM's models (balanced and unbalanced) and balanced the highly imbalanced dataset that would serve as the model training data. She also assisted with preparing the presentation files. 
	
	+ Yue Liang 
	+ Luyao Sun 

Following [suggestions](http://nicercode.github.io/blog/2013-04-05-projects/) by [RICH FITZJOHN](http://nicercode.github.io/about/#Team) (@richfitz). This folder is orgarnized as follows.

```
proj/
├── lib/
├── data/
├── doc/
├── figs/
└── output/
```

Please see each subfolder for a README file.
