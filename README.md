# TikTok Exploratory Data Analysis and Hypothesis Testing
Hypothesis Testing is basically to check whether the difference between the means (or ratio) of two samples is statistically significant. But what do we mean by "statistically significant"? It means that there is definitely some significant amount of difference between the two means (or ratios) and this difference is not by chance/luck, this difference has some statistical significance to it. For Hypothesis Testing I will work on TikTok Dataset. First I will perform some EDA because Hypothesis Testing do not give relevant results if there are missing values, duplicate values or any extreme outliers.

I will consider the following activities. For each, I will construct a hypothesis test and use my results of that test to make a recommendation:

1. I will consider run a descriptive test and check for some missing values. I will clear if there are any. <br>
2. I will run a Hypothesis Test to check whether the mean video view count for verified and non-verified authors is same or different. And if it is different then does it have any statistical significant to it.

Notes: <br>
For this analysis, I'll default to a 5% level of significance. Throughout the lab, for two-sample t-tests, use Welch's t-test (i.e., setting the equal_var parameter to False in scipy.stats.ttest_ind()). This will account for the possibly unequal variances between the two groups in the comparison.
