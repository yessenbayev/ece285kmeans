# KMeans Clustering in CUDA

The objective is to implement KMeans algorithm in CUDA.

##System Requirements
NVIDIA GPU with at least 5.2 CUDA compute capability 
CUDA 9.1

There are several branches of interest in this repository:
* **master** holds the version of the program that performs PCA on MNIST dataset and then clusters 3D embedding with k-means algorithm
* **randompointsnew** holds the version of the program that perform k-means clustering on 3 randomly generated clusters
* **implemented-paper-triangle-inequality...** holds the implementation of the triangle inequality optimization, which forces to terminate if it is guranteed that all points left for checking are further away than the last visited centroid.

To compile and run the solution please use CMake. 
1. Choose the root directory of this repository as a Source folder, and choose any folder for the Build folder
2. Open classlab.sln (with Visual Studio), which is located in the Build folder you have chosen
3. Choose a Startup project of interest by using the right-click menu
4. Run the **release** version without debug
