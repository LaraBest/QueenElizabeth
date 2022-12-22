# Public perceptions of the death of Queen Elizabeth II
Analysing the perceptions of Queen Elizabeth's death among twitter users over time 

*By Lara Best-Dunkley, Carolina Bergstein, Benjamin Garcia*

## Introduction 
September 8, 2022 marks the death of Queen Elizabeth II. Four months ago, the Queen passed away at the age of 96, after a reign over the United Kingdom and the Commonwealth realms for almost 70 years. Indeed, a few months earlier, the queen had celebrated her platinum jubilee marking this exceptional duration. To be interested in the Queen is to be interested in a contemporary figure, while at the same time being interested in a historical figure. She has known and worked with a great number of figures while being an important actor herself. She was probably also one of the most famous people on the planet, everyone knew Queen Elizabeth II. 
Indeed, her reign marks the beginning of the real media coverage of the English royal family, and this is also what is interesting and what made this family so famous, in addition to the colonial empire founded by the United Kingdom, which extended over a large number of territories and populations. For example, the coronation of Queen Elizabeth II was the first to be broadcast live on television and was watched by the majority of the British people. Thus, we thought it would be interesting to analyze the live reactions around her death, on the social network Twitter. 
	The reign of Elizabeth II is also a controversial one: between the death of Princess Diana in 1997, the affair of Meghan and Harry with the Megxit, the sulfurous affairs of her son Andrew that seem to have been covered up, and especially the colonial empire, we wondered if this would have an impact on the reactions to her death.
Thus, we necessarily expected at first sight empathetic reactions to the death of the queen in relation to the respect of a deceased person, but we wanted to know if these controversial matters for the queen would emerge again at her death, when the review on the life of this historical figure would be realized, and what would be the reaction of the Twitter users. In addition, we wondered if Twitter users from the former colonies of the United Kingdom, and the left part of the United Kingdom, would bring out these discussions again.
This is why we asked ourselves: 
how did perceptions of the queen's death change over time? 
We had some hypotheses, notably that over time the interpretations of the death became more focused on the queen’s colonial legacy, while in the beginning the topics/sentiments would be more focused on mourning and her positive legacy.

# Plan :
1. Case Info/Literature
2. Methodology
3. Results per week
4. Synthesis and comparisons
5. Limitations
6. Conclusion

## Queen Elizabeth's Death
- setting up the case - what happened, what other people have analysed (news articles etc)
- why is this research relevant - what is our objective - relevance of looking at the issue over time 
- similar papers (others using computational content analysis methods to analyse social media after someone died/perceptions of a famous person etc) 

## Method 


**1.  Selection of time periods and extraction of tweets using minet.** To answer our research question, we decided to extract tweets over the course of the month of September, to see how, in each week, perceptions of the Queen’s death changed. To ensure our datasets included enough tweets for a comprehensive analysis, we selected three days for each week of September per dataset. We decided to extract four discrete datasets to be able to create independent network maps and topic models of their tweets, and to determine whether the number of tweets on the topic of the Queen’s death changed over time, which would be illustrated in the size of the datasets. The starting day of the data collection is the 8th of September – the day Queen Elizabeth’s death was made public. Another notable day during the collection period is September 19th, the day of the Queen’s funeral. Although the date is not included in a dataset, we expected it to influence the tweets of the nearby weeks. We extracted the tweets from twitter using the query “Queen Elizabeth death lang:en until:2022-9-10 since:2022-09-08”, changing the dates as corresponding with our selected time periods. 

![image](https://user-images.githubusercontent.com/115983335/209151929-9e155c57-6a6b-4d13-8f5f-0ec231235ab5.png)

**2.	Dataset uploading to CorText and parsing**

**3.	Use of the Terms Extractor function** to create a list of the 100 most frequent terms from the ‘text’ of the tweets from each dataset. This produced four separate ‘keyword’ lists. 

**4.	Use of List Builder function** to create lists of the 100 most frequent terms for each dataset (from the previous step) and allowed for the cleaning of the lists to remove instances of repetition and uninformative terms. 

**5.	The Corpus Terms Indexer function** was then used to index each dataset with its corresponding terms list. 

**6.	The Topic Modelling function** was then used to create a topic model from the ‘text’ of the tweets of each dataset. The function was limited to assigning one topic per tweet to avoid over-complicating the interpretation as the text in the tweets is very short.

**7.	Finally, we used the Network Mapping function** to create heterogeneous networks maps for each dataset using the indexed 100 most frequent terms lists as the nodes. 



## Results 


### Week 1

***Topic Modelling***

The online visualisation of the topic model for the week 1 dataset can be accessed [here](https://documents.cortext.net/8382/83828dae10c1edb22c6703956e2e8a45/322114/vislda.html)


| Top 10 Topics |
| ------------- |
| 1_queenelizabeth_peopl_like_one_make |
| 4_majesti_famili_royal_condol_sadden |
| 7_king_charl_iii_follow_leagu |
| 10_world_tribut_mourn_news_leader |
|  5_follow_day_mourn_london_septemb |
| 6_palac_buckingham_age_96_announc |
| 8_peac_rest_may_life_god |
| 3_mourn_react_live_via_britain |
| 2_-2_—_»_«_statement_presid |
| 9_wish_flag_excruci_professor_pain |


The topic modelling for Dataset 1, which includes tweets from the first three days after Queen Elizabeth’s death, present quite predictable results. The topics mainly revolve around twitter users presenting their condolences for the Queen’s death (see topic 4, topic 10), as well as their mourning and sadness over the announcement (see topic 10, topic 3). There is also a prominence of wishing that the Queen shall rest in peace (topic 8). This was present also from an international dimension, as many topics included the names of foreign leaders who had made public statements on the Queen’s death (see topic 2) – “world” was also the 6th most salient term in dataset.  Interestingly, instead of Elizabeth or Queen being the most salient terms, “king” and “Charl” (referring to Charles, the new King of the United Kingdom) were the most salient. This would suggest that twitter users perceived the shift of power after the Queen’s death to the new King as very important. Finally, topic 9 shows discussion among twitter users on a tweet by a Carnegie Mellon professor Uju Anya, whereby she wished the Queen an “excruciating death”. The original tweet and the heated debate which followed its release, also evidenced by this topic model, demonstrate the divided perceptions of twitter users on the topic of Queen Elizabeth’s death, already in the first days after it happened. 


***Network model***

The interactive version of the network map can be accessed [here](https://documents.cortext.net/lib/mapexplorer/explorerjs.html?file=https://assets.cortext.net/docs/28b8b62116561fb97e2a44dc3c99aeca)


| Top 10 most frequent terms | Stem |	Main form |	Forms |
| -------- | ------ | ------ | ----- |
| 1 |	british throne |	British throne |	British throne |
| 2 |	address charl iii	 | Charles III addresses	| Charles III addresses |
| 3	| elizabeth news queen	| news of Queen Elizabeth	| news of Queen Elizabeth & News of Queen Elizabeth & Queen Elizabeth News & News Queen Elizabeth & news about Queen Elizabeth & news Queen Elizabeth | 
| 4	| canada queen	| Queen of Canada	| Queen of Canada |
| 5	| alexandra elizabeth mari |	Elizabeth Alexandra Mary	| Elizabeth Alexandra Mary |
| 6	| bezo jeff	| Jeff Bezos	| Jeff Bezos |
| 7	| uk world	| UK and world |	UK and world |
| 8	| age death |	death at the age | death at the age & death aged & death age & death at age |
| 9	| britain great	| Great Britain	| Great Britain |
| 10 |	kate middleton	| Kate Middleton |	Kate Middleton |


The network map based on the top 100 most frequent terms in the tweets shows similar patters as the topic model for Week 1. This is shown by the three largest clusters in the network model, which are closely tied together with lots of short edges, meaning the terms are closely associated in tweets. The three topics include 1. Various expressions of condolence and sadness (blue), 2. References to the importance and significance of this “moment in history” meaning the shifting of power to King Charles (orange) and 3. Mentions of other members of the royal family. The network map also demonstrates the divided nature of the discussion about the Queen’s death, as contentious issues arise alongside the condolences. In the dark blue cluster, the term “kohinoor diamond” references the highly valuable diamond is a part of the Queen’s crown (taken from India during the imperial era), which has caused debate over whether it should be returned to India. Similarly, the Uju Anya tweet also makes an appearance in a small dark red cluster. However, both of the more critical clusters are completely disconnected from the clusters on condolences, which may suggest that these conversations were occurring separate from each other on twitter. 


![week1network](https://user-images.githubusercontent.com/115983335/209161325-aa3c91ec-a38b-406b-9c5a-4cf300096abc.png)



### Week 2


***Topic modelling***


The online visualisation of the topic model for the week 2 dataset can be accessed [here](https://documents.cortext.net/2f6b/2f6bb8a057216cecb4aa34dab2982267/322217/vislda.html)


| Top 10 Topics |
| -------------- |
| 1_queenelizabeth_one_like_via_news |
| 4_septemb_majesti_monday_close_respect |
| 6_british_—_»_«_chang |
| 5_uk_follow_mourn_nation_john |
| 3_princ_tribut_harri_william_memori |
| 9_king_charl_iii_day_royal |
| 2_royal_famili_children_feel_loss |
| 7_condol_peopl_british_express_unit |
| 8_commonwealth_mourn_mark_princ_follow |
| 10_wish_royal_professor_call_world |


In the second week, the topics were very consistently about mourning both among the royal family (see topic 4, topic 2) and the British nation (see topic 5). Lots of the most salient terms included terms referring to expressing loss and sorrow and about the royal family. Still, week 2 included topic 10, which has many terms referencing the Uju Anya tweet and Britain’s history of colonialism more broadly. For instance, topic 10 includes the terms “Africa”, “exploit”, “steal” and “pain”, all which seem to refer to Britain’s colonial history. 


***Network model***


The interactive version of the network map can be accessed [here](https://documents.cortext.net/lib/mapexplorer/explorerjs.html?file=https://assets.cortext.net/docs/64098d00ab2e03194a3943a1272df577)


| Top 10 most frequent terms |	Stem |	Main form |	Forms |
| -------------------------- | ------ | --------- | ------ |
| 1 |	bandmat pistol sex |	Sex Pistols bandmates |	Sex Pistols bandmates |
| 2 |	follow jewel queen |	Jewels Following Queen |	Jewels Following Queen |
| 3	| africa britain south |	South Africa for Britain |	South Africa for Britain |
| 4	| kingdom street unit |	streets of the United Kingdom |	streets of the United Kingdom |
| 5	| elizabeth queen visit |	Visit Queen Elizabeth |	Visit Queen Elizabeth |
| 6	| return world	| return the world	| return the world |
| 7	| anya prof uju |	Prof Uju Anya |	Prof Uju Anya |
| 8	|china ignor imperi |	Imperialism While Ignoring China |	Imperialism While Ignoring China |
| 9	| ferguson sarah |	Sarah Ferguson |	Sarah Ferguson |
| 10	| carnegi mellon professor |	Carnegie Mellon Professor	| Carnegie Mellon Professor |


The network map of the top 100 most frequent terms highlights the prominence of perceptions of the linkages between Queen Elizabeth II and Britain’s colonial legacy, with many related terms showing up on the Top 10 list and featuring often in the most important clusters. Although grief and condolences still show up as having an important role in twitter discussions in the second week, topics of the UK’s imperial past and justice for it were very present in conversation and were interlinked with the grief-based discussions. 


![week2network](https://user-images.githubusercontent.com/115983335/209164577-624c7ea0-5418-4c61-9eb5-823dc6bc528c.png)



### Week 3


***Topic modelling***


The online visualisation of the topic model for the week 3 dataset can be accessed [here](https://documents.cortext.net/d958/d9588e2358c91a4736fb127478236bdc/322218/vislda.html)  


| Top 10 Topics |
| --------------- |
| 5_royal_famili_mourn_media_king |
| 3_last_william_princ_name_kate |
| 8_follow_countri_peopl_call_say |
| 7_world_us_peopl_mourn_follow |
| 10_day_age_majesti_mark_follow |
| 4_princ_harri_say_predict_simpson |
| 2_—_»_«_predict_king |
| 9_tribut_pass_caus_come_australian |
| 1_here_read_know_british_die |
| 6_hour_street_vandal_statu_target |


The topic modelling of week 3 produced varying results. The topics mainly consisted of terms referencing Britain’s colonial history and slave trade as well as how the Simpsons animated television show seemingly ‘predicted’ Queen Elizabeth’s death (see topic 2, topic 4). Mentions of condolences and mourning vis a vis the British royal family still came up as salient in the topic modelling but has a visibly lower frequency than in previous weeks (see topic 5, topic 3). Another prominent feature in Dataset 3 was the salience of terms referring to Britain’s colonisation of Australia and their subsequent treatment of indigenous peoples (see topic 6). 


***Network model***


The interactive version of the network map can be accessed [here](https://documents.cortext.net/lib/mapexplorer/explorerjs.html?file=https://assets.cortext.net/docs/94fee01f0aae7b03edd22f1da7a31f24)


| Top 10 most frequent terms |	Stem  |	Main form	| Forms |
| ------------- | --------- | ---------- | --------- | 
| 1	| albanes anthoni minist |	Minister Anthony Albanese	| Minister Anthony Albanese |
| 2	| death follow queen |	death following Queen |	death following Queen |
| 3 |	coloni legaci	| legacy of colonialism |	legacy of colonialism |
| 4	| cybercrimin death use |	cybercriminals use the death	| cybercriminals use the death |
| 5	| content note	| contents of note	| contents of note & contents of the note |
| 6 |	elizabeth news queen	| news of Queen Elizabeth	| news of Queen Elizabeth & news about Queen Elizabeth |
| 7	| crown fact jewel	| fact that the Crown Jewels |	fact that the Crown Jewels |
| 8	| famou street wall	| Famous Wall Street	| Famous Wall Street |
| 9	| elizabeth hour queen	| Queen Elizabeth hours	| Queen Elizabeth hours |
| 10	| statu street wall	| Wall Street statue |	Wall Street statue |


The network map for week 3 shows some familiar themes about condolences for the Queen’s death and about the legacies of British colonialism. However, the focus of the top 100 most frequent terms in this dataset and their interlinkages focus significantly more on people in the British royal family and the different royal estates than on colonial legacy, as was the case with this dataset’s topic model. The network model still shows some shared edges between “graffiti targeting queen” (which references the Australian case, as in the topic model) with the more general large yellow cluster on members of the royal family. 


![week3network](https://user-images.githubusercontent.com/115983335/209165049-3a7d73a2-8e62-4865-a3c4-0af584623578.png)


### Week 4

***Topic modelling***

The online visualisation of the topic model for the week 4 dataset can be accessed [here](https://documents.cortext.net/d28b/d28b83963c504c8d19b47810ea70a669/322219/vislda.html)

 
| Top 10 Topics |
| --------------- |
| 2_old_age_die_certif_say |
| 4_reveal_caus_via_certif_news |
| 6_caus_certif_confirm_releas_old |
| 10_offici_caus_releas_“old_age” |
| 5_follow_meghan_uk_markl_hm |
| 7_scotland_record_nation_thursday_8 |
| 8_princ_harri_public_windsor_castl |
| 3_die_new_day_famili_certif |
| 1_royal_famili_certif_week_reveal |
| 9_—_»_«_nation_reason |


Notably, the tweets in the fourth and final week of analysis after Queen Elizabeth’s death focus on her cause of death and her old age. This makes sense, as on the first day of data collection for Dataset 4, the Queen’s death certificate was released. The topics in this week centre thus on the contents of the death certificate and how news agencies interpreted its significance. Differing from the previous weeks, the most salient terms in week 4 did not include as many references to sadness and condolences about the Queen’s death, rather the most salient terms discussed “old age” as the Queen was 96 when she died. The terms “age”, “old” and “die” featured in the top five most salient terms of the entire dataset. 


***Network model***


The interactive version of the network map can be accessed [here](https://documents.cortext.net/lib/mapexplorer/explorerjs.html?file=https://assets.cortext.net/docs/354d8238578481c1990114c250544476)


| Top 10 most frequent terms |	Stem |	Main form |	Forms |
| ---- | ----- | ------ | ------ |
| 1	| releas scotland |	Scotland Releases |	Scotland Releases & Scotland released & Scotland releases |
| 2	| longest monarch reign |	longest reigning monarch |	longest reigning monarch |
| 3	| age http old |	old age https |	old age https & Old Age https |
| 4	| archiv nation scotland |	National Archives of Scotland |	National Archives of Scotland |
| 5	| elizabeth hour queen |	hours after Queen Elizabeth |	hours after Queen Elizabeth |
| 6 |	fox news |	Fox News |	Fox News & Fox news |
| 7	| elizabeth queen |	Queen Elizabeth	| Queen Elizabeth & queen elizabeth & queen Elizabeth & QUEEN ELIZABETH & ELIZABETH QUEEN |
| 8	| balmor castl |	Balmoral Castle |	Balmoral Castle |
| 9	| death list time |	listed time of death	| listed time of death |
| 10 |	8th septemb |	September 8th |	September 8th & 8th September |


The outcome of the network model for week 4 strongly supports the findings of the topic model. The large, central, blue cluster includes terms relating to the release of the official death certificate, and every other cluster has edges connecting to it. This demonstrates that the death certificate played a central role in the twitter conversation over the course of these days. The other clusters have terms which link quite clearly to the Queen’s death with the orange cluster having many terms referring to the time of death and neighbouring (and overlapping) yellow one focusing on Scotland and Balmoral, where the Queen died. Notably, this network map has no references to Britain’s colonial legacy, but for the first time the isolation caused by Covid 19 is present in the network, in a small and distant cluster in the top left corner, which still links to the death certificate/cause of death of Queen Elizabeth. 

![week4network](https://user-images.githubusercontent.com/115983335/209165257-79a77b41-8438-4417-9003-a8606ea9d348.png)


## Discussion - limitations
First of all, we did not fully observe what we thought we were observing. Indeed, we see mostly messages of sadness and condolences about the death of the queen. 
A first limitation to our research is perhaps the query we have done that has restricted us on the number of tweets. Indeed, we have focused on the search ""Queen Elizabeth death lang:en"" at several given dates. Thus, we only had the tweets that had all the words "Queen Elizabeth Death", which removes the tweets with only "Queen Elizabeth" or "Queen death". Contrary to the large number of tweets we expected, we sometimes got only a few thousand tweets. For example, between the 22nd and the 24th, we had only 1,013 tweets when the funeral had taken place on the 19th. Similarly, in the days leading up to the funeral (between the 15th and 17th), we had just under 5,000 tweets. Thus, this limits our analysis as to what we wanted to observe. Furthermore, the English language is also a limitation in itself since we do not have access to tweets from other countries that may be less warm towards the Queen, such as tweets in Indian or Swahili, which may be much more critical of the Queen and the empire they have suffered.
Then, it would have been interesting to have a wider search such as "Queen OR Elizabeth AND death OR legacy" which would have allowed us to widen our search, and to learn a little more about the idea that twitter has of Elizabeth II's legacy. We could also have analyzed the ratio of comments to likes to see what is really controversial, to see what brings discussion, more than tweets liked on the death of the queen that are only condolences. Also, we only looked at the discussion on twitter, where many users are passive (only liking and sharing), not at newspapers or other social media where people might express their thoughts/opinions differently.
Furthermore, on the evolution over time, we analyzed only 3 days over the one month period following the death of the queen. Although we have already observed evolutions on these periods, it might have been interesting to retrieve and analyze tweets on larger periods but later in time like 2 weeks in November, and 2 weeks in December. Thus, it could be interesting since there are always twists and turns regarding the royal family, especially right now with the release of the documentary Meghan and Harry which gathered almost 2.4 million people for the first episode on the first day of its broadcast on Netflix, December 8, 2022. 
Finally, we could also merge our different datasets to have a global analysis of all the collected tweets, which we could compare with each separate week. 

## Conclusion/discussion
### synthesis of results
- compare the results of the different weeks between one another -> answer the research question 
- differences between the weeks 
- similarities 
- what stood out as notable 
- what can we conclude about evolution over time 
- ... despite our limitations our main conclusions is x 
