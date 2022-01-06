In this task, we are required to predict the location where the pictures were taken based on the given dataset.

Generally, Our solution include 2 steps:
* Find the closest pictures in the training set using SIFT and RANSAC
* Find the distance from the traning and the test picture using Multiple-View Geometry

Furthermore, corner cases, especially when the SIFT points can not be found, were dealt with histogram plot and color matching.

# Result
In Kaggle, our predictions ranked top 30% among 200+ participants and got full mark on coding.
![Kaggle Result](LeaderBoard_Result_60in215.PNG?raw=true)
