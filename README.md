# Data Scientist Take Home Exercise 

This exercise consists of 2 parts:
1. Statistics: Use crime dataset to understand the determinants of crime and to generate policy suggestions that are applicable to local government.
2. Machine Learning: Use news dataset to build a model to help classify news posts into different topics. 

**NOTE**
1. This exercise is meant to understand your approach and your analysis than the actual performance of your models.  You are advised not to spend more than a few hours on this exercise. 
2. Please use R or Python or both for this exercise.


## 1. Statistics

The file ```crime.csv``` is a dataset of crime statistics for a selection of counties.  Your task is to examine the data to help a campaign understand the determinants of crime and generate policy suggestions to local government to reduce crime.

|variable | description  |
|---------|--------------|
|county|county identifier|
|year|1988|
|crime|crimes committed per person|
|probarr |‘probability’ of arrest|
|probconv |‘probability’ of conviction|
|probsen |‘probability’ of prison sentence|
|avgsen|avg. sentence, days|
|police|police per capita|
|density |people per sq. mile|
|tax|tax revenue per capita|
|west|=1 if in western part of the state|
|central |=1 if in central part of the state|
|urban |=1 if in Standard Metropolitan Statistical Area| 
|wagecon |weekly wage, construction|
|wagetrd |weekly wage, wholesle, retail trade|
|wageser |weekly wage, service industry|
|wagemfg |weekly wage, manufacturing|
|wageloc |weekly wage, local government employees|

Please prepare an analysis investigating the determinants of crime and addressing the concerns of the political campaign.  Please provide the data analysis, model specifications and your policy suggestions. 


## 2. Machine Learning

The file ```news.json``` is a dataset of newsgroup postings on a variety of topics.  Your task is to distinguish the posts between the topics based on the text of the posts.

|variable | description  |
|---------|--------------|
|news_category|topic of the news post|
|news_text|body of the news post|

Please explain 3 algorithms that you could use to solve this problem but you are only asked to model one of them.  Please provide the model source code and basic comment of the source code.



