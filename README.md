# TheMuskEffect

Can we predict Crypto market movement based on Elon Musk tweets.

## Approach

- Get historical Elon Musks tweets
    - Twitter API
    - Dumps already exists
- Is tweet related to crypto?
    - Keyword analysis
    - More sophistecated method?
- Is the sentiment of the tweet positive or negative?
    - Sentiment analysis
        - Remove stopwords,
    - Positive: Increase in value
    - Negative: Decrease in value
- Check the value of crypto to evaluate model
    - Get historical value of crypto (Dogecoin)

## TODOS

- [] Historical data for the interesting period is missing (We only have data until 2021-04-01)
- [] Mulitply tweets per day, we currently assume the impact will be visible over days, but it might be over hours instead
- [] Crypto related tweet
    - [] More words
    - [] Another approach
- [] Can we add Context
    - [] Better sentiment analysis
    - [] Crypto change just before tweet
    - [] Check if sentiment score is right
- [] Crypto value
    - [] Higher resolution than daily
