# (Analyze A-B Test for E-commerce Website)
## by (Khaled Yaseen)


## Dataset

> I  working to understand the results of an A/B test run by an e-commerce website. My goal is to work through this notebook to help the company understand if they should implement the new page, keep the old page, or perhaps run the experiment longer to make their decision.


## In this project , We try different approaches to help us take decision to launch the new page or keep the old one , We tried :

The probability approach.
A/B test using hypothesis test.
logistic regression approach.

## The probability :

We found half of users would use the new page to convert but the other half would use the old page.

## A/B test :

We set the null hypothesis as the old page is better than or equal to the new page in conversion and the alternative hypothesis is the new page is higher than the old page in conversion.
We found the p_value is too high equal to 0.905.
We failed to reject the null.

## The logistic regression :

In regression we would find out two possible outcome to know if the new page is better in conversion or not.
From regression we found the same Z_score from A/B test but different P_VALUE because of two tailed case.
After adding the location of users we found the location has not observed impact on conversion.

## Take on consideration :

The duration of the experiment (21 days) and it not long time enough for A/B test.
Due to Change aversion effect, a group of users may give an unfair advantage to the old page.
Similarly, due to Novelty effect, users may give an unfair advantage to the newer page.