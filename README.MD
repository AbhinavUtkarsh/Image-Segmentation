## Image segmentation by K-Means Clustering

### Project Report

### Digital Image Processing (CS1553) 

# Problem Statement

##### This Project has an analysis of K-Means Clustering

##### on MRI scans to segment the tumor.

##### Implementation on Google Collab.

```
https://colab.research.google.com/drive/1ZxnCKDQrWmD4Y_fOdRed9wcM7yViVqTi
```
# Program in Brief
```
The program performs K-means clustering on images. The steps involved in K-means clustering are:

Choosing the Number of Clusters: The user specifies the number of clusters which determines how the image will be segmented.

Initialization of Centroids: Centroids are initialized. The program runs the initialization 40 times (n_init=40) and selects the best one.

Assign Pixels to Centroids: Every pixel in the image is assigned to its nearest centroid based on its color value.

Re-compute Centroids: After all pixels have been assigned to clusters, the centroids of the clusters are recalculated based on the average color values of the pixels in the cluster.

Reassignment and Iteration: Pixels are reassigned to the new nearest centroid. If any reassignment happens, the centroids are recalculated. This process iterates until centroids do not change between iterations or a maximum of 500 iterations (max_iter=500) is reached.
```
##### Note: The program saves the newly generated images in the PWD.

# Results
![Results](https://abhinavutkarsh728.s3.amazonaws.com/14%3A38%3A48+C_4.png)
![Results](https://abhinavutkarsh728.s3.amazonaws.com/14%3A38%3A48+C_3.png)
![Results](https://abhinavutkarsh728.s3.amazonaws.com/Unknown.png)




##### Details

This project report and file have been submitted by Mr. Abhinav Utkarsh

Date: 26 Nov 2019

Subject: Digital Image Processing


Steps to run the included code:

There are 3 ways to run the code

	1) Install Python and run the .py file with the images to be segmented in the same working directory as of the Python file. The output would be stored at the same PWD.

	2) Or simply use the Google Collab. link provided with project report and add it to your own Google colab instance. 
   		NOTE: You need to upload the images to collab. after every tab close.

	3) you could also install jupyter notebook and take it to the PWD of.ipynb with the images already there following simply with the code execution.
