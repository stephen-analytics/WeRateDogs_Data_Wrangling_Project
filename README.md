# WeRateDogs: Data Wrangling Project


## by Stephen Onyeukwu


## Introduction

The WeRateDogs data wrangling project is an exploration of the tweet data from the popular Twitter account [@WeRateDogs](https://twitter.com/dog_rates) which rates people's dogs with humorous comments. The project involves gathering, assessing, and cleaning the tweet data to make it suitable for analysis.



## Dataset
Three datasets are used in this project, they include:s

-  **Enhanced Twitter Archive** downloaded from the udacity platform.
-  **Additional Data via the Twitter API**
-  **Image Prediction File** downladed programmatically with requests library


## Installation

To run this project, you'll need to install the following libraries:

- pandas
- Numpy
- matplotlib
- seaborn
- requests
- json
- tweepy



## Project Overview

1. **Data Gathering**:
    - Enchanced Twitter Archive: Downloaded directly as provided by udacity.
    - Twitter API: The Twitter API was used to gather the tweet data for  WeRateDogs. The tweets were gathered using the tweepy library in Python.

    - Additional Data: Additional data such as the breed of the dog in the tweet and the image prediction was obtained using the requests library in Python. This data was obtained from a given URL.
    
2. **Data Assessment**: The gathered data was then assessed for quality and tidiness issues. The quality issues assessed included missing data, inaccurate data, and data that was not of the correct type. The tidiness issues assessed included issues with the structure of the data, such as having variables in one column that should be spread across multiple columns.

3. **Data Cleaning**: The data was then cleaned to address the quality and tidiness issues found during the assessment. The cleaning steps included removing duplicates, correcting data types, and dealing with missing data. The data was also structured in a way that made it suitable for analysis.

4. **Analysis and Visualization**: Once the data was cleaned, it was analyzed to answer several questions about the tweets from the WeRateDogs account. The results of the analysis were then visualized using the matplotlib and seaborn libraries in Python. The visualizations provided insights into the tweet data.


## Conclusion

From the Analysis carried out the following insights were releaved:

1. There is strong positive relationship between retweet_count and favorite_count which indicates that as the number of retweets for a tweet increases, the number of favorites for that tweet also increases. This relationship is positive because as more people see a tweet and engage with it by retweeting it, it is likely that more people will also take the time to mark the tweet as a favorite.

2. The dog with the highest retweet on average is doggo, puppo while the dog with lowest retweet on average is pupper

3. Most tweet are from iphone users.





