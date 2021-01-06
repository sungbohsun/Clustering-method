# Clustering-method
```
Project 3 - Clustering
Instructions 
●	You will need the following clustering algorithms for this project: 
Clustering algorithm  
K-Means
Hierarchical clustering
DBSCAN
 
●	Visually explore the data sets in all experiments by considering the following characteristics of the data. This exploration will help you understand the data and answer the questions. 
o	Types of attributes 
o	Class distribution 
o	Which attributes, if any, appear to be good predictors of the cluster structure 
o	Possible correlation between attributes 
o	Any special structure in the attributes that you might observe 
 
●	Compile your answers in the form of a PPT report.










Problem 1 
Dataset to be used in this experiment: Ecoli_v2 
This is a modification of the e-coli UCI dataset that contains 8 attributes and 4 classes. The classes are protein localization sites in the E-coli bacteria: site1, site2, site3, and site4, which have to be discovered using clustering. The objective of this problem is to become familiar with various clustering techniques. Load the dataset and visualize the data. 
1.	Perform the following set of experiments. 
a.	Perform K-means clustering with K = 4. Report the confusion matrix and the entropy. Comment on the quality of this clustering based on your analysis of the confusion matrix and entropy. Which classes are easily separable from others and which classes are mostly confused?  
b.	Perform K-means clustering with K = 3. What changes did you notice in the confusion matrix and entropy of the overall clustering? Based on these observations, what can you comment on site2, site3, and site4 classes?  
c.	 Plot the SSE (Sum of Squared Errors) as the number of clusters varies from 2 to 10. Describe the behavior of this plot in a sentence or two.  
 
2.	Use the ‘HierarchicalClusterer’ clustering approach to find 3 and 4 clusters. Make sure to set the ‘linkType’ property of this method to ‘AVERAGE’. Report the confusion matrix and the entropy. Also, answer the following questions: 
a.	Comment on the quality of this clustering based on your analysis of the confusion matrix and entropy. Which classes are confused?  
b.	Based on these observations, how does ‘HierarchicalClusterer’ differ from K-means? Which property of the data may cause this effect? 
  





Problem 2 
Datasets to be used in this experiment: 
1)	p2data1  
2)	p2data2  
3)	p2data3 
In all these dataset, there are 5 classes of points, three of which form clusters and two of which are noise. Load the p2data1, p2data2 and p2data3 data sets and visualize them. 
1.	Use the DBSCAN clustering approach to cluster the points in all the three data sets with the following settings:  epsilon-neighborhood = 0.05, minPoints (Minimum number of data points) = 4. Report the confusion matrix and the corresponding entropy for each run. Comment on how the entropy compares among the three datasets. What characteristic difference(s) between the data sets lead to this variation in entropy? Explain in detail. 
2.	Use the DBSCAN clustering approach to cluster the points in all the three data sets with the following settings: epsilon-neighborhood = 0.1, minPoints = 4. Report the confusion matrix	 and the corresponding entropy for each run. Comment on how the entropy varies comparing with the results from part 1 as Epsilon increases, and briefly explain. 
3.	Based on your observations in dealing with datasets above which involved noise, and varying density, what conclusions can you make about the behavior of hierarchical clustering and DBSCAN? Please limit your answer to this question to no more than a page. 
 
```
