# Live-Twitter-Sentiment-Analysis

Why Sentiment Analysis ?
Millions of messages are appearing daily in popular web-sites that provide services for microblogging such as Twitter, Tumblr, Facebook. Authors of those messages write about their life, share opinions on variety of topics and discuss current issues. Because of a free format of messages and an easy accessibility
of microblogging platforms, Internet users tend to shift from traditional communication tools (such as traditional blogs or mails) to microblogging services. As more and more users post about products and services they use, or express their political and religious views, microblogging web-sites become valuable sources of people’s opinions and sentiments. Such data can be efficiently used
for marketing or social studies.
"This is sample project to analyze sentiments based on particular subject"
We would like to add Facebook Sentiment Analysis based on text and also emotiocon as of now only twitter sentiment analysis available.


"How Does it Work?"

We use tweepy to authenticate with twitter and get tweets from twitter as json response. we parse tweets and analyze 
tweets using TextBlob [ NLTK library] and append the sentiment result to file twitter-out.txt

We analyze twitter-out.txt in liveTwitterGraph module and using matplotlib graph the live Stream.

"How to Run ?""
You need to create your own twitter appilication on twitter dev website .
Get your own Access and access secret token , consumer and consumer secert token and make changes to the code.
Now,
You can clone and run twitterStreamgit.py , liveTwitterGraph.py in python . 



You need to install first these python libraries
pip install tweepy
pip install TextBlob

Use of code is lincensed under MIT Lincense

 


