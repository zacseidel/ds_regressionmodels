# ds_regressionmodels

#Regression Models Notes

## Week 1


## Week 3
### Multiple Variable Regression Analysis
 - Example: do breath mints cause lung cancer?
 - Takeaway - Linear models get you most of the way to a best practice / optional solution
 - Linear Models are the single most important applied statistical and machine learning technique, by far:
 - Decompose a signal into it's harmonics (e.g. a music sound)
 - Flexibly fit complicated functions
 - Uncover complex multivariable 

## Multivariable Regression Examples
 - Require(datasets); data(swiss)
 - require(ggally) for pairs plot


## Swirl Notes

###  Introduction
 - Starting point is "Regression toward the Mean", a concept created by Francis Galton by studying the heights of parents and children
 - Data is from John Verzani's website, http://wiener.math.csi.cuny.edu/UsingR/
 - plot(child ~ parent, galton)
 - plot(jitter(child,4) ~ parent,galton)
 - regrline <- lm(child ~ parent, galton)
 - abline(regrline, lwd = 3, col = 'red')
 - summary(regrline)
 
 ### Residuals
  - mean(fit$residuals)
  - cov(fit$residuals, galton$parent)
  - all.equal(vector1, vector2)
  - variance(data) = variance(estimate) + variance(residuals) -> shows that the variance of the estimate is always less than the variance of the data
  
  ### Least Squares Estimates
   - regression line contains the point that is the mean of the two sets of data (x & y coord)
   - slope of the regression line is the correlation between the two sets of heights multiplied by the ratio of the standard deviations (of outcomes to predictors)




