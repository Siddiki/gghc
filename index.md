# Contents
  * [Twitter Engagement Analysis](#twitter-engagement-analysis)
  * [LinkedIn](#linkedin)
  * [Instagram](#instagram)
  * [Earnings Calls Transcripts](#earnings-calls-transcripts)


# Twitter Engagement Analysis

## Methodology

This project is an attempt to analyze the changing activity level of twitter users on a quarter to quarter basis. Originally, the program gathered users who had recently interacted with a tweet from an account with a high number of followers (Like former President Barack Obama ([@BarackObama](https://twitter.com/barackobama)) or Pop Star Katy Perry ([@KatyPerry](https://twitter.com/katyperry)) and produced results for number of likes, retweets, and tweets per quarter. What we found were incredibly biased results - and lots and lots of bots. In the updated run, users who interacted with a Jeff Bezos ([@JeffBezos](https://twitter.com/JeffBezos)) during or before Q1 2016 were sampled, and their activity plotted over time. 

It is worth noting that due to limitations of the twitter API, only users with fewer than 3200 tweets are analyzed. The program gathers and plots the total number of likes, retweets, and tweets by all users per quarter, divided by the number of users analyzed. Of the 2000 gathered users, 545 met our criteria. The following plot is interactive. 

## Results

### Likes, Retweets, and Tweets
<div>
    <a href="https://plot.ly/~siddiki/5/?share_key=A8EvcNHDElNb4ehiDmWgSA" target="_blank" title="styled-line" style="display: block; text-align: center;"><img src="https://plot.ly/~siddiki/5.png?share_key=A8EvcNHDElNb4ehiDmWgSA" alt="styled-line" style="max-width: 100%;width: 600px;"  width="600" onerror="this.onerror=null;this.src='https://plot.ly/404.png';" /></a>
    <script data-plotly="siddiki:5" sharekey-plotly="A8EvcNHDElNb4ehiDmWgSA" src="https://plot.ly/embed.js" async></script>
</div>


### Days Engaged

This table shows the percentage of days that users were engaged in the quarter and the number of users that liked, tweeted, or retweeted something every day.

|         | Average Days engaged      | Users Active Everyday |
|---------|---------------------------|-----------------------|
| Q1 2016 | 38.20%                    | 3                     |
| Q2 2016 | 33.86%                    | 0                     |
| Q3 2016 | 31.05%                    | 1                     |
| Q4 2016 | 31.06%                    | 1                     |
| Q1 2017 | 32.29%                    | 5                     |
| Q2 2017 | 33.77%                    | 5                     |


## Analysis


#### Bots

Early runs of the experiment, run on the followers of celebrity accounts like Katy Perry's, showed that twitter truly has a bot problem. We noticed a massive uptick in activity of the most recent quarter, and a closer look at some of the accounts showed a pattern. Several users were accounts that were created several years ago, had little to no activity for a very long time, and then a sudden uptick of simply retweeting every post and mention regarding Katy Perry. It is very likely that social media managers for these celebrities are buying followers and interactions for a very cheap rate and using those to boost a celebrity's social media presence and consequently promotional power. More about bots in the appendix. 

#### Engagement

Engagement seemed to be on a fairly clear decline until about Q3 2016. Then likes and retweets take a steep turn for the better and the number of tweets stabilize. What could be the cause of this? Perhaps it was an election that will be remembered for how it impacted social media. And although these users aren't interacting as much, they are interacting as often. The users who did stay on the website seem to be using it on about as many days as they have in the past few quarters. 

#### Disparities

It is also interesting to note that as time goes on, the gap between likes, retweets, and tweets, continues to grow. It seems as time goes on, users are liking and retweeting much more than they are tweeting. This seems like it would be positive for advertisers - they benefit much more from a user who engages with other's tweets more than they tweet themselves. It is also interesting to consider what twitter is doing differently to cause this. Are they doing a better job of suggesting tweets to users? Is the culture of twitter shifting towards reading more than tweeting? 

#### A Few Grains of Salt

It is important to note a few things to keep in mind when understanding this data. One is that the sample size is very small - twitter is estimated to have approximately 328 million users, not all of which are active. Due to limitations in the API, only users with fewer than 3200 tweets are analyzed, which again is not representative of the entire population.

##### Collaborators

Yaroslav Faybishenko

##### Appendix

https://www.fastcompany.com/3000064/whos-woman-twitter-bot-profile :

"Bots are cheap. The company Buy Real Marketing will sell you 1,000 of them for $17, or 25,000 for $247–meaning the value of each is about a penny. And who’s buying them? Anyone. A brand’s social media manager will never admit to it, but chances are, gigantic companies have invested in this cheap form of image building. Why wouldn’t they?
Athletes definitely do it. A publicist for some major players–people at the top of their game–told me it’s common in his world. He once tried it himself, just to see what happens. He ordered the $17 package from Buy Real Marketing, via its website buytwitterfollowers.org. “They didn’t come in right away. I thought at first I’d been scammed,” he said. “But sure enough, within three days, they just poured in. It was exactly 1,000. To me, it shook the whole foundation. It made Twitter meaningless.”

The publicist gave me the names of a few people who also bought from Buy Real Marketing, and I dug into their followers. The bots were easy to spot–and these bots, no surprise, follow plenty of other celebrities and big brands. There’s no way to know if these were purchased follows or just pure coincidence, of course, but the list is wide-ranging. One bot from this batch followed Kelly Osbourne, former Formula 1 racer Tiago Monteiro, the Huffington Post, and an “Internet marketing consultant” named Trent Partridge, among 2,000 others.

website where you can purchase followers and retweets: https://www.buyrealmarketing.com/buy-twitter-followers (other sites:  Fiverr, SeoClerks, InterTwitter, FanMeNow, LikedSocial, SocialPresence and Viral Media Boost)

NYT article about fake bots, estimating 20 million fake users in 2013: https://bits.blogs.nytimes.com/2013/04/05/fake-twitter-followers-becomes-multimillion-dollar-business/

Why celebrities are buying bots:
"But it turns out bots are becoming big business—not for Twitter users, but for companies that sell batches of fake accounts. Several companies exist solely to sell batches of fake accounts for anywhere from $2 to $30 per account. The bot-selling business could pull in $360 million at the higher end, and a more modest $40 million at the lower end.
Those figures come from security researchers Carlo De Micheli and Andrea Stroppa, who told the New York Times that there are some 20 million fake Twitter accounts. They arrived at that number after analyzing the most popular tweet-sellers, including Fiverr and LikedSocial.
There are many reasons someone would want to buy followers. After all, popularity is currency in social media. Companies, politicians, bloggers, and media outlets all benefit when they rack up followers. It’s even better when those followers retweet your content, like links to products, fundraising pages, or articles. A robust number of followers and retweets lend legitimacy in the social media world. Real people are more apt to like something on Facebook or follow someone on Twitter if that product or person is already established.
These days, fake followers are being fleshed out with seemingly real names, bios, and even websites. But the real emphasis is on retweets—companies or individuals can buy a certain number of retweets per account per day. Stroppa and De Micheli told the Times that five retweets a day can be had for $9 a month, and 125 daily retweets for $150 a month."

Vice article from March stating 15 percent of twitter users are bots, mentions how it affects advertising:

https://news.vice.com/story/twitters-users-are-15-percent-robot-but-thats-not-necessarily-a-bad-thing

"A new study from the University of Southern California and Indiana University finds that up to 48 million Twitter users — or 15 percent of all users — are bots...
Advertisers pay Twitter when an an action takes place — a retweet, a like, or click-through on a link — so certain types of bots can disrupt Twitter’s business with fraudulent clicks. But if bots are sharing information like regular users, are they necessarily bad for advertisers? It seems that bots, like people, can be good, bad, or neither."

Interesting read about how bots affected the election: https://www.theatlantic.com/technology/archive/2016/11/election-bots/506072/

# LinkedIn

## Methodology

This project is an effort to automate the identification of CFOs who have been a part of multiple companies that were acquired.

**Note this project was canceled because of linkedin changing their API access to non-partners.

##### Collaborators

Yaroslav Faybishenko

# Instagram

## Methodology

This project documents the amount of times a location is being tagged on instagram. Simple python script using Instagram API. 

##### Collaborators

Elena Burger, Lucy Tang

# Earnings Calls Transcripts

## Introduction

The goal of this project is to be able to find stocks that are similar to stocks we have found interesting in the past without actually having to have a human read every call for every stock on the market. This project is a two-part machine learning effort that aims to unearth earnings calls that match the profile of the calls for stocks in our portfolio. The first part required the building of a sentiment analysis model that would analyze conference calls that led to taking a position in a stock - long or short - and build a profile of these stocks using certain metrics (e.g. percent negative, percent positive, composite sentiment score). The second portion is to build another machine learning model that would learn said profile and be able to take sentiment analysis scores from earnings calls that have not yet been read and output a probability of them matching the profile of calls that indicates long or short. 

## Sentiment Analysis

This portion of the program analyzes the conference call and classifies statements based on their sentiment, along with outputting some metrics. These metrics are used in the logistic regression model to learn a profile for conference calls and subsequently make predictions about a call matching the profile of a long or a short. 

### Example output

This is an example of snippets of a conference call that were processed by the program. In order of most negative to most positive the highlighting scheme is as follows: red, yellow, no highlight, green, blue. 

***
<html><style type='text/css'>
html {
  font-family: Arial;
  color: #000000;
}
r {
  color: #000000;
  background: #9D190E;
}
g {
  color: #000000;
  background: #05AD0D;
}
b {
  color: #000000;
  background: #0061ff;
}
y {
  color: #000000;
  background: #FFC300;
}
k {
  color: #000000
}
.grayBorder {
 border: 2px dashed gray;
 padding: 50px;
 }
</style><div style="grayBorder"><k>
</k><br><b>In closing, our focus remains on executing our New World Fossil restructuring efforts, advancing our wearables initiative and stabilizing and growing our core watch business to drive long-term profitable growth. Given our conviction and the positive impact these initiatives can have on our financial performance, we are also working to ensure that we have the proper capital structure needed to support our long-term financial objectives.

</b><br><k>

</k><br><b>We are taking the necessary steps to strengthen our financial position to further enable us to execute our strategies well into the future and position our business model for continued strong cash flow generation.

</b><br><k>

</k><br><g>Now I'd like to turn the call over to Dennis for additional color on our financial performance.

</g><br><k>

</k><br>Dennis R. Secor - Fossil Group, Inc.

<br><k>

</k><br><k>Thanks, Kosta, and good afternoon, everyone. Before I provide an operational review of the quarter, let me discuss the impairment charge we've reported on today. In the quarter, we recognized a $407 million or $6.50 per share non-cash charge to impair certain intangible assets primarily related to goodwill. The impairment was triggered by the sustained compression of our market cap that occurred throughout most of the back half of the second quarter. This charge significantly impacts this quarter's operating expenses. However, it does not impact our liquidity or financial covenant calculation. I will isolate it where relevant as I discuss our overall results.

</k><br><k>

</k><br><r>Second quarter constant currency net sales decreased 12% and on a reported basis decreased 13% to $597 million. Our traditional watch business performed within our expectations, though still down compared to a year ago. During the quarter, wearables continued to positively impact the trend of our business. Overall, wearables represented roughly 9% of our sales for the quarter, a sequential improvement from the 7% in the first quarter.

</r><br><k>

</k><br><y>Our Connected business, which posted more than a 300% increase off a relatively low base last year, did not fully deliver against our ambitious goals for the quarter. Overall, our sales for the quarter were just short of our expectations.

</y><br><k>

</k><br><g>We were able to offset the shortfall in our sales goals with higher traditional gross margins as we delivered stronger cost reductions in our supply chain and managed the quarter with lower recurring expenses.

</g><br></div></html>

***
```python
negative: 0.0746606334841629
positive: 0.4029034690799397
neutral: 0.5224358974358975
average: 0.132615874293
```
***
Below is the graph of the scores of calls for 150 long and 150 short positions in the DH group portfolio. The logistic regression model learns based on this data to classify calls as long or short. Red markers represent short positions and blue markers represent long positions.

![graph1](https://github.com/Siddiki/gghc/blob/master/graph.PNG?raw=true)

## Logistic Regression
Logistic regression models are trained to output probabilities to make classifications based on input data. The idea is to train on the sentiment profiles of conference calls that led to positions and then be able to predict the probability of a call being a short or a long based on its own sentiment profile. Below is a graph of the accuracy of the model. 

![graph2](https://github.com/Siddiki/gghc/blob/master/acc.png?raw=true)

## Predictions

Below are the results of analysis on real conference calls from 10 companies with market cap over $500M

| Ticker | Sigmoid Output | Prediction |
|--------|----------------|------------|
| MCRB   | 0.26           | SHORT      |
| CARB   | 0.98           | LONG       |
| GNMK   | 0.98           | LONG       |
| GDEN   | 0.43           | SHORT      |
| HMTV   | 0.84           | LONG       |
| ABEO   | 0.98           | LONG       |
| BLDP   | 0.62           | LONG       |
| PLAB   | 0.10           | SHORT      |
| OSTK   | 0.73           | LONG       |
| MBUU   | 0.49           | SHORT      |

## Conclusion

The model achieves approximately **68% accuracy** in classifying a stock as a long or a short based on the similarity of conference call data to that of calls which may have led to taking a position in the past. An untrained model should theoretically be at about 50% accuracy. It is important to note that this accuracy does not represent or predict the *performance of stocks* but rather the ability of the model **to recognize the patterns of the group's positions in the past.** And of course it does not take into account anything asides from the sentiment data of a call itself, whereas when a portfolio manager takes a position, much additional analysis is reviewed. This could include considering other stocks, the performance of the industry, conference calls prior to the last call before taking a position, etc. 

### Improvements

The program requires some polishing - the sentiment analysis program is trained only on movie review data and not on actual conference call information. Results could potentially be highly improved and more accurate if a labeled set of statements from confernce calls was trained on. The issue here is the time it would take to label - human time sunk into individually labeling 10,000 sentences for the program to learn. Each call takes about 8 minutes to process on our current cloud instance. Additionally, the 300 calls analyzed from the portfolio for training are a very small percent - about 5% of the calls. 

## Appendix

### Deciding a Model Architecture - Research and Failed Attempts

My research began with reading papers on classical natural language processing (NLP) using ideas such as bag-of-words and vector embeddings and evolved soon into deep learning territory. The biggest challenge facing me was deciding what architecture to use - with no real guidelines or rules of thumb on what would work best for the challenge facing me - I researched and implemented several models. The first challenge was deciding between convolutional (CNN) and recurrent neural networks (RNN). CNNs in general are effective at feature extraction, whereas RNNs have been effective in the past for sequential modeling (which is how we process text.) Ultimately after combing through multiple papers, blog posts, and github repositories, I settled on an recurrent neural network architecture known as multiplicative long short-term memory (mLSTM). 

### mLSTM

A [blog post](https://blog.openai.com/unsupervised-sentiment-neuron/) from non-profit AI research company [OpenAI](https://openai.com/about/) led me to looking into the architecture I ultimately chose for the sentiment analysis portion of the project. In their [research](https://arxiv.org/abs/1704.01444) they were aiming to build a generative model and found that in their architecture, almost the entire sentiment signal was contained in one distinct neuron. This led to state-of-the-art sentiment analysis accuracy on the Stanford Sentiment Treebank dataset (91.8% accuracy versus the previous best of 90.2%). I used and modified their [open source model](https://github.com/openai/generating-reviews-discovering-sentiment) for the task. 

### Logistic Regression

Logistic Regression is a well studied problem with many widely available and succesful architectures available for use. The one I am using for this project is a modified version of the model that can be found [here](https://github.com/nfmcclure/tensorflow_cookbook/tree/master/03_Linear_Regression/08_Implementing_Logistic_Regression).

##### Collaborators

Yaroslav Faybishenko, Steve Steinberg
