# SF_Flight_Prediction

## Project goal:
Predict the Delayed Status of the Flights Depart from SFO

## Data sources :
a. Flights Dataset: United States Department of Transportation
   - Data size: 2.12G
   - Description: Monthly flights of the United States from 2013 to 2015
   - For this project, around 500,000 flights departure from San Francisco International Airport (SFO) are extracted.

b. Historical Hourly Weather Data 2012-2017: Kaggle
   - Data size: 52.5MB
   - Description: Hourly weather data for 30 US & Canadian Cities + 6 Israeli Cities¶
   - For this project, weather conditions in SF from 2013 to 2015 are extracted.

## SFO Variables Clarifications

- __*YEAR*__: 2013-2015
- __*MONTH*__: 1-12(JAN-DEC)
- __*DAY_OF_WEEK*__: 1-7(MON-SUN)
- __*OP_UNIQUE_CARRIER*__: Airline
- __*ORIGIN*__: Departure airport
- __*DEST*__: Arrival airport
- __*CRS_DEP_TIME*__: Scheduled departure time (first 2 digits are hour, last 2 digits are minute)
- __*CANCELLED*__: If the flight is cancelled (YES=1)
- __*DEP_DELAY*__: Departure delay in minute
- __*CARRIER_DELAY*__: Delay due to airline operation
- __*WEATHER_DELAY*__: Delay due to unsatisfactory weather
- __*NAS_DELAY*__: Delay that is within the control of the National Airspace System (NAS) may include: non-extreme weather conditions, airport operations, heavy traffic volume, air traffic control, etc
- __*SECURITY_DELAY*__: Delay due to secruity issue
- __*LATE_AIRCRAFT_DELAY*__: Delay due to late arrival aircraft

## Data Exploration and Visualization
   - Interactive geo graph
   - Statistical analysis and graphs
   
## Machine Learning:
   - KNN
   - Random Forest
