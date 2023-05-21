# Customer behaviour and value analysis and ml clustering
I attempt to understand customer behaviour patterns on an ecommerce sales dataset for better business strategies by using a variety of analysis methods including cohort analysis of purchase activity, RFM value analysis, and unsupervised machine learning.

### Cohort analysis
* Creating cohorts based on month of first purchase
* Organising data by cohort and month
* Analysing different metrics: Retention rate, Mean cohort order quantity, Mean cohort order price

### Recency, frequency, monetary value analysis
* Wrangled data to calculate metrics at the client level
* Recency (days since last purchase)
* Frequency (how many purchases in the last 12 months)
* Monetary value (How much spent in the last 12 months
* Assigning metric scores based on percentiles to analyse general behaviour
* Added product breadth metric

### Clustering
* Removal of outlier clients
* Transforming and scaling data
* Clustering with kmeans (Elbow method, SSE scores, silhouette scores)
* Business actions based on kmeans cluster analysis
* Clustering with density-based scan (Selection of min samples in a cluster, and distance where to pick neighbours)
* Business actions based on dbscan clusters analysis