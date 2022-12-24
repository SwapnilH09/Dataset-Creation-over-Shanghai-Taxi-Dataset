# Dataset-Creation-over-Shanghai-Taxi-Dataset

### A mobile user experiences high latency issues as compared to a stationary user. This occurs due to higher physical distance between the user and the services running in the cloud. One solution to this is to deploy the applications near the user, so it takes minimum hops for the connection between user's device and the server location. 

### An algorithm using Reinforcement learning is trained and tested over <a href="https://www.researchgate.net/figure/Sample-raw-input-data-from-a-dataset-of-2-300-taxis-in-Shanghai-emitting-GPS-samples_fig1_254464339">Shanghai Taxi Dataset</a> which contains coordinates of all 2300 taxis running in Shanghai City on a particular day and location of all the edge tower locations in the city. 

### performed clustering over the dataset creating --
<ul type="A">
<li> clusters of edge towers around a mobile user whose position chnages with time (coordinate_edgeTower, coordinateDistance betwwen user's device \& edge tower) </li>
<li> clusters of users around an edge tower, with variable user-density over time </li>
</ul>

### metric used to calculate coordinate distance -- Haversine Distance

### tools -- Python, NumPy, Pandas
