---
output:
  pdf_document: default
  html_document: default
---
# Statistics: The Science of Decisions Project

### Summary
This is a report about The Science of Decisions Project, we give some descriptive statistics about the dataset including reaction time of some participants in a Stroop task, and visualize the distribution of the sample data, after that, hypothesis anylysis will be porfomed. Finally, our conclusion is that incongruent do increase the reaction time.

###1. Independent and dependent variable
Independent variable is the conditions of the test, which consist of two type of a congruent words condition and an incongruent words condition.
Dependent variable is the time spent by participants.

###2. Hypothesis and statistical test
The Null Hypothesis for this task is that the congruent mean population time,  μ1 is equal to the incongruent mean population time μ2.
H0: μ1 = μ2
The Alternative Hypothesis is the incongruent mean population time μ2 is greater than μ1. this also implying that this is a lower-tailed test.
H1: μ1< μ2
A one-tailed dependent t-test in positive direction will be perfomed for the reason below:
1. The sample size is small and the sample distribution is unclear, so we should use t-test.  
2. Since each participant performed both conditions not all samples are independent, so we use dependent t-test.
3. The Alternative Hypothesis suppose that μ2 is greater than μ1, so positive direction one-tailed t-test fit this case. 

###3. Descriptive statistics
The mean time of congruent condition is 14.05113
The mean time of incongruent condition is 22.01592
The sd time of congruent condition is 3.559358
The sd time of incongruent condition is 4.797057

###4. Distribution of the sample data
![](../Congruent.png) 
The figure above shows the distribution of time spent in congruent condition, in which the blue line represents mean value of this sample.
![](../Incongruent.png) 
The figure above shows the distribution of time spent in incongruent condition, in which the blue line represents mean value of this sample. It seems that both sample are more like Normal Distribution, and mean value of time spent in incongruent condition is greater than that in congruent condition.

###5. Statistical test
As we know, the mean value of congruent sample is 14.05113, repersented by mu0. And the mean value of incongruent sample is 22.01592 repersented by mu1. 
Degrees of Freedome is 23 cause we have 24 samples.
T-critical value is 1.713872 at alpha = 0.05.
SD of difference is 4.864827
T-stistic value is 8.020707 which is greater than t-critical value, so we should reject the null hypothesis.
finally, we can make conclusion in terms of the experiment task that incongruent do increase the reaction time, and that also match up with my expectations.
