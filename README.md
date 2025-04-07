K-Means Clustering¶
the main concept of this algorithm is really simple.

Each point must belong to a cluster and each point can belong to only one cluster.

k-mean steps:
choosing K(Cluster number)

Randomly select K distinct data point.named them as our cluster points.

assing each remaining point to the nearest cluster points.

Calculate the center of the cluster points( mean value of each point vector).

assign each point to the nearest cluster center.

repeat steps 4 and 5 until there is no reassignment.

choosing K value:
how can we measure goodness of fit?

choose a random K( usually K=2)

Measure SSD(Square Sum of the distance)

then we fit an entirely new Kmeans model with K+1

then measure again the SSD for K+1

repeat
