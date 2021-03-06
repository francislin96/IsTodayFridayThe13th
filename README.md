# IsTodayFridayThe13th

[/r/IsTodayFridayThe13th](https://www.reddit.com/r/IsTodayFridayThe13th) is a subreddit that asks and answers the same question every day: "Is Today Friday the 13th?" While it has a simple premise, its [most popular post](https://www.reddit.com/r/IsTodayFridayThe13th/comments/d3ozdj/is_today_friday_the_13th/) has over 140k upvotes.

I wanted to take a look at how the community has grown since it was first created. Using the [pushshift.io](https://pushshift.io/) API, I was able to gather all of the post IDs and number of subscribers on each date. I then gathered the number of upvotes and comments per post through the [Reddit API](https://www.reddit.com/wiki/api) through [PRAW](https://praw.readthedocs.io/en/latest/). Matplotlib was used for visualization and Dask was used to parallelize hitting the Reddit API.

![./IsTodayFridayThe13thUpvotes.png](https://raw.githubusercontent.com/francislin96/IsTodayFridayThe13th/master/IsTodayFridayThe13thUpvotes.png)

![./IsTodayFridayThe13thComments.png](https://raw.githubusercontent.com/francislin96/IsTodayFridayThe13th/master/IsTodayFridayThe13thComments.png)

![./IsTodayFridayThe13thSubscribers.png](https://raw.githubusercontent.com/francislin96/IsTodayFridayThe13th/master/IsTodayFridayThe13thSubscribers.png)

\* Last updated: Nov 20, 2020
