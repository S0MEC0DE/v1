========
OVERVIEW
========

SOMECODE is a research platform for serious observation and analysis of Twitter data. SOMECODE brings together 9 years of unbroken continuity in developing social media research tools. Previous tools and processes developed by the contributor team are in daily use by many FORTUNE100 companies and major advertising agencies. SOMECODE is the solution we always wanted to build, but due to the kinds of restraints commercial entities have, never got to. ::

    pip install somecode

All you need to have is Python 2.7 and the somecode installation will take care of all the dependencies. 

--------
BENEFITS
--------

With one command from idea to looking at results of regression analysis, advanced plotting, sentiment analysis, etc. etc.

- Get started with serious social media research in minutes
- Equal or better capabilities vs. best industrial solution
- Up to 10 million tweets per day with single API key
- Optmized for minimizing out-of-scope time use (configuration, data wrangling, etc.)
- Supports both streaming and rest API endpoints for both status (tweet) and user objects
- Provides an ideal environment for academic research and publication

SOMECODE is built by researchers for researchers and is very easy to extend / customize to suit specific needs. For most research scopes SOMECODE will work "out of the box". It has very few depedencies (below) and takes minutes to deploy for your first research project.

GETTING STARTED
---------------

DESKTOP:
........

SOMECODE runs on any regular low-end laptop with a common web browser. Tested on Linux and Mac OS X. Jupyter is highly recommended. 

SERVER/CLOUD:
.............

SOMECODE runs on Amazon Nano (or similar) for $5 per month. Tested on Ubuntu 14.04LTS

For both options::

    pip install somecode 

SOMECODE is very easy to customize / extend if you would feel the need to do it. Even if you are a beginner python learner.

100% fun, 0% mindless wrangling.

-----------
PERFORMANCE
-----------

During the 2016 election, SOMECODE topical, sentiment, scoring and other computations have been tested in up to 200,000 tweets per hour volume using a single $50 per month server (8gb RAM) where the computations required for every 10 minute cycle were generally completed in 20 seconds. 


---------
FUNCTIONS
---------

DATAPOINTS
---------- 

All of the 'data collection' methods ('search','stream','timeline','flatfile') return a pandas dataframe with direct signals from Twitter, together with SOMECODE scores and other inferred metrics.::

    VARIABLE                        DTYPE
    days_since_creation             int64
    influence_score                 int64
    reach_score                     int64
    quality_score                   int64
    retweet_count                   int64
    text                           object
    user_tweets                     int64
    user_favourites                 int64
    user_followers                  int64
    user_following                  int64
    user_listed                     int64
    handle                         object
    created_at             datetime64[ns]
    default_profile                  bool
    egg_account                      bool
    description                    object
    location                       object
    timezone                       object
    compound                      float64
    neu                           float64
    neg                           float64
    pos                           float64

DATA COLLECTION
---------------

There are four ways to get data in to SOMECODE. 

- a one-time search (use Twitter Rest API
- stream for some time (use Twitter streaming API)
- timeline search 
- loading from a file

# search()

An example of use to get 1000 tweets for keyword "election"::

    some.search("hillary",1000)

search() has three parameters: 

keyword 
max_tweets 
language (by default


+------------------------+-------------+------------+
| Header row, column 1   | Default     | notes      |
| (header rows optional) |             |            |
+========================+=============+============+
| keyword                | *           | 1  or list |
+------------------------+-------------+------------+
| max_tweets             | 200         | 0 - 3200   |
+------------------------+-------------+------------+
| language               | 'en'        | any        |
+------------------------+-------------+------------+

(*)required input

stream()
flatfile()
timeline()

Example use

search("election",1000)

items = single keyword, single user, list of keywords, list of users
kind = either 'user' or 'keyword' (default is 'keyword')

You also need to set access_token, access_secret, consumer_secret
and consumer_key (get it from http://apps.twitter.com)

EXAMPLE SEARCH QUERIES: 

users = ['3329715436','4064981488','1345822466','21587082']
keywords = ['hillary','trump']


DATA PROCESSING
...............

REPORTING
.........


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


BUILT ON
--------

Frankly speaking, SOMECODE would not be possible without all the amazing technology solutions it's based on. What SOMECODE does, is put a few key technologies together, with "business logic" that came from working on over a thousand social media research projects since 2005. Somecode uses pandas, numpy, seaborn and matplotlib libraries heavily.

Other than that, dependent on the system, you should have minimal dependencies to worry about. Also if you're not using it already, I highly recommend Jupyter (http://jupyter.org/). It helps make programming much more about fun, and less about frustration.
