# AIRBNB-LISTINGS-ANALYSIS
This is an analysis of Airbnb Boston listings dataset . The question we want to answer is: What factors are associated with Airbnb prices, and can we quantify the uncertainty in those relationships?


We'll be following these steps:
### Exploratory Data Analysis (EDA)
    • What does the distribution of Airbnb prices look like? 
    • What's the median price? 
    • Are there extreme outliers? 
    • How does price vary by neighborhood? 
    • Reviews price
### Probability / simulation
       What's the probability that a randomly selected Airbnb costs more than $200/night? we'll use a simulation to understand the uncertainty around our estimate. 
### Bootstrap 
    For example: What's the 95% confidence interval for a given price? We can bootstrap the dataset and construct the confidence interval ourselves rather than relying on a black-box function. 
### Hypothesis testing
       Are Airbnb prices significantly different between two neighborhoods? Then we will perform a permutation test. 
### Correlation
       Is the number of reviews correlated with price? Or: Is minimum-night requirement correlated with price? And calculate Pearson's rr. 
### **Linear regression**
    How much does price tend to change as the number of bedrooms increases? Then we build a regression and use a pairs bootstrap to estimate uncertainty around the slope.
