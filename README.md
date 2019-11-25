# Indian Subreddit Flair prediciton

Creating a **Classification** model for predicting the the flair of a post using it's content, date and comments.

##  Database used
MongoDB, to save the extracted posts for analysis and easy share.


## All Flairs(to be predicted)
|Flair   | Count |
|--|--|
| Non-Political | 2161 |
| NaN|9838 |
| Politics| 2122|
| Science/Technology| 479|
|AskIndia | 1385|
| Photography|254 |
| Policy/Economy| 478|
|Business/Finance |726 |
|Sports |138 |
| Food| 147| 
|Demonetization | 80|
|Scheduled | 28|

## API
 - Praw( had a limit on post extraction)
- PushShift


# Models Used

 - Naive Bayes 
 - Linear SVM

## Data set used

The given model contains  a dataset of around 10000 posts, whuch took around 45 mins to extract and process.
This data was the exported to MongoDB










```
