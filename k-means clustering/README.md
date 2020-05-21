# K-Means Clustering

## Goal:
Segment and group the pixels of a given image according to their RGB values with k-means. 

## Libraries used:
1. sklearn.cluster
2. PIL
3. numpy
4. matplotlib

## Pseudocode:
1. Import image
2. Convert to RGB
3. Run k-means from sklearn
4. Convert back to 8 bit values
5. Flatten the labels array
6. Convert all pixels to the color of the centroids
7. Reshape back to the original image dimension

K = 3
![k-means3](https://github.com/OlhaMaslova/AI_assignments/blob/master/k-means%20clustering/kmeans-3.png)

K = 6
![k-means6](https://github.com/OlhaMaslova/AI_assignments/blob/master/k-means%20clustering/kmeans-6.png)

K = 12
![k-means12](https://github.com/OlhaMaslova/AI_assignments/blob/master/k-means%20clustering/kmeans-12.png)

K = 18
![k-means18](https://github.com/OlhaMaslova/AI_assignments/blob/master/k-means%20clustering/kmeans-18.png)
