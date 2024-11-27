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


