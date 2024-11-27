# Starbucks-Customer-Segmentation
Customer segmentation for Starbucks reward program members on the basis of their reactions to offers, to further assist marketing team design marketing strategies accordingly

+ **ML Techniques used :** K-Means, PCA, t-SNE, Gaussian Mixture Models, Silhouette plot, SSE/Inertia, Cluster Analysis

+ **Project Domains :** Market Segmentation, Marketing, Data Science, Cluster Analysis

**Q Why segment customers ???**

Ans - Well, because it is still a very difficult and computationally intensive task to target each customer in unique ways, as well as there would be lots of customers on which similar Marketing strategies and Discount offers would work well. Hence it makes intutive sense to break the customer base into clusters on the basis of how and which offers they react to and then proceed to make targeted strategies.

# If I had a minute to tell u about this project -
+ Coffee, Business, Marketing, Data Science , Action !

+ Performed Data Engineering to merge the 3 datasets, performed Data Cleaning (Some enteries were errors cause their data was missing as well as age was 118 which seemed to be an error). (coe)

+ Used Power Transforms to make dataset more gaussian since K-means likes rounder (isotropic) clusters.

+ Performed PCA ( Principal Component Analysis ) to reduce Data Dimensionality and avoid Curse of Dimensionality , and also so that redundant features would be removed and the data would be in continuous so that we don't need to bother ourselves with K-Prototype kind of algorithms ( its K-means plus K-mode for mixed (continuous plus categorical) data modelling )

+ Used K-means clustering to form clusters, along with Silhouette score and SSE(Sum of Squared Errors)/Inertia to determine optimal number of clusters, and then Silhouette Plots to further analyse quality of clusters.
+ Visualized Clusters in 2-D using t-SNE to further confirm the feasiblity of clusters.
  
+ Performed Gaussian Mixture Modelling since it is a Generative and not Discriminative classifier, also it's a soft classifier, to allow further scope for data-points on borders of clusters or customers which behave like 2 or more clusters. Also it can form "non-round" clusters better too.
  
+ Performed Cluster Analysis to determine properties and behaviours of clusters, understood the physical significance of the clusters in real life, and went ahead to think of how the company should make different strategies for these clusters.

+ Studied present Starbucks site to see their presently deployed marketing strategies for a new customer. Developed Product Understanding and understanding of UI/UX for marketing used by them.

# My findings

+ One cluster resembled people who were probably young office going people who were our regular customers, this is the customer segment which provides us the most monetary value currently. They react well to all offers, since they are regulars they already know the ins-and-outs of our schemes and hence use offers regularly. In my opinion, we can leave them as it is going, or even reduce the number of offers given to them slightly as long as they don't seem to be running away from us.
  
+ Another cluster had a lot of Rich, older members of reward program who usually react to discounts but not to BOGO's (Buy One Get One). A clear indication is that they like to drink coffee alone, and we can give them more discount offers than anything which requires them to buy more than one food item, and specifically not give them a BOGO offer.
  
+ Another customer segment was behaving in such a way that they only come to Starbucks when there is an offer (Us bhai us) , and their non-offer period spending is very low. I feel that by giving them small but regular offers on weekends, we can convert them to regular customers.
  
+ Another cluster resembled lower-income groups which did not seemed to be tempted by any type of offers. Either starbucks can introduce lower cost drinks to target these, or it can maintain its brand image and ignore these customers. Since India is a price sensitive market, to thrive in such a market it wouldn't hurt much to introduce a few "Mid-Priced" meals targetting middle class customers, and then slowly introducing combo-meals where we can sell a mid-priced and high priced item together in the name of discount.

+ One cluster had people who are moderate customers, with an okayish amount of spend, and I feel it is best to leave them as it is, and give them offers only when their frequency seems to have decreased.

+ The last cluster had no appreciable features, some of them were "ghosts" who had come only once or twice, and had very irregular patterns. Which , is a gentle remainder that all things which make sense mathematically do not have to make business sense .


