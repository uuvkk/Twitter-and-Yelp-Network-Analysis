# Social Network Analysis of Yelp and Twi er Users in Urbana-Champaign Area
[Dandan Tao](https://github.com/DandanTao), Department of Food Science and Human Nutrition, University of Illinois at Urbana-Champaign

[Jiazheng Li](https://github.com/uuvkk), School of Information Sciences,  University of Illinois at Urbana-Champaign
## Abstract
Social similarity is critical in the formation of friendship. The purpose of this project is to test the well-established sociological hypothesis that people tend to be similar to their friends on social media. Yelp and Twitter were chosen as platforms to collect data for network analysis. Users’ following information on Twitter and reviewing profile on Yelp are used as main characteristics for calculating similarity. Group detection was conducted on Gephi using the Louvain method. Network properties of people grouped with different similarities were compared and the impact of node property on graph property were discussed. It was found that the similarity of users who are friends are much higher than users who are not friends on both Twitter and Yelp. Interest has significant impact on network properties.
## Keywords
Network analysis; Social media; Grouping; Node similarity
## Introduction
Similarity in network analysis occurs when two nodes fall in the same group. From sociological perspective, people tend to be more similar to their friends than to people who are not their friends [2]. With massive data generated online every day, social media has been employed as a useful tool to conduct varieties of researches. Analysis of similarity helps us to detect groups with speci c interests, which is bene cial for recommendation, advertising and so on [9, 13].
Yelp is one of the most popular online review websites in the world. Most of the previous studies on Yelp dataset are based on semantic analysis of Yelp reviews for the purpose of identifying the impact of fake reviews [6], analyzing consumer dietary habits [1], and predicting user attributes [8]. A few researches have been focused on the network aspect of Yelp dataset. Gender impact on Yelp friendship network was investigated based on network analysis method triangle motifs identi cation [12]. Personalized recommender systems were proposed based on relationship heterogeneity of the information network [9, 13].
Twitter is one of the mainstream online social networking platforms, which give the users great chances to follow and know the topics and persons that interest them. Studies on Twitter user data have been widely conducted, and applied for various purposes including spam detection in user networks [10], analyzing public sentiment toward U.S. presidential election in 2012 [11], and creating alerts for cybersecurity threats and vulnerabilities [7]. In terms of grouping, clustering and communities in Twitter networks, Twitter stream is studies to build real-time systems that can  nd hierarchical spatiotemporal hashtag clustering for event exploration [3], community structures in Twitter social network are analyzed to predict and explain prostate and breast cancer communities [4], and spatiotemporal clustering of Twitter data are also used to infer the locations of users [5].
Though Facebook and Twitter are the two dominant tools in the  eld of social media analysis, increasing amount of studies have been done on Yelp due to the open Dataset Challenge. Besides, Yelp is di erent with the two prevalent social media tools in that it’s more of a review website though it also provides social functions. To our best knowledge, there is no research applying network analysis to investigate similarity of users’s preferences on di erent platforms.
The goal of this project is to test the hypothesis on virtual relationships namely friendship on Yelp and Twitter. In speci c, three network-based research questions are raised: 1) how to determine similarity; 2) how to interpret grouping results based on similarity; and 3) how does similarity in uence friendship network? To answer these questions, methods including similarity computation, grouping and metrics analysis will be employed to gain insights of node similarity and the in uence on graph property.
