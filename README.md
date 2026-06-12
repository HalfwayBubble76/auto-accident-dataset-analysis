Instructions for this assignment are as follows -

In the Auto Accident Dataset Microsoft® Excel® spreadsheet, clean and prepare the data from the Auto Accident Dataset and:

Check for and remove duplicate records.

Convert column A: CASENUM to an integer value.

Enumerate column G: URBANICITYNAME and place a 1 in column F: URBANICITY if column G is urban area and place a 2 in column F if column G contains rural area.

Create a frequency chart and a PivotTable using your cleaned and prepared auto accident data. Use the following requirements:

Frequency chart: Show the total number of auto accidents in rural and urban areas using data from column G: URBANICITYNAME, total number of auto accidents that occur by day of the week using data from column N: DAY_WEEKNAME, and total auto accidents by weather conditions using column AG: WEATHR_IMNAME.

PivotTable: Using Excel, create a PivotTable in a new tab that includes the following information from the auto accident data: region (column D: REGION), month (column J: MONTH), harm (column T: HARM_EVNAME), weather conditions (column X: LGT_CONDNAME), weather type (column AB: WEATHERNAME), and lighting (column AF: LGTCON_IMNAME).

Step 1: Cleaned the dataset following the instructions.

        1) Converted CASENUM column to number, removed decimal point.
        
        2) Used "IF" formula to enumerate URBANICITY column based on whether URBANICITYNAME column showed rural or urban.
        
Step 2: Followed instructions to create Frequency Chart in Excel

        1) Quickly observed there are more accidents in urban areas than rural areas.
        
        2) Quickly observed the two days of the week with the highest amount of accidents are Thursday and Friday in both rural and Urban areas, and the day with the least amount of accidents is Sunday.
        
Step 3: Followed instructions to create PivotTable in Excel

        1) Observed that most of the data is from the month of January, 2020. There is 1 record from August, 2020.
        
Step 4: Converted .xlsx file to .csv

Step 5: Loaded .csv file into python for exploratory data anlaysis
