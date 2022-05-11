# Blog Comments Prediction

Below are the details for the attached files:
* **blog_test_data.ipynb**: original modeling file used to build models based on original data.
* **refreshtoken.py**: utility file used to get the refresh token necessary to continually interact with the Reddit API.
* **BlogScraping.ipynb**: scrapes reddit using the PRAW API to create all the necessary features.
* **bagofWords_Reddit.ipynb**: used to created the 200 bag of word features necessary for the model.
* **RedditModleing.ipynb**: data file used to run base models against Reddit models.
* **RedditData.csv**: data file imported into the bagofWords_Reddit file with all the basic statistical features.
* **reddit-final.csv**: data file imported into the RedditModeling file to do the final modeling.

Data set used to build the original models can be found at: https://archive.ics.uci.edu/ml/datasets/BlogFeedback
