## This Model Determines Customers' Segmentation.


#### This made use of the Kmeans Clustering algorithm whilst factoring in a dataframe of targeted column base comprising of the gender, age, annual income 
#### and spending score of individual customer .


#### It becomes pertinent to observe that the sample dataframe has got no labels as this makes a case for an unspervised learning algorithimic approach.


#### A range of values (X) had to be generated, seconded by a range of different clusters sequel to deciphering the SILHOUTTE score - a factor which validates
#### the consistency of data clusters.



#### The WCSS(within clusters sum of squares) takes into account the sum of squared distance beween each point and the centroid froma range of values.
#### This springs forth an Elbow point graph at 5 on the horizontal(Number of clusters) axis.
#### Also note the the values of WCSS decreased with corresponding increase in the values of K.
#### The clusters are then plotted along with their centroids and yields a 5 pointer clustering in consonance with the Elbow point graph.



#### In order to assert  double assuance on the profound 5 cluster hypothesis, a code sample is lifted from https://scikit-learn.org/stable/auto_examples/cluster/plot_kmeans_silhouette_analysis.html wherein the aformentioned range of (X) values are incorporated to further factor in the Silhouette theory which endorses the given K value as corresponding silhouette value approachs 1.



#### From the plots that followed, it could be easily pointed out that the Silhouette anaysis for KMeans clustering on sample data wth n_clusters = 3, 4 and 5 gave positive values,  so 5 seemed the choicest value for K because it's the biggest of all 3 and the biggest number always creats a generallized model.



#### Since K = 5 , it means that there are basicaly 5 different categories of customers.
