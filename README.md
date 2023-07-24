# Linear-Regression-assignment

Linear Regression Assignment:

A Linear Regression Machine Learning Model to predict bike sharing bookings for BoomBikes based upon 2018 ans 2019 data.

This assignment is a programming assignment wherein you have to build a multiple linear regression model for the prediction of demand for shared bikes.

A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.



A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 

A regression model uses gradient descent to update the coefficients of the line by reducing the cost function. It is done by a random selection of values of coefficient and then iteratively update the values to reach the minimum cost function.

The company wants to know:
Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands

Conclusion:- The regression line enables one to predict the value of the dependent variable Y from that of the independent variable X. Thus, for example, after a linear regression has been performed, one would be able to estimate a person's weight (dependent variable) from his or her height (independent variable) 

Model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations.

The Assignment for bike-sharing demand is predicting the number of bikes that will be rented from a bike-sharing system at a given time based on factors such as weather, day of the week, and time of day.

Analysis: 
• Most important factor affecting demand is temperature. With a coefficient of 0.73126, for every change in temperature of 1 degrees, demand increases by a factor of 0.73126 (temperature × 0.73126. Based on this, company will have to consider:
• Necessary capacity building during hotter months to fulfill the demand:
• Recall from our DA section that hottest months lie in Fall season, June, July and Aug being the hottest.
•If the company is able to scale up its resources to meet the increasing demand in these 3 months, it will also be wise to invest in increased marketing and promotional activities if more competitors operate in the same market with similar offering.
• Second most important factor is Light Rain or Snow with a coefficient of -0.27750. Hence, if a particular day has light rains, it is expected to reduce the demand by 27.7%.
• Recall from our EDA section that frequency of light rains has been lowest and heavy rains have largely been non existant. October month shows the maximum number of instances of light rains.
• Based on this, it is recommended to develop a sentiment based advertisement plan that heavily promotes "fun element" of "riding bikes in the rain with family'
• Third most important factor is year with a coefficient value of 0.24236. Based on the historical data, given all internal and external factors remain unchanged, the company is expected to see annual growth over last year at around 24%.
• This helps us in factoring teh revenue and cost projections over a period of time,
• Fourth most important factor is winter with a coefficient of 0.12793. This signifies that every winter, the demand is expected to incerase by a factor of 0.12793 bad on other months.
• Recall from our DA section, we recollect that Winter season constitutes of Sep. Oct, Nov and December months.
• Company needs to work on capacity planing of these months and additionally plan for promotional campaigns in case a competitors exist with similar value propositions.
• Fifth most important variable is the month of July with a coefficient weightage of -0.10141 which signifies that every July the demand is expected to drop by a factor of 0.10141 (Around 10%)
• Since month of July is also one of the hottest months, its relative weightage will simply decrease as compared to June and August. Hence, by logic, we can exclude month of July from our past recommendation.

Significant variables to predict the demand for shared bikes

holiday
temp
hum
windspeed
Season
months(January, July, September, November, December)
Year (2019)
Sunday
weathersit( Light Snow, Mist + Cloudy)

Technologies Used
numpy - version 1.20.3
pandas - version 1.3.4
matplotlib - version 3.4.3
plotly - version 5.6.0
seaborn - version 0.11.2
statsmodels - version 0.12.2
sklearn - version 0.24.2
scipy - version 1.7.1

This Project is created by @Vinaysharma5672.
