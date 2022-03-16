# electricVehicleConsumptionAnalysis

This project is created as part of Udacity's nanodegree program "Data Scientist" and shows the results of the capstone project.

This Data Science project focusses on the "State of Charge" (SoC) of electric vehicles, explores dependencies to measures taken during 
a vehicle's trip, and makes predictions of the required battery power for a vehicle's trip.

For the analysis, a dataset is used which includes 70 trips of a BMW i3 in 2019 in and around Munich, Germany. Throughout the trips 
a variety of measures have been recorded, such as velocity, acceleration, ambient temperature, elevation, heating, air conditioning, 
motor torque, and more.


Summary of results:

We see that the State of Charge is dependent on other measures taken throughout the vehicle's trip: velocity, throttle, acceleration,
and motor torque. Additionally, we see a trend that a high difference between ambient and cabin temperature increases the power needed
to move the vehicle per kilometer.
Upon testing four regression techniques (Linear Regression, Decision Tree, Random Forest Regression, K Nearest Neighbor), we see that
the Random Forest Regression yields the best results with a mean of mean squared error of 15.45 and a median of 6.52.


Files in the repository:

Battery_and_Heating_Analysis.ipynb | contains all python code written for this analysis

battery_and_heating_data | contains all data in csv / xlsx format used for this analysis

     /Overview.xlsx | contains informations for every trip, e.g. date, region, and weather

     /Trip<A01 - B38>.csv | 70 files, one for each trip taken that show measures recorded while driving

README.md | contains all useful informations to get starting studying this project. This document is the README.md.


Python libraries used:

pandas
os
matplotlib
numpy
sklearn


Acknowledgements:

This project is conducted as part of the Udacity Nanodegree on Data Science. 
Please find further informations here: https://www.udacity.com/course/data-scientist-nanodegree--nd025

The rawdata for this project have been downloaded on kaggle. 
Please see https://www.kaggle.com/atechnohazard/battery-and-heating-data-in-real-driving-cycles

Author of this project is: F B 
Created in March 2022
