# Sentiment_Analysis
Sentiment Analysis, also known as opinion mining, is a subfield of Natural Language Processing (NLP) that builds systems to identify and extract subjective information from text. This can involve determining whether a piece of writing is positive, negative, or neutral.

Here’s why we do sentiment analysis:

Business Intelligence: Companies often use sentiment analysis to understand customer opinions about their products or services. This can help them identify areas for improvement, monitor changes in customer sentiment over time, and respond to customer concerns.
Social Media Monitoring: Sentiment analysis can be used to monitor social media platforms for public opinion about different topics. This can be useful for things like brand management, public relations, and market research.
Political Analysis: In politics, sentiment analysis can be used to track public opinion about different issues, candidates, or policies. This can help politicians understand public sentiment and adjust their strategies accordingly.

#This is the sentiment analysis of tweets .

sentiment_analysis1 code uses the live tweets and to get the live tweets , we need API keys and access_tokens. We need to create a developer account in twitter or X .
After creating developer account , create twitter app in that account , so that it generates API keys and access_tokens .
Paste that API keys and access_tokens in this code to perform sentiment_analysis .
#NOTE#: YOU SHOULD HAVE BASIC OR PRO ACCESS LEVELS IN DEVELOPER ACCOUNTS TO GET THIS CODE EXECUTED .

sentiment_analysis2 code does not use any API keys but we have to give the tweets manually , and we use a model called 'roberta' which was pre trained by META . So we get that model using transformers package and we take help of that model in performing sentiment_analysis.
