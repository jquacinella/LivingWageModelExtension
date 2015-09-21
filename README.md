# Master's Thesis github Page

## Proposal

I'm interested in how to model how bad / false information travels through social media, and if there is any way to categorize conversations into 'rumorous' or 'non-rumorous'. There are two projects, Truthy and Pheme, that are working in this general area. I need to read more of their research, but this paper sparked my interest (http://www.pheme.eu/wp-content/uploads/2015/02/ai4cities-rumours.pdf), specifically:

>In order to create social media rumour datasets, we propose an alternative way of manually annotating rumours 
> by reading through the timeline of tweets related to an event and selecting stories that meet the 
> characteristics of a rumour ... The creation of both rumour and non-rumour datasets will allow us to train 
> machine learning classifiers to assist with the identification of rumours in new events, by distinguishing the
> characteristics of threads that spark conversation from rumour-bearing ones"

I'm hoping to get a hold of their manually annotated data to see if I can use the features of the tweets to detect rumor bearing convos via a machine learning model. I'd also like to look to see:

  * if features regarding any links in the tweets help the model accuracy (article title + text, article topic, article source, etc)
  * if features regarding the metadata of the twitter users in the convo (can we use an api to find bot users? low quality tweets for some definition of quality?)

## Status

In proposal phase
