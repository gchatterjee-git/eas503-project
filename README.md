![UB](https://github.com/mayurs142/eas503-project/blob/media/ub_logo.png?raw=true)
# EAS 503 - Project Group 20
### Team Members:
> Gaurav Chatterjee <br>
> Mayur Sinha <br>
> Megha Shirodkar

### Introduction
The trip costs of Uber and Lyft are not static like those of public transport. They are hugely impacted at a given time by the demand and supply of trips. So, what exactly drives this demand? The first guess would be the time of the day; the most significant spikes should be seen between 9 AM and 5 PM as people go to work/home. Another explanation is the weather; rain/snow increases the demand for the cabs.
### Data Description
There are two datasets. The cab ride data covers the different types of Uber & Lyft cabs taken and their price for the trip along with any surge. The weather data includes attributes such as temperature, rain, cloud, etc. for the listed locations.
##### Cab Rides
| columns  | description |
|----- | ---- |
| distance | distance covered |
| cab_type | Uber or Lyft |
| time_stamp | epoch time |
| destination | destination of the ride |
| source | source of the ride |
| price | total cab ride fare |
| surge_multiplier | fare multiplier |
| id | unique identifier |
| product_id | Uber/Lyft identifier |
| name | Uber/Lyft cab type |

##### Weather Data
| columns  | description |
|----- | ---- |
| temp | temperature in Fahrenheit
| location | location name
| clouds | cloud forecast in oktas |
| pressure | atmospheric pressure in millibar | 
| rain | rain in inches in the last hour |
| time_stamp | epoch time |
| humidity | humidity in percentage |
| wind | wind in miles per hour |

### Proposed Analysis
The proposed analysis is to evaluate the price of these ride-sharing apps and to decide what factors drive the business. Do different days have different demands? How much weather contribute to the fare of these cab rides.

### Analysis Methods
Analyses techniques employed in the project are:
1. Statistical analysis of the numerical data to organize and summarize data and draw conclusions about cab fares.
2. Predictive analysis to make forecasts about future outcomes of cab fares based on current data.

### Tech Stack Used
![Python](https://github.com/mayurs142/eas503-project/blob/media/python.png?raw=true) ![SQLite3](https://github.com/mayurs142/eas503-project/blob/media/sqlite3.png?raw=true)