# Contents
  * [Twitter Engagement Analysis](#twitter-engagement-analysis)
  * [LinkedIn](#linkedin)
  * [Instagram](#instagram)
  * [Earnings Calls Transcripts](#earnings-calls-transcripts)


# Twitter Engagement Analysis

## Methodology

This project is an attempt to analyze the changing activity level of twitter users on a quarter to quarter basis. Originally, the program gathered users who had recently interacted with a tweet from an account with a high number of followers (Like former President Barack Obama ([@BarackObama](https://twitter.com/barackobama)) or Pop Star Katy Perry ([@KatyPerry](https://twitter.com/katyperry)) and produced results for number of likes, retweets, and tweets per quarter. What we found were incredibly biased results - and lots and lots of bots. In the updated run, users who interacted with a Jeff Bezos ([@JeffBezos](https://twitter.com/JeffBezos)) during or before Q! 2016 were sampled, and their activity plotted over time. 

It is worth noting that due to limitations of the twitter API, only users with fewer than 3200 tweets are analyzed. The program gathers and plots the total number of likes, retweets, and tweets by all users per quarter, divided by the number of users analyzed. Of the 2000 gathered users, 545 met our criteria. The following plot is interactive. 

## Results

### Likes, Retweets, and Tweets
<div>
    <a href="https://plot.ly/~siddiki/5/?share_key=A8EvcNHDElNb4ehiDmWgSA" target="_blank" title="styled-line" style="display: block; text-align: center;"><img src="https://plot.ly/~siddiki/5.png?share_key=A8EvcNHDElNb4ehiDmWgSA" alt="styled-line" style="max-width: 100%;width: 600px;"  width="600" onerror="this.onerror=null;this.src='https://plot.ly/404.png';" /></a>
    <script data-plotly="siddiki:5" sharekey-plotly="A8EvcNHDElNb4ehiDmWgSA" src="https://plot.ly/embed.js" async></script>
</div>


### Days Engaged

This table shows the percentage of days that users were engaged in the quarter and the number of users that liked, tweeted, or retweeted something every day.

|         | Users created before 2016 | Users Active Everyday |
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
