# Birthday Problem

## Summary

The Birthday Problem concerns the probability that some pair of them will have the same birhday. For example, if 23 people in the group would have the probability of a shared birthday more than 50 percentages, while a group of 70 people woule have 99.9 percentages.
Therefore, it does not need 366 people in a group in order to get 100% of shared birthday. If you are supposed to bet this problem in the group of at least 23 people, you should bet the exist of shared birthday.

## Explanation

- Premise
For simplicity, variations in the distribution, such as leap years, twins, seasonal, or weekday variations are disregarded, and it is assumed that all 365 possible birthdays are equally likely.

- Calculation
The goal is to compute P(A), the probability that at least two people in the room have the same birthday. In order to calculate it more easier, we use P(A'), the probability that no two people in the room have the same birthday. And these are also mutually exclusive.
P(A) = 1 - P(A')

In order to calculate P(A'), the second person must have diffrent birthday with first one, and also third one must have diffrent birthday with first and second person, and so on. the probability of event 2 is 364/365, as person 2 may have any birthday other than the birthday of person 1. Similarly, the probability of event 3 given that event 2 occured is 363/365, as person 3 may have any of the birthdays not already taken by persons 1 and 2.


- What it means
The equation expresses the fact that the first person has no one to share a birthday, the second person cannot have the same birthday as the first, the third one cannot have the same birthday as either of the first two, and in general the 'n'th birthday cannot be the same as any of the n-1 preceding birthdays.

Therefore, the probability of shared birthday p(n) is 1 - p(n')

