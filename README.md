# A/B Testing for Marketing Strategies

## Executive Summary
Star Digital, a video service provider was curious about whether their advertisement is really effective, so it designed an experiment for advertising through internet to test it.

## Main Business Goals
There are three business goals I would like to discuss here:
1. Is online advertising effective for Star Digital?
2. Is there a frequency effect of advertising on purchase? In particular, whether increasing the frequency of advertising increases the probability of purchase?
3. Which sites should Star Digital advertise on? In particular, should it put its advertising dollars in Site 6 or in Sites 1 through 5?

## Analysis Process
1. Explore the data set
2. Check whether there is missing data
3. Evaluate the data set randomization efficiency
4. Apply t.test and logistic regression model to analyze the business problems accordingly
5. Analyze the results and interpret the business values

##  Whole Picture of the Experiment
By considering the several aspects, including baseline conversion rate, campaign reach, the minimum lift that the advertiser cares to detect and power of the experiment. There are 2,656 control group and  22,647 treatment group. The duration of the experiment was 2 months in 2012.

## Potential Concern
There may be SUTVA problems, for example, one of the member of treatment group and one of the member of control group are family. They might share information with others.

## Terminology to Know First
1. “t-test” is a statistic method. In this case, we will use it to check if one feature can cause any difference to control group and treatment group.
2. “logistic regression” is the model that we can learn about whether one feature have any effect to our purchase. We will interpret their effects by their coefficient. Positive means positive effect,negative indicates the opposite. The absolute size of the coefficient indicates the influence it has.
3. “p-value” is a statistic results, we use p-value 0.05 as threshold to prove our assumption.
