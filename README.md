# Yellow vs. Green Taxi Tip Analysis

## Overview

This project examines whether yellow and green taxi cabs receive different average tip amounts. A two-sample t-test was used to compare the two groups.

## Process

The taxi data was loaded into a pandas DataFrame and reviewed using descriptive statistics. The data was then separated into yellow cab and green cab groups.

Histograms were created to examine the distribution of tips. A normality test showed that yellow cab tips were approximately normal, while green cab tips were not normally distributed.

Bartlett’s test produced a p-value of **0.3798**, indicating no significant difference in variance between the groups.

## Results

The two-sample t-test produced:

* T-statistic: **0.0454**
* P-value: **0.9638**
* Degrees of freedom: **582**

## Conclusion

Because the p-value is greater than **0.05**, we fail to reject the null hypothesis. There is no statistically significant difference between the average tips received by yellow cabs and green cabs.
