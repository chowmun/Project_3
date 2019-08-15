# Project 3 - Reddit post classification 

Problem Statements¶

1.Reddit posts are extremely large, it is near to impossible to sort all the posts manually.
2.How to utilise machine learning ability(NLP) to organise the posts into a logical acceptable way.

This project consists of:
A. API Scrapping
B. Data Cleaning
C. Modeling
D. Model Evaluation
E. Conclusion and Recommendation 

### Data dictionary
|Feature|Type|Description|
|---|---|---|
|**subreddit**|object|Specific page on reddit| 
|**title**|object|The title of subreddit| 
|**selftext**|object|The message inside the subreddit| 
|**content**|object|The combination of title and selftext | 

Conclusion and Recommendation<br>
1.Some of the posts contains only a few words and it is hard for the model to predict the outcome accurately.<br>
2.The model performs better under LogisticRegression with the average accuracy of 0.93 and average precision of 0.93. It is performs far more better from the baseline.<br>
3.Given our preliminary findings we would recommend that the Reddit data science team move forward with the LogisitcRegression.<br>
4.In future, we could explore in the classification of subreddit with the pictures posted in the post as one of the feature.




              