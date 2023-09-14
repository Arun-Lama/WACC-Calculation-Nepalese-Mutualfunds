# Purpose

This code can be used to calculate WACC for each unit holder of Nepalese mutual funds. The WACC is calculated based on the trades done by the unit holder. The WACC of a unit holder is also impacted by the units of fund they are alloted during the IPO. Therefore, it is crucial to merge the IPO allottment data to the floorsheet csv file before running the program. 

# Floorsheet Format (Input)
The floorsheet format is as provided by NEPSE. New calculated columns should be added to calculate broker and sebon comission. Effective rate should be calculated for each transaction in the floorsheet. 
![Floorsheet format](https://github.com/Arun-Lama/WACC-Calculation-Nepalese-Mutualfunds/blob/a3038d03b7d028cf2b9ee780c2c3a7c1a0f062c5/output%20format.png)

# Output 
Upon running the program, excel file will be created for each unit holder with two sheets within the file. One sheet contains the trade history of the client while the other contains the WACC value with remarks. 
In the end the summary excel file is created where WACC and remarks for each client is merged. 
![Final output excel format](https://github.com/Arun-Lama/WACC-Calculation-Nepalese-Mutualfunds/blob/519e298efdf5c1b2fd14078015ccae9aeac09b94/WACC%20OUTPUT.png)

# Contribution
Any kind of contribution is appreciated. 
