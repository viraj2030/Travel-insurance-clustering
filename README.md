# Travel-insurance-clustering

### What this project is about
This project uses unsupervised machine learning clusters travel insurance data in order to perform targeted marketing when selling Travel Insurance. I have then created a Power BI dashboard to visualise the insights.


​

### Initial exploratory analysis

 - 16 Agency types with EPX appearing most frequently

 - 26 Product types with Cancellation plan being the most frequent

 - The average duration is ~50 hours

 - The most common place to travel to is Singapore

 - The average age of the policy holder is ~40

 - Majority of the top 20 destinations to get travel insurance for are in Asia

​

### Results and Power BI dashboard 
Using principle component analysis to reduce the feature space, I was able to use 4 components to explain ~75% of the total variance. This is a huge reduction from the original 53 features. This also improved the silhouette score which I used as a model evaluation technique. I chose to use 2 clusters which gave me a silhouette score of 0.488


### Insight about the different clusters to use for marketing  
##### LETS FOCUS ON CLUSTER 0 
Cluster 0 customers are more likely to travel to the far east (Singapore, Malaysia, Thailand, China, Indonesia etc.)

Cluster 0 customers are more likely claim

Cluster 0 customers are more likely to use a travel agency over an airline agency 

Cluster 0 customers are more likely to use online distribution channels 

Cluster 0 customers are typically younger than cluster 1 customers 

Cluster 0 customers are more likely have deals which are cheaper than cluster 1 and also better value (less commission is earned on these deals)

Cluster 0 customers are more likely to travel less hours compared to cluster 
