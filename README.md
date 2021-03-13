# Unit 12—Tales from the Crypto

![Stock Sentiment](Images/crypto_news.jfif)

## Background

In this assignment I'm tasked with getting the latest news headlines regarding Bitcoin and Ethereum to get a better feel for the current public sentiment around each coin.

In order for me to find the sentiment I'll apply natural language processing to understand the sentiment in the latest news articles featuring Bitcoin and Ethereum. I'll also apply fundamental NLP techniques to better understand the other factors involved with the coin prices such as common words and phrases and organizations and entities mentioned in the articles.

Tasks to be completed:

1. Sentiment Analysis
2. Natural Language Processing
3. Named Entity Recognition


#### Sentiment Analysis

I have the following answers to the questions:

### Questions:

Q: Which coin had the highest mean positive score?

A: Ethereum has a higher mean positive score than BitCoin.

Q: Which coin had the highest negative score?

A: Ethereum had the highest negative score.

Q. Which coin had the highest positive score?

A: Both kinds had the same highest positive score.

#### Natural Language Processing

In this section, I will use NLTK and Python to tokenize the text for each coin. Be sure to:

1. Lowercase each word
2. Remove punctuation
3. Remove stop words

Finally, I'll generate word clouds for each coin to summarize the news for each coin.

![btc-word-cloud.png](Images/1.png)

![eth-word-cloud.png](Images/2.png)

#### Named Entity Recognition

In this section, you will build a named entity recognition model for both coins and visualize the tags using SpaCy.

![btc-ner.png](Images/3.png)

![eth-ner.png](Images/3.png)