# Final-Project---TAKE-TWO
A refined version of my final project for Advanced Data Journalism. 

## Data
This analysis uses data from New York state's weekly Nursing Home Bed Census. Nursing facilities report their number of available beds each week. This analysis is based on data from the week of October 23: [Nursing_Home_Weekly_Bed_Census__Last_Submission_20241023.csv](https://github.com/user-attachments/files/18046041/Nursing_Home_Weekly_Bed_Census__Last_Submission_20241023.csv)

The spreadsheet contains the following columns which are relevant to the analysis: 
- Facility Name
- County
- Available Capacity
- Total Capacity

## Methodology
The notebook performs the following analyses: 
1. Cleaning data by checking for incomplete submissions and addressing typos in important columns.
2. Calculating the statewide vacancy and occupancy rate for nursing home beds.
3. Narrowing down the data to focus on specific counties in the Hudson Valley.
4. Using groupby to create a pivot table and add up the number of available / total beds per county. Add columns with calculations for the vacancy and occupancy rates to the pivot table.
5. Create a cleaned-up dataframe with the Hudson Valley vacancy / occupancy rates, and tack on the statewide calculations at the end. 
6. Export dataframe to .csv.

## Outputs
The notebook outputs this spreadsheet, which includes location, vacancy rates, and occupancy rates: [HV_Nursing_Home_Vacancies.csv](https://github.com/user-attachments/files/18046063/HV_Nursing_Home_Vacancies.csv)

## Running the Analysis Yourself
You can run the analysis yourself. To do so, you'll need the following installed on your computer:
- Python 3

## Licensing
All code in this repository is available under the MIT License. The data file in the output/ directory is available under the Creative Commons Attribution 4.0 International (CC BY 4.0) license. All files in the data/ directory are released into the public domain.

## Feedback / Questions?
Contact Jesse King at jesse.king1218@gmail.com
