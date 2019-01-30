# reddit-playground

Files taken from: https://files.pushshift.io/reddit/comments/

Results (Corpus: Comments from September 2018) :

1. `english-subs.csv`: Collection of subreddits sorted by a) Total Number of English Comments, b) Ratio of English Comments vs Total Comments. 
2. `bots-filtered.csv`: List of all user accounts sorted by response time. 
    These Data points are available in the dataset: 
    2.1) Average Response Time
    2.2) Total Number of comments made by the user
    2.3) Total Number of unique subreddits the user has commented on
    2.4) Total Number of unique submission by the user
    2.5) Average Comment Length
    2.6) Levenshtein Ratio - Average of Levenshtein Score over all the user comments. Levenshtein Score is calculated between two comments: any given comment made by the user vs the last comment made by the same user. This gives us an obvious metric to detect bots (since bots usually have repetition in their commenting style)
