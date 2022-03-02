<div align="center">
<h1>Estimation of the parabolic trajectory of a ball using Least Squares, Total Least Squares & RANSAC</h1>
</div>

LS, TLS and RANSAC are techniques to data fitting techniques which find the best ways to reprent the data in a system as a whole. Ordinary Leasr Sqaures (OLS) is used to estimate the unknown parameters in a model by minimizing the sum of the squares of the differences between the observed dependent variable in a dataset and those predicted by the linear function of the independent variable. Total Least Squares (TLS) is a technique in which observational errors on both dependent and independent variables are taken into account. RANSAC is used to estimate parameters of a model often using a from a set of observed data that contains both inliers and outliers. This would consist of eliminating the outliers based on a stanard method such as OLS by using it to estimate the number of data points which can be classified as inliers or outliers. Therefore, it also can be interpreted as an outlier detection and rejection method. 

 ### Input Videos showing the trajectory of a ball
<p float="left">
<img src="https://github.com/jayesh68/LS-TLS-and-RANSAC/blob/main/Ball_travel_10fps.gif" width="450" height="450" />
<img src="https://github.com/jayesh68/LS-TLS-and-RANSAC/blob/main/Ball_travel_2_updated.gif" width="450" height="450" />
</p>

### Output Plots showing the trajectory
<img src="https://github.com/jayesh68/LS-TLS-and-RANSAC/blob/main/Output_Plots.png" />

### Analysis
Based on the above plots the following conclusions can be made.
1. The LS and TLS plots try to cover almost all the points in the for video 2 whereas RANSAC ignores some points as outliers and covers only those which are inliers.
2. TLS performs better than OLS as it looks to minimize the error for both the dependant and the independent variable.
3. The other advantage of using RANSAC is the function runs a certain number of times till it finds the best fit which are consistent with an estimated model (in this case the least squares model). The model with the maximum number of inlier points is chosen as the best fit model.

### Instructions to run the code
1. HW1_P2.py consists of the code to run the least squares, TLS and RANSAC method. This would create 2 subplots for the two videos with all the 3 methods being plotted for each video.
2. The command to run the program is $python3 HW1_P2.py.
