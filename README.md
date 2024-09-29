### Will the Customer Accept the Coupon?

**Context**

Imagine driving through town and a coupon is delivered to your cell phone for a restaurant near where you are driving. Would you accept that coupon and take a short detour to the restaurant? Would you accept the coupon but use it on a subsequent trip? Would you ignore the coupon entirely? What if the coupon was for a bar instead of a restaurant? What about a coffee house? Would you accept a bar coupon with a minor passenger in the car? What about if it was just you and your partner in the car? Would weather impact the rate of acceptance? What about the time of day?

Obviously, proximity to the business is a factor on whether the coupon is delivered to the driver or not, but what are the factors that determine whether a driver accepts the coupon once it is delivered to them? How would you determine whether a driver is likely to accept a coupon?

I am planning to extend and explore more with this dataset, for that reason I created a folder 'Phase1' with just data exploration and analysis. in future I will be creating more folders with more exposure in ML & Ai domains.

**Data**

This data is from the UCI Machine Learning Repository and was collected via a survey on Amazon Mechanical Turk. The survey describes different driving scenarios, including the destination, current time, weather, and passenger, and then asks people whether they will accept the coupon if they are the driver. There are three possible answers people can choose from:

“Right away”
“Later, before the coupon expires”
“No, I do not want the coupon”
The first two responses are labeled as “Y = 1,” and the third is labeled as “Y = 0.” There are five different types of coupons: Less expensive restaurants (under $20), coffee houses, carryout and takeaway, bars, and more expensive restaurants ($20–$50).


**Data Description**

Keep in mind that these values mentioned below are average values.

The attributes of this data set include:

1. User attributes

-Gender: male, female

-Age: below 21, 21 to 25, 26 to 30, etc.

-Marital Status: single, married partner, unmarried partner, or widowed

-Number of children: 0, 1, or more than 1

-Education: high school, bachelors degree, associates degree, or graduate degree

-Occupation: architecture & engineering, business & financial, etc.

-Annual income: less than $12500, $12500 - $24999, $25000 - $37499, etc.

-Number of times that he/she goes to a bar: 0, less than 1, 1 to 3, 4 to 8 or greater than 8

-Number of times that he/she buys takeaway food: 0, less than 1, 1 to 3, 4 to 8 or greater than 8

-Number of times that he/she goes to a coffee house: 0, less than 1, 1 to 3, 4 to 8 or greater than 8

-Number of times that he/she eats at a restaurant with average expense less than $20 per person: 0, less than 1, 1 to 3, 4 to 8 or greater than 8

-Number of times that he/she goes to a bar: 0, less than 1, 1 to 3, 4 to 8 or greater than 8


2. Contextual attributes
   
-Driving destination: home, work, or no urgent destination

-Location of user, coupon and destination: we provide a map to show the geographical location of the user, destination, and the venue, and we mark the distance between each two places with time of driving. The user can see whether the venue is in the same direction as the destination.

-Weather: sunny, rainy, or snowy

-Temperature: 30F, 55F, or 80F

-Time: 10AM, 2PM, or 6PM

-Passenger: alone, partner, kid(s), or friend(s)

-Coupon attributes

-time before it expires: 2 hours or one day


**Outcome**

The final product should be a brief report that highlights the differences between customers who did and did not accept the coupons. To explore the data we will utilize the knowledge of plotting, statistical summaries, and visualization using Python. 


** Summary of Analysis Perfomed in Phase 1**

In Phase 1, I tried find out any missing data and explored the patterns with the modified data

Most of my analysis on coupons types of 'Bar' & 'Coffes House'

**Outcomes of my analysis**

1. Acceptance Patterns of 'Bar' Coupons
