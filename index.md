# Contents
  * [Twitter Engagement Analysis](#twitter)
  * [LinkedIn](#linkedin)
  * [Instagram](#ig)
  * [Earnings Calls Transcripts](#NLP)


# Twitter Engagement Analysis

## Methodology

This project is an attempt to analyze the changing activity level of twitter users on a quarter to quarter basis. The program gathers approximately 2000 users who have recently interacted with a tweet from an account with a high number of followers (Like former President Barack Obama ([@BarackObama](https://twitter.com/barackobama)) or Pop Star Katy Perry ([@KatyPerry](https://twitter.com/katyperry)) and produces results for two classes of users:
1. Users who had an account prior to 2016
2. Users who created an account in Q1 2016

It is worth noting that due to limitations of the twitter API, only users with fewer than 3200 tweets are analyzed. The program gathers and plots the total number of likes, retweets, and tweets by all users per quarter, divided by the number of users analyzed. Of the 2000 gathered users, approximately 200 met criteria 1 and about X users met criteria 2. The following plot is interactive. 

## Results

### Likes, Retweets, and Tweets
<div>
    <a href="https://plot.ly/~siddiki/5/?share_key=A8EvcNHDElNb4ehiDmWgSA" target="_blank" title="styled-line" style="display: block; text-align: center;"><img src="https://plot.ly/~siddiki/5.png?share_key=A8EvcNHDElNb4ehiDmWgSA" alt="styled-line" style="max-width: 100%;width: 600px;"  width="600" onerror="this.onerror=null;this.src='https://plot.ly/404.png';" /></a>
    <script data-plotly="siddiki:5" sharekey-plotly="A8EvcNHDElNb4ehiDmWgSA" src="https://plot.ly/embed.js" async></script>
</div>

### Days Engaged

|         | Users created before 2016 | Users Created Q1 2016 |
|---------|---------------------------|-----------------------|
| Q1 2016 | 27.3 %                    |                       |
| Q2 2016 | 22.8%                     |                       |
| Q3 2016 | 38.1%                     |                       |
| Q4 2016 | 41.0%                     |                       |
| Q1 2017 | 55.4%                     |                       |
| Q2 2017 | 68.5%                     |                       |

For users in category 1, only 2 users had 100% engagement in a quarter, and both fell in Q2 2017 (which is still ongoing).

## Analysis

#### Engagement

It is clear from even a brief look at the graphs and tables that engagement has gone up. Multiple results show a small dip in the amount of engagement between quarter 1 and 2 of 2016, but after that, a big jump, one that is reflected by their revenue in the quarter: ["The company posted revenue of $616 million in revenue, an 8% lift year-over-year, and an adjusted profit of $0.13 a share in the three months that ended September 30."](http://www.businessinsider.com/twitter-q3-earnings-2016-10) What could cause this jump? One possibility is the election, one that will be remembered for having a big impact on social media. Another interesting jump in engagement is the one in Q2 2017. This one seems unnatural and baseless - the quarter isn't even over yet and there have been more tweets than the last few quarters by a significant margin. It seems unlikely to me that this jump is caused by human users, and is much more likely to be the result of bots. 

#### Disparities

It is also interesting to note that as time goes on, the gap between likes, retweets, and tweets, continues to grow. It seems as time goes on, users are liking and retweeting much more than they are tweeting. 

#### A Few Grains of Salt

It is important to note a few things to keep in mind when understanding this data. One is that the sample size is very small - twitter is estimated to have approximately 328 million users, not all of which are active. Due to limitations in the API, only users with fewer than 3200 tweets are analyzed, which again is not representative of the entire population. Nonetheless, through multiple experiments, the trends do stay fairly the same, and the trends themselves show something of value.

##### Collaborators

Yaroslav Faybishenko

# LinkedIn

## Methodology

This project is an effort to automate the identification of CFOs who have been a part of multiple companies that were acquired. 

##### Collaborators

Yaroslav Faybishenko

# Instagram

## Methodology

This project documents the amount of times a location is being tagged on instagram.

##### Collaborators

Elena Burger, Lucy Tang

# Earnings Calls Transcripts

## Methodology

This project is an effort to learn attributes of earnings calls reports that have been indicative of positive results for a company in the past, and then process multiple reports to identify potentially interesting companies. 

##### Collaborators

Yaroslav Faybishenko, Steve Steinberg
