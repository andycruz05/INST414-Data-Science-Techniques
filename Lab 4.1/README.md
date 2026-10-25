Main Exercise. Finding the most likely cluster given a particular genre

* Download movie_to_cluster.csvDownload movie_to_cluster.csv. This file contains all of the movies in the database and the cluster they were sorted into.
* Load the csv into Python as a dataframe
* Set your target genre as "Sci-Fi"
* Use a for loop to iterate through the clusters. For each one, calculate the probability that a new movie will fit in that cluster given that it is a Sci-Fi movie. In other words calculate P(Cluster | Sci-Fi)

* You should get the following output:
* Pr[Cluster 00 | Sci-Fi]: 	 0.17345971563981044
* Pr[Cluster 01 | Sci-Fi]: 	 0.040758293838862564
* Pr[Cluster 02 | Sci-Fi]: 	 0.20379146919431282
* Pr[Cluster 03 | Sci-Fi]: 	 0.02464454976303318
* Pr[Cluster 04 | Sci-Fi]: 	 0.05308056872037915
* Pr[Cluster 06 | Sci-Fi]: 	 0.061611374407582936
* Pr[Cluster 07 | Sci-Fi]: 	 0.0
* Pr[Cluster 08 | Sci-Fi]: 	 0.008530805687203791
* Pr[Cluster 09 | Sci-Fi]: 	 0.021800947867298578
* Pr[Cluster 10 | Sci-Fi]: 	 0.0009478672985781991
* Pr[Cluster 11 | Sci-Fi]: 	 0.047393364928909956
* Pr[Cluster 13 | Sci-Fi]: 	 0.013270142180094787
* Pr[Cluster 14 | Sci-Fi]: 	 0.03033175355450237
* Pr[Cluster 15 | Sci-Fi]: 	 0.13175355450236967
* Repeat steps 3 and 4 for the genres "Fantasy" and "Adventure"
