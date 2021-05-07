# accenture_interview

For Technical Team==================

Below are the given Suggestions for the task as part of improvements.

1. Negative and positive sentiment can be created into two different input files and sentiment analysis can be done on top of these files to analyse the severity of the sentiment.
2. Further more continuous updates can be done to training set for new jargons for sentiments. any shortcuts which are used frequently by genx should be considered.
3. there should be training set for mixed reviews to understand different types.

Code
=====
there are two different endpoints created in python code using flask.
1. enpoint1 take the input in the form of paragraphs and returns a json object which. contains the sentiment.
2. endpoint2 takes the input in the form of sentences from the paragraph and returns a json object which contains the sentiment, either of these enpoints can be
called individually to extract the sentiment.

