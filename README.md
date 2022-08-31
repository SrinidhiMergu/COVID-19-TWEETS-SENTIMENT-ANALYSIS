# COVID-19 Tweets Sentiment Analysis

Developed sentiment analysis model using Natural Language Processing to understand relationship between public vaccination programs and public reception.

Through sentiment analysis we looked for things such as 
- Sentiment Polarity like whether the tweet is neutral/positive/negative in relationship with each vaccinend
- Evolution of sentiment in time

#### FEATURES IN TRAIN_TWEETS DATASET:
- Text_id: order no. of tweet
- Text: given tweet
- Selected_text: important part of given tweet
- Sentiment: neutral/positive/negative

#### FEATURES IN VACCINATION TEETS DATASET
- id
- user_name
- user_location
- user_description
- user_created
- user_followers
- user_friends
- user_favourites
- user_verified
- date
- text
- hashtags
- source
- retweets	
- favorites	
- is_retweet

#### TASKS PERFORMED:
- Clean data (fill null values, drop duplicates, clean text)
- Done train test split
- Models Building: 
    1. Naïve Bayes (MultinomialNB) (78)
    2. SGD Classifier (79)
    3. SVM (SVC) (83)
- Hyper parameter tuning using GridSearchCV
- Obtained
    1. accuracy score: 84
    2. Classification report
    3. confusion matrix
- Applied vaccination tweets dataset to the model
- Clean Data (remove duplicates, fill null values0
- Obtained correlatioin matrix (heat map)
- Performed sentiment analysis
- Analysed tweets using WordClouds
- Performed timeline analysis
