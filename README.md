# Predicting-Landing-distance-of-Flights

## Federal Aviation Administration case study 
Analysis of 950 commercial flights to draw insights on what factors affect the flight landing distance. This was done through data importing, dataset merging, treatment of missing values, exploratory data analysis (EDA), and data visualization.
Also, a predictive model (using Linear Regression) was built to predict landing distance so that risk of landing overrun can be reduced.

## Tools Used:
R

## Datasets used
FAA1.csv and FAA2.csv datasets uploaded in this repository.

## Variables analyzed
**Aircraft:** The make of an aircraft (Boeing or Airbus).

**Duration (in minutes):** Flight duration between taking off and landing. The duration of a normal flight should always be greater than 40min.

**No_pasg:** The number of passengers in a flight.

**Speed_ground (in miles per hour):** The ground speed of an aircraft when passing over the threshold of the runway. If its value is less than 30MPH or greater than 140MPH, then the landing would be considered as abnormal.

**Speed_air (in miles per hour):** The air speed of an aircraft when passing over the threshold of the runway. If its value is less than 30MPH or greater than 140MPH, then the landing would be considered as abnormal.

**Height (in meters):** The height of an aircraft when it is passing over the threshold of the runway. The landing aircraft is required to be at least 6 meters high at the threshold of the runway.

**Pitch (in degrees):** Pitch angle of an aircraft when it is passing over the threshold of the runway.

**Distance (in feet):** The landing distance of an aircraft. More specifically, it refers to the distance between the threshold of the runway and the point where the aircraft can be fully stopped. The length of the airport runway is typically less than 6000 feet.

## Key Insights
There is a difference in factors and how they affect landing distance for the two different types of aircrafts
Whereas for Airbus planes, factors affecting 'Landing Distance' the most tend to be 'Air speed', 'Ground Speed', and 'Height', for Boeing planes the variables are Air speed and Height (at a 95% confidence level).
In general, a unit change in 'Air speed' affected 'landing distance' 8 times more than a unit change in 'height'.
