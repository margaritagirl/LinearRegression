# LinearRegression

Simple linear Regression

A simple linear regression asuumes a linear relationship between an input variable X and an output variable Y The value of Y is depended on the value of X, Hence Y is the dependent variable X is the independent variable Mathematically 'linear relationship' can be reresented by 'linear equation' such as

Y=mX+b

Formula to find m and b (using least square method)

m=NΣ(xy)−ΣxΣyNΣ(x2)−(Σx)2

b=(Σy−mΣx)N

If you are curious about the derivation of these formulas,I recommend reading https://nptel.ac.in/content/storage2/courses/122104019/numerical-analysis/Rathish-kumar/least-square/r1.htm

The basic idea is when we have scatterred data, we try to find a curve that best fits the data, by figuring out the best fit line. Now which line would be the best fit? The line which lies as close to the scattered data points in the most optimum way.

This is a python program with the linear regression implementation using scikitlearn package.
The dataset that I have used is from here
https://www.ncdc.noaa.gov/data-access/land-based-station-data/land-based-datasets/world-war-ii-era-data

we wre using the miminum temperature on a day to predict the maximum temperature.
