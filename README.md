# FrankPracticalApplication1
This is the first Practical Application for Berkeley Machine Learning Certificate Program.

## Overview:

This project aims to use what we know about visualizations and probability distributions to distinguish between customers who accepted a driving coupon versus those who did not.

## Data:

This data comes to us from the UCI Machine Learning repository and was collected via a survey on Amazon Mechanical Turk. The survey describes different driving scenarios, including the destination, current time, weather, passenger, etc., and then asks the person whether he will accept the coupon if he is the driver. Answers that the user will drive there ‘right away’ or ‘later before the coupon expires’ are labeled as ‘Y = 1’, and answers ‘no, I do not want the coupon’ are labeled as ‘Y = 0’. There are five different types of coupons -- less expensive restaurants (under $20), coffee houses, carry-and-take-away bars, and more expensive restaurants ($20 - $50).



## Notebook:

Notebook can be found here:  Link to notebook



## Data Description:

The attributes of this data set include:

### User attributes

1. Gender: male, female
2. Age: below 21, 21 to 25, 26 to 30, etc.
3. Marital Status: single, married partner, unmarried partner, or widowed
4. Number of children: 0, 1, or more than 1
5. Education: high school, bachelor's degree, associate degree, or graduate degree
6. Occupation: architecture & engineering, business & financial, etc.
7. Annual income: less than \$12500, \$12500 - \$24999, \$25000 - \$37499, etc.
8. Number of times that he/she goes to a bar: 0, less than 1, 1 to 3, 4 to 8, or greater than 8
9. Number of times that he/she buys takeaway food: 0, less than 1, 1 to 3, 4 to 8, or greater than 8
10. Number of times that he/she goes to a coffee house: 0, less than 1, 1 to 3, 4 to 8, or greater than 8
11. Number of times that he/she eats at a restaurant with an average expense of less than \$20 per person: 0, less than 1, 1 to 3, 4 to 8, or greater than 8
12. Number of times that he/she goes to a bar: 0, less than 1, 1 to 3, 4 to 8, or greater than 8

### Contextual attributes

1. Driving destination: home, work, or no urgent destination
2. Location of user, coupon, and destination: we provide a map to show the geographical location of the user, destination, and the venue, and we mark the distance between each two places with the time of driving. The user can see whether the venue is in the same direction as the destination.
3. Weather: sunny, rainy, or snowy
4. Temperature: 30F, 55F, or 80F
5. Time: 10 AM, 2 PM, or 6 PM
6. Passenger: alone, partner, kid(s), or friend(s)

### Coupon attributes

1. time before it expires: 2 hours or one day



## Analysis:

1. Individuals under 30 who visit bars more than once monthly are the most likely to accept bar coupons. This trend may stem from their frequent bar visits and greater openness to exploring new venues.

2. Bar patrons who visit more than once a month, have no children as passengers, and do not work in agriculture, fishing, or forestry show the second-highest coupon acceptance rates. This is comparable to similar frequent bar visitors without child passengers and who are not widowed, indicating a social component to coupon usage and bar attendance.

3. Drivers who frequent bars more than once a month tend to accept more bar coupons, likely seeing more benefit in using them.

4. Those who patronize less expensive restaurants and earn a lower income also show a notable rate of coupon acceptance, though it is the weakest among the groups. This indicates that budget-conscious individuals or those with limited spending money will likely value these coupons.

5. The substantial acceptance rates, which vary from 60% to 72%, among these groups highlight the potential effectiveness of targeted marketing strategies. Focusing on these particular demographics could yield a significant marketing return on investment.
