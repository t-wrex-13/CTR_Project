# CTR_Project
This is a ML project looking to predict click-through rate from a [large data set from Taobao found on Kaggle](https://www.kaggle.com/datasets/pavansanagapati/ad-displayclick-data-on-taobaocom)

Summary of the questions and answers.
The central goal of this project was to answer one key question: How can we accurately predict whether a user will click on a specific ad in a large-scale e-commerce environment? The answer was yes - we were able to generally predict click through

We also explored related questions, such as:

What are the most influential factors—from a user's behavior to an ad's characteristics—that drive clicks? User Behavior is King: The two features with the highest importance are user_distinct_categories and user_category_interactions. This is a significant finding. It shows that a user's past behavior—specifically, the variety of product categories they've interacted with and how they've engaged with them—is the single strongest predictor of whether they will click on a new ad

How can we build a model that overcomes the challenge of extreme data imbalance, where clicks are far less frequent than non-clicks? We had to add heavy weights and use a massive amount of data to overcome this imbalance. In fact, an even LARGER data set than the 26 million data points from the Taobao data set might increase performance

Link to the final project paper.


Link to a video demonstration.
