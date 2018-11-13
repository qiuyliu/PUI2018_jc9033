
# Homework 8
Individual work by Junjie Cai<br>

# Assignment 1: Review classmates' plots
Reviewd plots from Guanjia Wang(gw1054) and Rufei Sheng(rs6431) from the aspects of CLARITY, ESTHETIC, HONESTY and etc.<br>

## Assignment 2: exercises with linear regression using statsmodels

1. create a line with a chosen slope and intercept = 0 and plot it with uncertainties as errorbars

2. print y, x, and the result of applying statsmodels.api.add_constant() to x

3. use statsmodels.api.OLS to fit x and y
        a. the wrong way: by passing x as exogenous variable
        b. the right way: by passing statsmodels.api.add_constant(x) as exogenous variable

and print the model summary for each and discuss the differences

4. plot the data (as points) and both statsmodels fits

5. create a line with a chosen slope and a chosen intercept >=100*slope and plot it with uncertainties as errorbars

6. repeat step 3

7. now fit the data with WLS weighted least square, a linear fit that takes into account the uncertainties by "down-weighting" (considering less important) observations with large uncertainties

## Assignment 3: investigate linear relationships between fire arm possession, homicides by fire arms, and mass shootings for different countries, considering also the country GDP

#### 1  DATA:

#### 2  exploration

2.1  plot mass shooting vs gdp in absolute numbers, and per person. Show the errorbars (y errors)

2.2  plot the average number of civilian fire arms per person

2.3  plot the average number of homicide by fire arms per person

2.4  plot the number of homicides by fire arm against the number of civilian firearms. plot the US in a different color

2.5  plot the number of mass shootings against the number of civilian firearms. plot the US in a different color

#### 3  Modeling

3.1  fit a line to the Number of mass shootings per person as a function of Average total all civilian firearms per person.

3.2  Outlier removal:

3.3  Extra credit: calculate the confidence interval by hand and also plot them

3.4  Use the stsatsmodels.gaphics package to plot the influence plot.

3.5  Extra credit: calculate from scratch the stanrdardized residuals and the H leverage for the WLS model and discuss if there are any differences

3.6  Discuss your findings
