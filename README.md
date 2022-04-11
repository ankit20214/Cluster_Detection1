# Cluster_Detection1

(1) Ensured that duplicate latitude, longitude and timestamps are not appended.
(To check for duplicates it is broken down in a manner that, timestamp should be unique, thereafter if either the lat or long is unique we append the data to the dictionary (considering the case maybe where only the lat/long changes during movement)
(2) When the cluster is detected, create a JSON that contains vehicle_id, the centroid of the latitudinal and longitudinal positions recorded while detecting the cluster, and the timestamp at which the cluster was detected. (For finding centroid just calculated the mean of the coordinates)

