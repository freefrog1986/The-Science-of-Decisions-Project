# Statistics: The Science of Decisions Project

### Summary
This is a report about The Science of Decisions Project, we give some descriptive statistics about the dataset including reaction time of some participants in a Stroop task, and visualize the distribution of the sample data, after that, hypothesis anylysis will be porfomed. Finally, our conclusion is that incongruent do increase the reaction time.

###1. Independent and dependent variable
Independent variable is the conditions of the test, which consist of two type of a congruent words condition and an incongruent words condition.
Dependent variable is the time spent by participants.

###2. Hypothesis and statistical test
In the test each participant will go through and record a time from each condition, so we can treat those samples as dependent samples.
The Null Hypothesis for this task is that the time spent has no change when test condition change from congruent to incongruent.
The most reasonable Alternative Hypothesis is the time spent incresed due to test condition change from incongruent to incongruent.
A one-tailed t-test in positive direction will be perfomed. If we reject the null hypotheses, conclution can be made that participants spent more time in incongruent words condition than congruent words condition.

###3. Descriptive statistics
The mean time of congruent condition is 14.05113
The mean time of incongruent condition is 22.01592
The sd time of congruent condition is 3.559358
The sd time of incongruent condition is 4.797057

###4. Distribution of the sample data
![](/Users/freefrog/Studing/DataScience/The-Science-of-Decisions-Project/Congruent.png) 
The figure above shows the distribution of time spent in congruent condition, in which the blue line represents mean value of this sample.
![](/Users/freefrog/Studing/DataScience/The-Science-of-Decisions-Project/Incongruent.png) 
The figure above shows the distribution of time spent in incongruent condition, in which the blue line represents mean value of this sample. It seems that both sample are more like Normal Distribution, and mean value of time spent in incongruent condition is greater than that in congruent condition.

###5. Statistical test
As we know, the mean value of congruent sample is 14.05113, repersented by mu0. And the mean value of incongruent sample is 22.01592 repersented by mu1. 
Degrees of Freedome is 23 cause we have 24 samples.
T-critical value is 1.713872 at alpha = 0.05.
SD of difference is 4.864827
T-stistic value is 8.020707 which is greater than t-critical value, so we should reject the null hypothesis.
finally, we can make conclusion in terms of the experiment task that incongruent do increase the reaction time, and that also match up with my expectations.
