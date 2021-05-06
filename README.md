# Data_Science_internship_Task-2 :

Task-2 : Prediction using Unsupervised ML.

Problem Statement : Using given 'Iris' dataset predict the optimum number of clusters & represent it visually.

Determining the optimal number of clusters in a data set is a fundamental issue in partitioning clustering, such as k-means clustering, which requires the user to specify the number of clusters k to be generated.

K-means algorithm :
 
      The algorithm tries to find groups by minimizing the distance between the observations, called local optimal solutions.
      
      The distances are measured based on the coordinates of the observations. For instance, in a two-dimensional space, the coordinates are simple.
      
The algorithm works as follow:

        Step 1: Choose groups in the feature plan randomly.
        Step 2: Minimize the distance between the cluster center and the different observations (centroid). It results in groups with observations.
        Step 3: Shift the initial centroid to the mean of the coordinates within a group.
        Step 4: Minimize the distance according to the new centroids. New boundaries are created. Thus, observations will move from one group to another.
        Repeat until no observation changes groups.     
