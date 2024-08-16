# k-means
&emsp; This was machine learning 3rd assignment, implementing k-means clustering algorithm. Here we implemented and applied k-means clustering for these two different examples:<br/>
### 1. image color clustering:<br/>
&emsp; First we read the image and then we store all its data (RGB data) into a dataframe. Then we performed k-means clustering on it. Then for each record of dataset, we replaced 
that point's color with the thats point centroid. Somehow we put these records in 3D dimension (for example you can imagine it as this: r(red) as x, g(green) as y and b(blue) as z in 3D dimension). Then we calcuated its 
euclidean distance (in our 3D dimention example) for them with their centroids. Then as the clustering algorithm goes, they gets into the clusters and we replaced their centroids with them and then we showed 
the result image and saved it.<br/>
### 2. point clustering:<br/>
&emsp; We simply implemented k-means clustering algorithm for the provided poins in the dataset. And we applied k-means with different vaules for k and plot the result.
