# grouping_clustering_project

More details about project at: https://docs.google.com/presentation/d/1tKDKZt2Ru49Fp_Vj0Wk_K_CdQlfeCGS5VFl4IoQcZ5Y/edit?usp=sharing

The client is a plane ticket booking agency. They wanted for me to add value by automatically grouping user ticket searches/watches into “trips." 

A user "search / watch" is somebody saving a query like "trip Toronto to Amsterdam". There are many searches per user, and there are many users. So, there are many searches. The client wanted to group searches in a way that can enable business value. 

My Solution: A data product - a pipeline that assigns a grouping to each search / watch. The grouping is based on tiers that features (ex: price) of this search / watch fall under (ex: high vs low price). Discretization and K-Means algorithms are used to do the grouping / clustering.

Also, there is a prototype of how this grouping can be used to make recommendations.
