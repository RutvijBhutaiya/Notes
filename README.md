# Statistics Notes

Data Science Stats concepts notes for refrence


1.  Mahanolobis distance: It is used when independent variable are correlated. And hence, in that situation Euclidian distance would not work.  So we use Mahanolobis distance. 
It is measurement based on 2 points variance and the centre point of the dimension. 
It can be used to measure distances eve in 3, 4, n dimension space. 

2.	Before any model selection, especially take plot between variables – Check if points are NO overlaps (for class 0 and 1) then you can use linear or logistic regression or basically regression technique. 
If there is mix and overlap – use KNN method because Knn goes for Euclidian distance and can predict class accordingly. 

3.	You can plot Bar chart with R, with table () plus also box plot (class wise like male & Female) with the use of table ().

4.	OLS – Ordinary Least Squared Method (in Regression) – least squares: minimizing the sum of the squares of the differences between the observed dependent variable (values of the variable being observed) in the given dataset and those predicted by the linear function.


5.	Residuals = Actual – predicted 

6.	What is Statistic? How to use: IN real world when we do experiment for example if want to measure Swatch Bharat Abhiyan impact in rural sanitation. Then we can’t take data from every villages (cost involved). So, we take sample, let’s say 20 village (choosing right sampling method). And we run statistics – Descriptive stats (mean medium mode, relationship) and Inferential Stats (ANOVA, t-test, Hypothesis). And we can come to conclusion Perspective stats How Swatch Bharat worked in villages and what needs to improve.  

7.	P-value: less the p-value mean less often we expect the result/value, if Null Hypothesis is true. Hence, in hypothesis we try to reduce p-value (< 0.05) and hence, proved that the value occurrence is less and based on that we reject the Null. And Alternate Hypo approved. 

8.	Sampling Distribution (Before every distribution we do this): Can use histogram for smooth curve. Here we computer choose random numbers based on the probability described by the histogram curve. 
-	We take sample from distribution to explore statistics We can generate n numbers of samples and can use it statically (t test, z test, chi test) to explore it. 
-	If distribution is same for both samples, p-value should be large. If different, p-value small. 

9. Central Limit Theorem: Central Limit Theorem states that if you add up independent random variables, their normalization sum tends towards normal distribution. CLM holds even if random variables themselves do not come from a normal distribution.  
-	E.g. create 100 samples, u’ll get 100 means from each sample. And If histogram is not skewed it means normal distribution. In 2nd e.g created 100 means from right skewed data and still histogram is normal. 
-	So, who cares from where the data is come from, we can always sample it and normally distribute it CLM. And we can use normal distribution for confidence interval (Hypothesis) or also for t-test (for 2 samples) or ANOVA (for more than 2 samples)
-	BUT for CLM – SAMPLE SHOULD BE AROUND 30. IF SAMPLE SIZE IS 20 RULE IS BROKEN. 

10. Quantile (Percentiles): If there are 10 data points of Students weight.  5 data measurements are below 5 and 5 are above 5. Then quantile is 50% because 50% above medium and 50% below medium.  Now, if we again split the both the sets (above 50% and below) we get 2 more quintiles (in below 50% we get 0.25 point as quantile and at above 50% we get 0.75 point at quantile).
-	Percentile are quintiles that divide data into 100 equal size. Like, 25th or 60th percentile etc.  


11. Standard Errors: 
-	3 common type of errors, 1. SD: Big SD shows some data points are far from the mean. 2. Std error: Tells how mean is distributed. 3. Confidence interval related to std error.  
-	SD of means called standard error. (So, if we take 5 sample and calculate their SD, and when we avg. all SD, we get std error)
-	Step 1. Take 5 samples 2. Take mean for each sample 3. Take SD 4. Get std error.

12.	T-test: Before and after measurement from same test study. (Like Golf ball and new golf ball shape). So, you have paired data. 
-	Two tail t-test: When you what to check low and high end of the test. Like in Golf balls e.g. you want to see the low distance and max distance test. 
-	One tail t-test: When you are sure that you want to test only max distance of the golf balls test. You choose one tail t-test. 
-	Preferred two tail – because let the data speak itself in test. (but still depends)
-	Two tailed T-test tells us whether new measurements are better, worst or not significant different. One tail test doesn’t distinguish worst and not significant results. It only gives better or not significant result.  

13. A/B Testing (Same as Hypothesis testing)
-	A/B testing is to give two variants of same model, to different set of process. Whichever variant gives accurate results becomes winner. 
-	Example – Website traffic and conversation ratio - One way to optimize your website’s funnel is A/B testing. A/B testing (also sometimes referred to as split testing) is the practice of showing two variants of the same web page to different segments of visitors at the same time and comparing which variant drives more conversions. Typically, the one that gives higher conversions is the winning variant, applying, which can help you optimize your site for better results.
-	Once you explain A/B test concept. Give example of Ho and Ha and how p-value is useful to reject or keep Ho.

14. Variance: In random variable how much data deviates from mean. E.g. x = 3,3,3,3 and Y= 1,3,3,5. Bothe variables has same mean but different variance. 

15.	Covariance: In two random variables, when variable Apple size deviated from it’s mean when variable grapes size deviated from it’s mean. We see the trend (positive / negative / No trend) in covariance. 

16.	Correlation: Relationship between two variables (Strong / Moderate / Weak)

17.	Data Validation: To check the accuracy and quality of the data source, before processing the data. E.g Range check

18. Normal Distribution:
-	IN probability distribution, Normal distribution is widely used by Data scientists. 
-	Also known as Gaussian distribution.
-	Normal distribution based on purely 2 parameters. Mean and SD.
-	Mean is average value of samples. And SD is how diverse data is from the mean. 
-	This is based on random variables selected, now when you add new variable to the distribution, it will automatically fall under normal distribution. Thanks to Central Limit Theorem. 
-	Normal Dist. is important for high accuracy of the model. 
-	Mean = mode = medium 
-	1 SD = 68.2% area
-	2 SD = 95.5% area
-	3 SD = 99.7% area
-	This is gives the confidence to predict, less deviation better. 

19.	How statistics can lead to wrong decision: (Very Interesting) explained Simpson’s Paradox
-	https://www.ted.com/talks/mark_liddell_how_statistics_can_be_misleading#t-137041
-	Example of 2 hospital, and example of smokers. 

20.	Bayes theorem: (https://towardsdatascience.com/bayes-theorem-the-holy-grail-of-data-science-55d93315defb)
-	Mathematical formula for determining conditional probability. 
-	E.g. In finance, can identify risk to lending money to protentional buyers
-	E.g In pharma, medical test accuracy, for a person carries decease or not. 

