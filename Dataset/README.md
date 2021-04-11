# Dataset

We are using **sentiment140 dataset** from kaggle which contains 1.6 million tweets scraped from twitter using the twitter API. Each tweet is given a label, 0 being negative and 4 being positive and can be used to detect and predict sentiments. 

The dataset has following fields:

1. **Sentiment**: Sentiment of the tweet. 0 = Negative, 4 = Positive
2. **Tweet ID**:  Tweet ID
3. **Date**:      Date and time of tweet
4. **Flag**:      NO_QUERY
5. **User**:      Owner of the tweet
6. **Tweet**:     Body of the tweet

The only fields of concern for us are the **Sentiment** and the **Tweet** field and we can do away with rest of the fields.
