# Sentiment_Analysis_NLP
The sentiment related to a name or object is analysed.
## Table of contents
* [General info](#general-info)
* [Libraries used](#Libraries-used)
* [Things done](#Things-done)
* [Result](#Result)

### General info
Sentiment analysis is a natural language processing technique used to determine whether data is positive, negative or neutral. 

Sentiment analysis basically studies the subjective information in an expression, that is, the opinions, emotions, appraisals, or attitude towards a topic, person or entity. 
### Libraries used
* Pandas for dataframe manipulations.
* Matplotlib for data visualization.
* Nltk and textblob for text analysis.
* Re for regular expressions
* Tweepy for extracting tweets from Twitter API.
### Things done
* scraping data from social media websites.

After creating a twitter developer account, we should obtain the credentials.

* The tweepy library for extracting tweets from twitter API.
tweepy would authorise whether we have the right API.After extaracting the tweets the tweets are converted to text and changed to dataframe

* How to clean the textual data.

we use the regularexpressions which is very important for the text analysis.

we use replace the nonalphabet charactewrs and replaqce them with space. Next the numbers are removed from the text. Then all the words are converted to lower case.
* Lemmatization
* 
It is the process of converting a word to its base form. for example the word better is converted to good which is its base form.


* Removing stop words
* 
stop words are the words that donot add much value to sentences.They can be safely ignored without sacrifacing the meaning of the sentence. eg: the, he, she.
using the library textblob we can obtain the polarity from the function sentiment. Polarity is the expressionthat determine the sentimental aspect of an opinion. it can be positive negative or neutral. polarity lies between -1 to +1.

### Result

