# SEGMENTATION AND EDA OF CLASS PLUS GMV DATA SET

Primary Objective:
The objective of this case study is to analyse this data and come up with insights, highlighting the good things, bad things, cohorts of patterns found or cohorts of customers you can classify.
Approaches: 
To segment the creators, I have used RFM scores along with clustering techniques such as K means++ and DB Scan. Although best clusters of k-means++ were not able to separate our best creators from rest so I focused more on DB Scan and the results are satisfying.
Key Findings
From Basic Stats:
•	People those are here for a long time, are producing more videos. So this platform must be doing good for them.

•	Number of GMV per month also increasing so people must be getting benefit.

•	Watch per video is increasing on total but the mean and median are not increasing rather its declining which could have adverse effect on the creators since they are increasing their contents and they must be investing more on there quality of production if watch doesn’t increase then it may cause them disappointment. Reason must be viewers now have more options, but we should bring more customers as well.

•	Courses seems to be live classes or have access period less than month. If business model doesn’t allow to sell recorded contents, then we should encourage them to produce more frequently.

•	Top 20 Content creators must be having big studious and large man powers since the number of contents produced per month are quite high in number. Reason must be obvious it’s a B2B ED Tech company.
	From DB SCAN
•	1 cluster separated by DB scan produces 99.2 % of total GMV and 96.17 % of videos but they are consisting of only % of total population. They have all the best creators from RFM segmentation. So, I consider them as the most important cluster to be focused on. 

•	Another cluster consisting 59.82% people don’t contribute to even .7 % of profit. Surprisingly there is one new high earning creator is among them so we can talk to him, and some potential creators to improve their level

•	And rest of the 2% Falls in between these two clusters.

From RFM Segmentation
Using RFM scores 5 segments 

•	(B Creator) Best Creators

•	(HSN Creator) High - Earning New Creators

•	(LSAL Creator) Lowest-Profitable Active Loyal Creators (At Risk creator)

•	(P Creators) Potential creators

•	(Cb Creator) Churned Best creators

 

I’ve defined them briefly below. Here 2 LSAL creators with us for a long time they are even in DB scan’s important cluster but there GMV are not high or possibly their price of sell is high. We should communicate with them. 

*Detailed analysis is in Report file or I urge one to have a look into attached jupyter notebook file
