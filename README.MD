## “Image segmentation by KNN Algorithm„

### Project Report

### Digital Image Processing (CS1553) 

# Problem Statement

##### This Project has an analysis of K - Nearest Neighbor Algorithm

##### on MRI scans to segment the tumour.

##### Implementation on: Google Collab.

```
https://colab.research.google.com/drive/1ZxnCKDQrWmD4Y_fOdRed9wcM7yViVqTi
```
# Program in Brief
```
The Number Program initially asks for the number of clusters to be selected in the K-NN algorithm. Obviously more the clusters more the number of segmented parts in the image.
So the steps Involved in K-NN algorithm:
1) Choosing the number of Clusters
2) Selecting at random K points for centroid, in our case 40 was passed as the number of
neighbors.
3) Assigning each Data point as we say each pixel value closest to the above centroid that
further gives us clusters.
4) Now we compute and place the new centroid for each cluster.
5) On the last step we just do the reassignment of the new nearest centroid and if in any case any new reassignment took place we would reiterate the above process.
```
##### Note: The program saves the newly generated images in the PWD.

# Results
![Results](https://abhinavutkarsh728.s3.amazonaws.com/14%3A38%3A48+C_4.png)
![Results](https://abhinavutkarsh728.s3.amazonaws.com/14%3A38%3A48+C_3.png)
![Results](https://abhinavutkarsh728.s3.amazonaws.com/Unknown.png)




##### Details

This project report and file has been submitted by Mr. Abhinav Utkarsh

Date: 26 Nov 2019

Subject: Digital Image processing


Steps to run the included code:

There are 3 ways to run the code

	1) Install python and run the .py file with the images to be segemented in the same working directory as of the python file. The output would be stored at the same PWD.

	2) Or simply use the Google Collab. link provided with project report and add it to your own google colab instance. 
   		NOTE: You need to upload the images to collab. after every tab close.

	3) you could also install jupyter notebook and take it to the PWD of.ipynb with the images already there following simply with the code execution.