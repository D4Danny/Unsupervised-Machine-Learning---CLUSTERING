# Unsupervised-Machine-Learning---CLUSTERING
<a title="Chire, CC BY-SA 3.0 &lt;https://creativecommons.org/licenses/by-sa/3.0&gt;, via Wikimedia Commons" href="https://commons.wikimedia.org/wiki/File:EM-Gaussian-data.svg"><img width="256" alt="EM-Gaussian-data" src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d8/EM-Gaussian-data.svg/256px-EM-Gaussian-data.svg.png" ></a>

Cluster Analysis (“data segmentation”) is an exploratory method for identifying homogenous groups (“clusters”) of records.
Similar records should belong to the same Cluster. Dissimilar records should belong to different clusters. 
CLUSTERING = GROUPING “Similar” things together!

### 1. [Hierarchical Clustering](#HC)
### 2. [K-Means Clustering](#KM)
### 3. [DBSCAN Clustering](#DC)


### BUSINESS CASE: 
#### Scenario 1. EAST WEST AIRLINE DATASET
East West Airlines has provided information on passengers who belong to an airline’s frequent flier program. For each passenger the data include information on their mileage history and on different ways they accrued or spent miles in the last year. The goal is to try to identify clusters of passengers that have similar characteristics for the purpose of targeting different segments for different types of mileage offers.

#### Scenario 2. US CRIME RATE DATASET
Perform Clustering(Hierarchical, Kmeans & DBSCAN) for the crime data and identify the number of clusters formed and draw inferences.

Data Description:
Murder -- Muder rates in different places of United States
Assualt- Assualt rate in different places of United States
UrbanPop - urban population in different places of United States
Rape - Rape rate in different places of United States



### 1. Hierarchical Clustering <a name="HC"></a>

Hierarchical cluster analysis  is an unsupervised clustering algorithm that merge similar data points together into groups called Clusters.
#### Similarity is seen between TWO DATA POINTS
#### Similarity is seen between CLUSTERS.
The above method is called Agglomerative or Bottom-Up.

### Scenario 1 [Hierarchical clustering with East-West Airline](https://github.com/D4Danny/Hierarchical-Clustering-for-Airline/blob/main/Hierarchical%20Clustering%20for%20East%20West%20Airline.ipynb)

### Scenario 2 [Hierarchical clustering with US Crime RATE](https://github.com/D4Danny/Hierarchical-Clustering-for-US-Crime-Rate/blob/main/Hierarchical%20Clustering%20for%20US%20Crime%20Data.ipynb)


#### Clustering of Data based on their homogenous characteristics





### 2. K-Means Clustering <a name="KM"></a>
K MEANS clustering analysis  is also known as Non-Hierarchical Clustering that pre-determined number (K) of Non overlapping clusters.
Clusters are homogeneous, yet dissimilar to other clusters. 
Need measures of Within-Cluster similarity (homogeneity) and Between-Cluster similarity.
#### K-Means clustering is useful for large datasets.

### Scenario 1 [K-Means with East-West Airline](https://github.com/D4Danny/K-Means-Clustering-for-Airline/blob/main/K%20Mean%20Clustering%20for%20East%20West%20Airline.ipynb)

### Scenario 2 [K-Means clustering with US Crime RATE](https://github.com/D4Danny/K-Means-Clustering-for-US-Crime-Rate/blob/main/K%20Mean%20Clustering%20for%20US%20Crime%20Data.ipynb)


#### Initialize K cluster centers and Obtain CENTROIDS 


### 3. Density-Based Spatial Clustering Application with Noise (DBSCAN) Clustering <a name="DC"></a>
DBSCAN is a density based clustering method that discovers clusters of Non-spherical shape. The DBSCAN clustering method can represent clusters of arbitrary shape and to handle noise. It groups together points with a dense neighbourhood into clusters.

#### A point will be considered as crowded if it has too many other neighbours points near it. DBSCAN finds this these crowded points and places them and their neighbours in a cluster.


### Scenario 1 [DBSCAN with East-West Airline](https://github.com/D4Danny/DBSCAN-Clustering-for-Airline/blob/main/DBSCAN%20Clustering%20for%20East%20West%20Airline.ipynb)

### Scenario 2 [DBSCAN clustering with US Crime RATE](https://github.com/D4Danny/DBSCAN-Clustering-for-US-Crime-Rate/blob/main/DBSCAN%20Clustering%20for%20US%20Crime%20data.ipynb)


#### DBSCAN alogorithm requires TWO parameters: 1) EPS and 2) MinPts. 
It has 3 types of data-Points:
#### 1. Core Point
#### 2. Border Point
#### 3. Noise or Outlier


