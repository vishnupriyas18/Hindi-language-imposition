#SENTIMENT ANALYSIS OF HINDI LANGUAGE IMPOSITION

[This](https://colab.research.google.com/drive/1QNsxkfUtzE_l3xPUDLjGijRwG8roG-gK) is the code for sentiment analysis of hindi language imposition.

##Problem statement

Perform sentiment analysis of hindi language imposition in India using tweets.

##My approach

I performed rule based analysis of twitter data to achieve the purpose. Rule based analysis is performs sentiment analysis based on a set of manually crafted rules. These rules identifies things such as subjectivity and polarity by using a lexicon. A lexicon is a dictionary of set of positive and negative opinion words and expressions with their associated polarity scores. A basic example of a rule based method would be to define two lists of polarized words for both negative and positive polarity words. Then given a text, count the scores of both positive and negative words. If we have a more positive score, then it is a positive text and if we have a more negative text, then it is a negative word. If both scores are equal, then the text is neutral.

##Algorithm

* Install required libraries
* Import the installed libraries
* Define Twitter API Authentication Variables
* Authenticate with Twitter
* Find tweets related to Hindi Language Imposition
* Go through the tweets to analyze their sentiment.
* Print the result
* Interpret the obtained data using a pie chart.

##Tools used

* Google Colaboratory
* Python framework
* Pandas, Twython, Vadersentiment libraries
* Twitter application

##Conclusion

Majority of people have neutral sentiment towards Hindi language imposition. Precisely, 85.72% people have neutral sentiment towards Hindi Language Imposition followed by 8.17% people with negative sentiment and 6.11% people with positive sentiment.

##Acknowledgements

Thank you Google for providing me a place to code and providing me with resources for the task. Thank you Twtter for giving me a developer account for this project. Thank you Python, Pandas, Twython, Vadersentiment for helping me perform sentiment analysis. Thank atom text editor for containing my README file. Thank microsoft excel for giving me the required pie chart. I would like to thank the admins of the whatsapp group for providing me with hints when required. I would to give my special vote of thanks to my family and friends, especially my mom for supporting me throughout this entire project. Thank you all for being there.
