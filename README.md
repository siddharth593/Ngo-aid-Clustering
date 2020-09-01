We received the data from **Help International NGO** that works for providing aid in countries which are in dire need of
Aid, Since the funding, is limited the CEO wants us to analyze and determine the top countries for priority Aid. Our Analysis
starts with the basic step i.e reading data, cleaning it, checking if data is incorrect form then we moved on to the EDA
part where we did Univariate analysis and detected the outliers in all the columns, we handled them by capping
upper and lower limits. After that, we analyzed the heatmap and found the top correlation in variables.
After checking the clustering tendency by Hopkins test we moved on to the model building. The first step is to scale the data
(‘we used standard scaling’). When scaling is done we are ready for our first model i.e K-means. For K-means finding
the number of clusters i.e. k is must for further analysis, we did that by analyzing Elbow curve(SSD) and Silhouette
Analysis. After visualizing the clusters formed we found the cluster of countries that are in dire need of Aid. For
Finding the top 10 countries we filter the data by cluster we want, then sort them by ‘child_mort’, ‘gdpp’, ‘income’ as
descending, ascending, ascending respectively hence we got the top 10 countries.
Second, we build the Hierarchical model, single linkage cluster formation wasn’t good so we built a complete linkage
model. On analyzing the dendrogram we finalized on the number of clusters i.e. ‘k’. We did the same visualization as we did for
K-means found the cluster then filtered the data and sorted the data by the same method. Hence we got the top
countries that are in dire need of Aid. Which concluded our Assignment after reporting those countries.
As for which clustering produced the best results, in my case, both methods resulted in the same top 10 countries. While they
produced the same results I would say that Hierarchical Clustering produced better result process was fast since data is
not big and choosing the number of cluster ‘k’ is also straight forward by looking at dendrogram. So Hierarchical
Clustering produced better results for my analysis approach.