# NLP Homework

In this homework, I have performed sentiment analysis and natural language processing on Bitcoin and Ethereum from news articles pulled from newsapi.  For the sentiment analysis a polarity score was calculated for each news article using the Vader Sentiment Analysis from the NLTK library.  For the natural language processing, the text was tokenized for each coin using the NLTK library.  After tokenization bigram and single word frequencies was calculated.  Next, a word cloud was constructed for each coin to illustrate the most common words found in the news articles.  Finally, a named entity recognition model was built for both coins and the tags were visualized using SpaCy.

## Sentiment Analysis

Bitcoin had a slightly higher mean positive score over Ethereum.  Bitcoin's score was 0.06825 to Ethereum's 0.06085.  Ethereum had the highest single negative score at 0.237 versus Bitcoin's highest negative score of 0.168.  Bitcoin had the highest single positive score of 0.184 compared to Ethereum's highest positive score of 0.143.  In general, Bitcoin seems to have a more positive sentiment in comparision to Ethereum.


## Natural Language Processing

By far the most apparent words in Bitcoin's articles were bitcoin, nakaboto, satoshi, robot, and colleague.  Not sure there is much to take from this particular NLP analysis.  For Ethereum, some of the most common words in news articles were bitcoin, ethereum, blockchain, cryptocurrency, and today.
Once again I don't think any of these words hold too much individual significance in our analysis. 

For both coins, there were a variety of different named entities that would require additional analysis to determine their overall importance to the sentiment of the coins.  I think furthur research into this area could be promising.  
