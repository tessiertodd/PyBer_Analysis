# PyBer_Analysis

## Project Overview
This project was launched to understand how the ride-sharing information by city differs, and how that information can be used by V. Isualize (CEO of Pyber) and rest of Pyber team to make decisions based on city type as they navigate the competitive ride sharing market.

Using the analysis we are asked to provide some three recommendations to help improve the PyBer business. 


## Resources
- Data Source: city_data.csv
- Data Source: ride_data.csv
- Sofware: Jupyter Notebook 6.3.0
- Library: Matplotlib.pyplot
- Library: Pandas
- Library: Matplotlib (imported style)
- Language: Python 3.6.7



# Deliverable 1: A ride-sharing summary DataFrame by city type
![Table for Ride Sharing Summary](https://github.com/tessiertodd/PyBer_Analysis/blob/main/Resources/Ride%20Sharing%20Summary%20DF.png)

The urban cities have more rides and drivers, which make sense given the larger population in urban vs. suburban and rural - there are 31x more drivers in urban than in rural and just under 5x more in urban than suburban. There are 13x more rides in urban than rural and 2.6x more rides in urban than suburban cities.

The Average fare per ride and per driver are higher in rural cities than suburban or urban... with Urban having the lowest of all three.  This variance speaks to the fact that in rural cities, the distance between locations is typically further than suburban or urban.

Another difference between urban and suburban/rural is that with people who live in urban cities, there is a higher chance they may not own a car... which also speak to some of the difference in ride sharing metrics between city types.


# Deliverable 2: Multiple line plot of weekly fares for each city type
![Table Ride Sharing Graph](https://github.com/tessiertodd/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)
![Table Ride Describe](https://github.com/tessiertodd/PyBer_Analysis/blob/main/Resources/Fares_Pivot_Describe.png)

The weekly total fares for each city type (range used 1st and 3rd quartile):
- urban cities generally generate between $2,000 to $2,300 (average is just under $2,100) 
- suburban cities generally generate $900 to $1,200 (average just over $1,000)
- rural cities generally generate $170 to $287 (average just over $225)



# Summary
***Based on my analysis of the PyBer's markets, here are 3 recommendations:***
  - In the Rural cities given the high average fare per ride of $34.62 and average fare per driver at $55.49 it appears that this type of city is underserviced as the average fare per driver vs. average fare per ride relative to both suburban and urban markets. I recommend you increase drivers in rural locations as you may be able to provide more rides while still being a profitable on a per driver basis. There will however be an upper limit as in rural areas many people own and drive cars.
 - Suburban market still has some upside potential where the average fare is still pretty high at $30.97 and there are less drivers than rides.  If the number of drivers increased but not higher than the number of drivers, there would be some upside revenue potential.
 - Given the low average fares per ride at $24.53 in Urban cities and average fare per driver being lower at $16.57, this market appears to have too many drivers (currently 2,405 drivers and only 1,625 rides) and you may want to consider taking some drivers out of this market.  An alternative to removing drivers is looking into also providing delivery services for food, drinks, or other items to help increase the overall revenue per driver.
