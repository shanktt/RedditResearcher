# RedditResearcher
Python Package intended for Reddit Researchers. Lets make collecting posts and comments from Reddit easier!

# Planned Features
* Collect post ids and comments ids from PushShift API
  * This will support subreddit, date range, number of comments, number of votes, filtering 
* Collect post and comment data from Reddit using PRAW and ids from PushShift and format them into a standardized csv
  * I plan on copying some of the formating used by [RedditExtractor](https://cran.r-project.org/web/packages/RedditExtractoR/RedditExtractoR.pdf) for displaying comment trees
* Options for downloading images and other media from non-text posts
