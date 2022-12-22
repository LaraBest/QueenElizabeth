# QueenElizabeth
Analysing the perceptions of Queen Elizabeth's death among twitter users over time 

## introduction 
- short overview of the research 
- research question, case, method, what the rest of the site contains (the different sections), main conclusion 

## Queen Elizabeth's Death
- setting up the case - what happened, what other people have analysed (news articles etc)
- why is this research relevant - what is our objective - relevance of looking at the issue over time 
- similar papers (others using computational content analysis methods to analyse social media after someone died/perceptions of a famous person etc) 

## method 

**1.  Selection of time periods and extraction of tweets using minet.** To answer our research question, we decided to extract tweets over the course of the month of September, to see how, in each week, perceptions of the Queen’s death changed. To ensure our datasets included enough tweets for a comprehensive analysis, we selected three days for each week of September per dataset. We decided to extract four discrete datasets to be able to create independent network maps and topic models of their tweets, and to determine whether the number of tweets on the topic of the Queen’s death changed over time, which would be illustrated in the size of the datasets. The starting day of the data collection is the 8th of September – the day Queen Elizabeth’s death was made public. Another notable day during the collection period is September 19th, the day of the Queen’s funeral. Although the date is not included in a dataset, we expected it to influence the tweets of the nearby weeks. We extracted the tweets from twitter using the query “Queen Elizabeth death lang:en until:2022-9-10 since:2022-09-08”, changing the dates as corresponding with our selected time periods. 

![image](https://user-images.githubusercontent.com/115983335/209151929-9e155c57-6a6b-4d13-8f5f-0ec231235ab5.png)

**2.	Dataset uploading to CorText and parsing**

**3.	Use of the Terms Extractor function** to create a list of the 100 most frequent terms from the ‘text’ of the tweets from each dataset. This produced four separate ‘keyword’ lists. 

**4.	Use of List Builder function** to create lists of the 100 most frequent terms for each dataset (from the previous step) and allowed for the cleaning of the lists to remove instances of repetition and uninformative terms. 

**5.	The Corpus Terms Indexer function** was then used to index each dataset with its corresponding terms list. 

**6.	The Topic Modelling function** was then used to create a topic model from the ‘text’ of the tweets of each dataset. The function was limited to assigning one topic per tweet to avoid over-complicating the interpretation as the text in the tweets is very short.

**7.	Finally, we used the Network Mapping function** to create heterogeneous networks maps for each dataset using the indexed 100 most frequent terms lists as the nodes. 


## results - comparing over time
### week 1
- put in the top keyword list + map for each week 
- analysis of what the results of each week are, but here not comparing them to one another
### week 2
### week 3
### week 4

## Discussion - limitations
- could have had a bigger dataset 
- language limitation - only looked at tweets in english 
- only looking at the discussion on twitter, where many users are passive (only liking and sharing), not at newspapers or other social media where people might express their thoughts/opinions differently 
- maybe think of something else - the example papers only had 2 or 3 and they didn't seem to be that deep 

## Conclusion/discussion
### synthesis of results
- compare the results of the different weeks between one another -> answer the research question 
- differences between the weeks 
- similarities 
- what stood out as notable 
- what can we conclude about evolution over time 
- ... despite our limitations our main conclusions is x 
