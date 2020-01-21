# Notes
Data Sceince concepts notes for refrence


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

10. 

