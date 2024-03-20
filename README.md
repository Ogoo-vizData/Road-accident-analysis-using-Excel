# Road accident analysis using Excel
### Analysis and visualization of road accidents that occured between 2021 and 2022.

## Project overview
This project is based on road accidents data. The assumed clients want a road accident dashboard for the year 2021 and 2022. By analyzing various aspects of the data, contains data about accidents occurring with different influences like time, location or vehicle., we seek to identify trends, and make visualization to enable easier and adequate comprehension. 

## Data sources
The primary Data set used for this analysi is 'Road Accident Data(1)" file , containing details about road accidents occurences between 2021 and 2022.

## Tools
- Excel - Data cleaning, KPI creation and visualization.


## Data cleaning/preparation
In the intial data preparation phase, we performed the following tasks:
- Data Loading and inspection.
- Data cleaning and formatting.
- Two columns for year and month were created using the =TEXT(“***) formula on the date column for easier visualization. The latitude and longitude were put into the same decimal place.
Searched and removed any duplicate and void data.
Moved on to analyzing the data and the, I determined the percentage of each severity; which includes, slight, fatal and serious.


## Exploratory Data Analysis
- total casualties taken place after the accident.
- total casualties and percentage of total with respect to accident severity and maximum casualties by the type of vehicle.
- total casualties in accordance with different vehicles.
- comparison of both years in terms of casualties.
- maximum casualties by road type.
- distribution of total casualties by road surface.
- relation between casualties by area/location and by day/night.

## Data analysis

'''excel
=TEXT(B2,"YYYY")
To derive the year from the date column for easy analysis and visualization.

'''excel
=TEXT(B2,"mmm")
To derive the month from the data column

several KPIs were created for projection of the visualization

## Results and findings
The analysis result are summarized as follows:
- single carrage road type has a  significant high number of occurence and casualties when compared to the other road types.
- 2021 has higher number of accident causualties that 2022.
- Cars had a significant high accident occurence when compared to other vehicle types.
- The urban area has more accident occurence that the rural.
- Accidents occurs more during the day .

## Recommendations
Based on the analysis, I reccomend the following:
- Replacement of single carrage way with dual carrage ways 
- provison of more and efficient traffic measures in the urban areas.
- Enlightenment of Cra drivers to promote more caution.



