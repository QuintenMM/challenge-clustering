### clustering to find different faults in bearings
We'll be using a dataset that consist of different features relating to bearings. we'll be clusingtering tha faulty bearings to find a pattern in them.

# Data Analysis
we have 113 rows of faulty and non faulty bearings.
we have 48 features consisting of:


these features are applied to:

## Data cleaning
we clean the data first before creating clusters.
- removed the working bearings
- droped following columns because they had to much influence and interfered. This was decided after testing).
-  impulse
-  RMQ_F
-  RV_F
-  hert


the features where put into combinations of 2. this would later be used to cross reference them againts each other to find the best combinations.

the data was normalised and scaled. 

## Data Analysis

first I calculated the silhoutte score to see how accurate it could create clusters and with what features. 

after understanding all the data i used the best features to plot them in a silhoutte plot.
- to see the distributian
![bearing_65_score.png](https://github.com/QuintenMM/challenge-clustering/blob/eeeb74cee4f4bb103373b8fa58c9355738543d1d/bearing_65_score.png)


![Screenshot from 2021-08-12 07-46-47.png](https://github.com/QuintenMM/challenge-clustering/blob/eeeb74cee4f4bb103373b8fa58c9355738543d1d/Screenshot%20from%202021-08-12%2007-46-47.png)

![Screenshot from 2021-08-12 07-37-56.png](https://github.com/QuintenMM/challenge-clustering/blob/eeeb74cee4f4bb103373b8fa58c9355738543d1d/Screenshot%20from%202021-08-12%2007-37-56.png)

- to see the accuracy 
- to see the elbowplot 






