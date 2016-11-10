[![Screen Shot 2016-10-29 at 19.59.52.png](https://s13.postimg.org/dlz5er05z/Screen_Shot_2016_10_29_at_19_59_52.png)](https://postimg.org/image/jzo8i051v/)

SOMECODE is a research platform for serious observation and analysis of Twitter data. SOMECODE brings together 9 years of unbroken continuity in developing social media research tools. Previous tools and processes developed by the contributor team are in daily use by many FORTUNE100 companies and major advertising agencies. SOMECODE is the solution we always wanted to build, but due to the kinds of restraints commercial entities have, never got to. 


### BENEFITS

- Get started with serious social media research in minutes 
- Equal or better capabilities vs. best industrial solution
- Up to 10 million tweets per day with single API key
- Optmized for minimizing out-of-scope time use (configuration, data wranging, etc.) 
- Supports both streaming and rest API endpoints for both status (tweet) and user objects 
- Ideal environment for academic research and publication 

With one command from idea to looking at results of regression analysis, advanced plotting, sentiment analysis, etc. etc. 

SOMECODE is built by researchers for researchers and is very easy to extend / customize to suit specific needs. For most research scopes SOMECODE will work "out of the box". It has very few depedencies (below) and takes minutes to deploy for your first research project. 


### GETTING STARTED WITH SOMECODE IS EASY

##### LAPTOP OPTION: 

SOMECODE runs on any regular low-end laptop with a common web browser. Tested on Linux and Mac OS X. 

##### SERVER OPTION: 

SOMECODE runs on Amazon Nano (or similar) for $5 per month. Tested on Ubuntu 14.04LTS

For both options you can find a a script in the /setup folder that automate. the setup process. Setup scripts are named 'setup_mac.sh' and 'setup_ubuntu.sh' respectively. 


### KEY FEATURES 

Without increasing cognitive demand for the user, SOMECODE is rich with features: 

- End-to-end streaming analytics pipeline for Twitter data
- Detect spam accounts, bots and other unwanted tweets/users 
- Amazing plotting (using Seaborn library) 
- Export to SQL, CSV, HTML, PDF, LaTeX, reveal.js + other formats 
- Lightning fast math and word processing computations
 
 
### SOMECODE SCORING 
 
One of the advantages of SOMECODE is its scoring system. Scores are available at three levels: 

- tweet level scoring
- user level scoring
- network level scoring 

Tweet: 

- Quality
- Reach 
- Impact

User / Network: 

- Intensity
- Engagement
- Reach
- Influence 

The 'user level' scoring system takes in to notice the three lifestages of a Twitter account; creation, activity and response/engagement. For example the creation stage score analyse +10 signals created to profile creation. 
 
SOMECODE is very easy to customize / extend. Even if you are a beginner python learner. 


##### 100% fun, 0% mindless wrangling. 

Some of the things SOMECODE takes care for you: 

- data structures
- datatypes 
- character types
- system performance
- API rate-limit management 
- JSON parsing 
- pipeline process automation 
- plot configuration 
- exception handling


### WHAT IS SOMECODE MADE OF

Frankly speaking, SOMECODE would not be possible without all the amazing technology solutions it's based on. What SOMECODE does, is put a few key technologies together, with "business logic" that came from working on over a thousand social media research projects since 2005. 

First and foremost, Pandas, a python 'data framework' that was conceived in AQR Capital Management for the needs of quantitative finance. Below the full list of what you'll need to have. 

- Python (Anaconda distribution is a plus for many reasons) 
- Pandas 
- Numpy
- Matplotlib / Seaborn                                                                                                                                                                                                                                                                                              
- Tweepy

With Anaconda, only Tweepy and Seaborn needs to be installed: 

    pip install tweepy 
    pip install seaborn

Other than that, dependent on the system, you should have minimal dependencies to worry about. Also if you're not using it already, I highly recommend Jupyter (http://jupyter.org/). It helps make programming much more about fun, and less about frustration. 


### BRIEF BACKGROUND TO SERIOUS SOCIAL MEDIA RESEARCH

In 2009 and 2010 a handful of companies, academic researchers and investors become interested about the idea of using social media data, and particulary Twitter data, for making predictions about real-life events. Some of the early papers covering the topic included work by researchers from Indiana university [1], from STATSIT [2], and from Stanford University [3]. 

By 2011 maybe 10 companies globally were working towards developing serious research capabilities based on social media sampling. Ipsos, Nielsen, etc. were doing what they had always been doing, and then "social media monitoring" or what was still then widely referred to as "sentiment analysis". Brainjuicer is one of the few companies from the traditional research field that has been credited for developing advanved research methods that rely on social media data. While hunderds of social media monitoring and research companies crowded the market place, still today very few social media listening or research company live up to the rigor and standards of the market research industry. 

"Serious social media research" is a term coined by Dr. Deborah Koh, Siim Sainas and Mikko Kotila to describe a method for social media research that address 5 pertinent points: 


#### 1) Data is polluted because of bots / spam / etc. 

#### 2) Rampant sampling violations distort the outputs  

#### 3) Reporting focus on quantity (on the expense of quality)

#### 4) Analysis lack statistical rigor - often merely reporting absolute values

#### 5) Outputs are disconnected from decision making


SOMECODE is based on the "serious social media research" methodology, and is the first comprehensive research suite specifically targeted to meet the needs of the most serious researchers wanting to benefit from social media based samples without all the headaches that come with it. 

SOMECODE is focused on Twitter data, and only Twitter data.

Twitter have been proven to be an effective source of data for analysis and prediction of trends and events. Evidence for successful predictions include movie ratings[1], financial market performance[2], disease outbreaks [3] and likeliness of someone becoming a Jihadist fighter[4]. Among countless other examples where real-life events and trends have been succesfully predicted with Twitter data. 


### REFERENCES: 

[1] Twitter mood predicts the stock market

https://arxiv.org/pdf/1010.3003.pdf


[2] Twitter	 Emotional	 Profile	 Improves	 The	  Stock	 Market	 Values  Forecast

http://arc.hhs.se/download.aspx?MediumId=1430


[3] Stock Prediction Using Twitter Sentiment Analysis

http://cs229.stanford.edu/proj2011/GoelMittal-StockMarketPredictionUsingTwitterSentimentAnalysis.pdf


[1] Predicting movie ratings and recommender systems

http://arek-paterek.com/book/


[2] How Investors Are Using Social Media to Make Money

http://fortune.com/2015/12/07/dataminr-hedge-funds-twitter-data/


[3] How Twitter Could Better Predict Disease Outbreaks

https://www.technologyreview.com/s/419845/how-twitter-could-better-predict-disease-outbreaks/


[4] Scientists Use Twitter to Predict Who Will Fight for ISIS

http://www.sciencetimes.com/articles/4802/20150326/scientists-use-twitter-to-predict-who-will-fight-for-isis.htm


[5] Descriptive Analysis of Physical Activity Conversations on Twitter

http://faculty.washington.edu/wpratt/Publications/CHI_WIP_Twitter_v1.0.pdf
