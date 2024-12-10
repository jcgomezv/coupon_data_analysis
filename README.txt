Introduction

This package contains the followin items:
1.-prompt.ipynb: Jupyter notebook that contains a study and disection of the data in data/coupons.csv
2.-data/coupons.csv: data about discount coupons distributed across some population of potential customers
3.-this file that contains a summary of the work and some general conclusions

Summary

In this notebook I explored the data provided and tried to infer some characteristics of clients that are more
likely to accept and use coupons. Some of the features in the data describe the target individuals, others describe
the weather conditions on the day of distribution, and others describe the coupons and more about context of the 
individual receiving it.

General Conclusions

Here I will only present general conclusions that I can infer from some of the data exploring I did, I would refer
you to the Jupyter notebook for more specific conclusions as it would be pointless repeating all specifics here.

1.-Some coupons, specially associated with lower cost are popular among all groups of targets (i.e. Carry out &
Takeaway and Restaurants < 20)

2.-Some coupons, like bar coupons, area more attractive to younger generations that are travelling in groups.

3.-The acceptance of coupons depends on the nature of the coupon and some coupons are more attractive to some subgroups
of the population.

4.-Good weather is a factor that increases the acceptance of coupons.

5.-Males end to accept slightly more coupons than Females

6.-The more educated populations seems to have slightly lower bias to accept coupons.

7.-Younger inidviduals seem to accept coupons at a higher rate than older ones.

8.-Travelling with kids tend to bias toward rejecting some type of coupons like Bars.

9.-Coupons Distributed very early or late tend to be rejected more than those distributed during working/awake hours.

10.-General accept rate of all types of coupons is 56.8 % which is good for any blind marketing effort.

11.-Some factors like direction of travel display some anomalies for Carry out and Restaurants < 20 which are more
frequently accepted when in opposite direction of travel direction, which is counterintuitive.

12.-Individuals are more likely to accept couponw when travelling to non-urgent places, but carry out is specially
likely to be accepted by those heading home.

13.-Customers with children are more likely to accept carry out but reject any other types of coupons.

14.-Most coupons have higher accept rates if driving distance is smaller, but the accept rates for some categories
like bars and take out are only sligthly affected by driving distance.

Conclusions

Using all the knowldege above we can target specific coupons to specific populations where they are more likely to be accepted and also use the weather and temperature and time of day to focus the higher rate of coupon generation on those time and conditions when we know we are more likely to be accepted. This would be specailly true even if the cost with distribution of coupons is very low cost, as customers who receive too many coupons they mostly reject will tend to ignore the 
future ones.

A system can collect information as a customer starts her trip and use contextual information about the individual, weather and time of day to generate coupons which are most likely to be accepted.


