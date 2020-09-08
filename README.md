# kMeans
k means algorithm from scratch

I have implement a function to calculate the k-means clustering of a dataframe of 'm' observations with 'n' attributes.

The implementation function has the signature:
```bash
    cluster_kmeans(df, k)
```  
where
    
 ```bash
    df is a Pandas dataframe of m observations with n attributes; m rows with n columns (excluding index;
    the index will contain the label for each observation and is not considered an attribute)
    
    k is the number of clusters to find
```
## Output
The function should return a new dataframe with a single column: the cluster label for each observation. It should also return the last Sum-of-the-Square-Errors (SSE) from the clustering.

For the proximity measure, Euclidean distance is used as the metric.  Sum-of-the-Square-Errors is the objective function.
