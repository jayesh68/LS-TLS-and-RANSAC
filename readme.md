<div align="center">
<h1>Estimation of the parabolic trajectory of a ball using Least Squares, Total Least Squares & RANSAC</h1>
</div>

LS, TLS and RANSAC are techniques to data fitting techniques which find the best ways to reprent the data in a system as a whole. Ordinary Leasr Sqaures (OLS) is used to estimate the unknown parameters in a model by minimizing the sum of the squares of the differences between the observed dependent variable in a dataset and those predicted by the linear function of the independent variable. Total Least Squares (TLS) is a technique in which observational errors on both dependent and independent variables are taken into account. RANSAC is used to estimate parameters of a model often using a from a set of observed data that contains both inliers and outliers. This would consist of eliminating the outliers based on a stanard method such as OLS by using it to estimate the number of data points which can be classified as inliers or outliers. Therefore, it also can be interpreted as an outlier detection and rejection method. 

 ### Input Videos showing the trajectory of a ball
<p float="left">
<img src="https://github.com/jayesh68/LS-TLS-and-RANSAC/blob/main/Ball_travel_10fps.gif" width="500" height="500" />
<img src="https://github.com/jayesh68/LS-TLS-and-RANSAC/blob/main/Ball_travel_2_updated.gif" width="500" height="500" />
</p>

### Output Plots showing the trajectory
<img src="https://github.com/jayesh68/LS-TLS-and-RANSAC/blob/main/Output_Plots.png" />
