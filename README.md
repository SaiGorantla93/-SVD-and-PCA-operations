# SVD-and-PCA-operations
http://www.cs.uakron.edu/~duan/class/635/projects/project2/project2.html

Steps Followed in SVD:

Step1: Converted the ASCII image into Binary​

Step2: Stored the U ,V and singular values in binary format after eliminating the singular values using rank approximation​

Comparing the sizes of images obtained in step1 and 2 using the ROC​

Rate of Compression (ROC)=(Original Image size-Approx Image Size)/ Original Image size​

Getting the original Image back from step 1 and approximated image from step2​

​PCA:

Principal Component Analysis (PCA) is a dimension-reduction tool that can be used to reduce a large set of variables to a small set that still contains most of the information in the large set.​

Principal component analysis (PCA) is a mathematical procedure that transforms a number of (possibly) correlated variables into a (smaller) number of uncorrelated variables called principal components.​

The first principal component accounts for as much of the variability in the data as possible, and each succeeding component accounts for as much of the remaining variability as possible.​

PCA simply performs a coordinate rotation that aligns the transformed axes with the directions of maximum variance.​

PCA can help find underlying structure of the data. It selects a rotation such that most of the variability within the data set is represented in the first few dimensions of the rotated data.​

PCA tries to find a lower dimensional surface so the sum of squares onto that surface is minimized.​

PCA tries to find the surface which has the minimum projection error.​

​
