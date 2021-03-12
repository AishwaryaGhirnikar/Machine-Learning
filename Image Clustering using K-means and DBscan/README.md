# Image Clustering using K-means and DBscan

**Introduction**

* **Clustering** is one of the most common exploratory data analysis techniques that are used to obtain an intuition about the structure of the data. It is the task of identifying sub-groups in the data such that data points in the same sub-group (cluster) are very similar while data points in different clusters are very different. In other words, we try to find homogeneous clusters within the data such that data points in each cluster are as similar as possible, with respect to a similarity measure such as euclidean-based distance or correlation-based distance. The decision of which similarity measure to use is application-specific.

![image](https://user-images.githubusercontent.com/62713812/110926625-a7257300-834a-11eb-9816-99f26334143b.png)

1) **k-means Clustering:** 
It is an unsupervised learning technique that is used when we have unlabelled data. The main goal of this algorithm is to divide the data points in a data set into different categories or groups. The data points are grouped together based on their similarities. k-means tries to partition the data set into k-clusters using an objective function.

![image](https://user-images.githubusercontent.com/62713812/110926716-c15f5100-834a-11eb-805a-e2399a4ef866.png)

* **k-means Clustering Algorithm**
 1) Choose the value of ‘k’, i.e no.of clusters that are to be formed for a given data set.
 2) Randomly select ‘k’ data points from the data set as the initial cluster centroids.
 3) For each data item in the data set, compute the distance between the data points and the cluster centroids.
 4) Assign the data points to the closest centroids and update the centroids by recomputing them with new data points.
 5) Repeat steps 3 and 4 for all the data points in the data set.

* **Image Clustering using k-means clustering**

  Let’s understand k-means clustering with the help of an image classification use case. The steps involved in image classification are:
1) The images that are to be classified are imported and converted into arrays.
2) Clusters are created. The clusters appear in the resulting image, distinctly dividing the image into a number of parts.
3) The number of clusters can be changed to visually validate the image with different colours and decide what closely matches with the required number of clusters.
4) Once the clusters are formed, we can recreate the image with the cluster centres and labels to display the image with grouped patterns.


