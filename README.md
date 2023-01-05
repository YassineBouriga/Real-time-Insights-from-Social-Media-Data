## Data Analysis Project
# Real-time Insights from Social Media Data

![](Images/title.PNG)

-----------------------------------------------------

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/YassineBouriga/Real-time-Insights-from-Social-Media-Data/main?labpath=notebook.ipynb)

## Project presentation :

In this project, I used pre-downloaded datasets to understand the nuts and bolts of Twitter data.
In particular, I did a thorough analysis of a hot trend.

## Detailed description of the work done on this project :

I loaded and inspected the data and then used json.dumps() to make the data more readable, I then extracted the names of common trends, texts, usernames, and hashtags from the tweets.
After creating a frequency distribution to organize and present frequency counts so that the information can be interpreted more easily, 
I started extracting data for retweets such as; retweet count, favorite count, followers count, screen name, and text from the fields of each tweet.
I created a table with insights using DataFrame, grouped them using groupby(), and used sort_values() with the followers as a parameter to sort the table by decreasing number of followers.
Later on, I extracted the language of each tweet and added it to the list of languages using the append method, 
and finally, I used the hist() method of Matplotlib with the tweets_languages as an input parameter to plot the frequency distribution of languages to create a histogram that shows the most used languages.

## Conclusion :

To conclude, this can allow us to get an understanding of the "category" of people interested in this topic (clustering). We could also analyze the device type used by the Twitteratis, tweet['source'], to answer questions like, "Does owning an Apple compared to Andorid influences people's propensity towards this trend?".

## Libraries used :

* pandas

![](Images/pandas.PNG)


* matplotlib

![](Images/matplotlib.PNG)
