# datastory.github.io
# Jazzssmine.github.io

# Want to grab attetions on Twitter?

### --How to Maximize an Original Post's Retweet Count

### Why are we interested? What problems do we hope to solve?

Twitter is a place where we relax ourselves, interact with others and know what’s happening around the world. Also, over the past few years, it has been a distinct social medium where the president of the United States communicates with the public.  An influencer is someone with millions of followers and a global presence. These days, Twitter has become more and more powerful as a social tool for all kinds of people. However, on Twitter you are one user among millions, and getting attention can be difficult. So what intrigues us the most is how can we establish a tweet, what kind of strategy can help us to get more attention and gain more retweets?

Based on the data available, here we mainly focus on **analyzing the factors that covary with the original post's retweet count**. In the original paper *Testing Propositions Derived from Twitter Studies: Generalization and Replication in Computational Social Science* by Hai Liang et al, they analyzed information diffusion at user and tweet level. However, the results only tell us whether multiple factors are positively or negatively correlated. We still have little idea of how exactly are they correlated: for example, **is the retweet count linearly increase with the number of followers? Is there certain "threshold effect"?** Also, we are interested in **whether posting in English - an international language - helps in getting more retweet count**. If that is the case, one might choose to post in English! *At the tweet level*, they found that <u>the presence of hashtags is positively correlated and the presences of URLs and mentions are negatively correlated</u>. This is something interesting! It suggests posting with a hashtag! However, you might also be interested to know **when is the best to post**. A hint is suggested by the paper that <u>users are more active in weekdays than on weekends and during a day, 8pm is when the number of active users reach the peak</u>. Well, is it really that posts posted at 8pm get the most retweet count on average?

That’s what this article is all about. We’ll show you what types of user and tweet that people pay attention to.

Let's explore together!

## data description

:memo:EgoTimelines: The dataset contains ego users’ dynamic activities, including posting original tweets, retweeting, replying and @-mentioning. It also contains information about the number of retweets, presence of URLs and presence of hashtags for each tweet. The dataset is ideal to analyze the contributions of factors at the post level to the post’s influence.

:memo:EgoAlterProfiles: The dataset contains sampled users profiles, including the number of followers, languages, account created time, etc. Combined with the “retweet_count” term in EgoTimelines dataset we can analyze the effect of the number of followers and language (factors on the user level) on the post’s influence.

:memo:EgoNetwork: This dataset contains all pairs of ego-alter relationships, where the number of followees for each ego users can be calculated and further analyzed.!


## goal

## findings

* user level

  * **post with hashtags**--**Join trending hashtags on Twitter**

    From above analysis, we realize that, if you already have many followers, you might not need to do much to get retweets; but if you do not, just like user 17159, **it's a smart choice to post with hashtags**, which will make your posts seen by more!

    [Hashtags are laser pointers](https://www.postplanner.com/hashtag-ideas-for-twitter-campaigns/) that shine on folks serious about a topic.

  * **gather more followers**

    We noticed that as the followers/followees/friends counts increases (from the first row to the fifth row) the probability of receiving more retweets increases (the plot gets "fatter"). **Especially when number reaches three digits the effect starts to become significant.**

  * **be more interactive**--**Respond to followers**--**Respond to people who reply to your tweets**

    By following more people, being more interactive (getting more friends), the user can hopefully get more followers and more retweets. When the figure reaches two digits from one digit, the user might not see much increase in terms of retweet count of a plain post, but once one has made it to three figures, he can expect to see some significant changes.

    Twitter is primarily about making connections and building dialogue. The last time I checked, it takes at least two people to get a dialogue going. BE that person who is there to engage in community, not to blast out a solid stream of spam.

  * **what language do you speak?**

    The fanatics: Arabic speakers have the highest average number of followers count, and they also have the highest retweets frequency among all langauge user groups.

    The actives: Dutch speaker, and japanese speakers share a common point: they more like to retweet even though they don’t necessarily have a high number of followers count. Which may be explained as they really focus on their favorite followers and keep interacting with them rather than follow many people but remain inactive. Therefore, **if you are Dutch or Japanese speaker, we would suggest you to posting in these languages as your post might get a higher chance of being retweeted by your people!**

    The silent group: Russian speaker and German speakers are the exact opposite of the previous category. Russian speakers and German speakers they have a high average follower count, which means they are active on this social media. But in the same time they have a low retweet frequqncy, which could be explained as they are more cautious about retweeting what others say. Therefore, **if you are Russian or German speaker, you might like to post in English to change your audiances to those who are more willing to retweet.** :P

  

* Tweet level

## future works?

Textual!!!!!!!!!!!!!!!!!

## what have we learn


