# Chicago_Crime_Analyzer

# Problem Statement:
The increasing complexity and volume of crime data present significant challenges for law enforcement agencies and policymakers. Understanding patterns in criminal activities, identifying high-risk locations, and analyzing trends over time are crucial for effective decision-making. However, the lack of accessible insights from raw crime data hinders the ability to allocate resources efficiently, predict future crime occurrences, and enhance community safety. Furthermore, assessing the effectiveness of arrests and understanding the impact of different crime types remain underexplored. This project aims to address these challenges by analyzing the provided dataset to uncover actionable insights and trends, ultimately aiding in crime prevention and fostering safer communities.

# Approach to the project:

# Phase 1:
# Python:
With the Provided dataset, I perfomed Data cleaning and EDA using python (Pandas) in the Jupiter notebook. I have replaced missing values, duplicate values in the columns of the dataframe and created new columns that would help from analysis in phase 2. After that, I have pushed the cleaned dataframe into postgres SQL to try the import functionality from postgres SQL server in power bi. Also, I have taken a copy of the cleaned dataset to provide to the stakeholders.
To know the detailed steps, click here to access my python file in githib repo.

# Phase 2:
# Power BI:
Imported the data from the SQL database using the postgres SQL server option. Created individual sheets in power BI for each approach as mentioned in the Problem statement. Used the same visualizations/Filters as mention in the problem statement.
I have provided my insights and screenshot below refering.

# Visualization and Reporting

![image](https://github.com/user-attachments/assets/2a3073fb-39e4-4902-8d17-e1a84001fac6)

- On Analyzing the cleaned data on high level, I was able to determine the following points for the crime report between 2000 to 2024.
- Total numbers of crime registered -  549.43K
- Crime locations identified -162
- Crime Types Reported – 33
- Most type of crime reported is Theft
- The more number of crimes were reported on the year 2000 (i.e 0.34M)
- May month is the where the more crimes ocuured.
- Thursday is where more crimes happen.

  # Temporal Analysis:

  ![image](https://github.com/user-attachments/assets/b657ff13-4bab-463f-a05b-b953abe22256)

- I’ve used line charts for the temporal analysis, to analyse the crimes registeres across years, months, Quarter, day_of_week and date.
- Among which the line chart will show crime trends on month, quarter, day_of_week and date. Used Year as an interactive slice filter and cases numbers in card to find the total crimes registered
- According to the analysis, Most crimes are reported in March across these years, followed by May and April.
- The Most crimes are most likely to occur on 1st Quarter of the year and within first 10 days of the month. And Most crimes has been occurred on Thursday, followed by Tuesday and Sunday.

# Peak crime Hours:

![image](https://github.com/user-attachments/assets/60d3f914-b201-4cec-b6f9-2d2ccdeeaaa3)

- I’ve used heatmap here to differentiate and the crimes and their occurring hours and highlight the most crime occurring hours of each type.
- Among the data we got, the most occurred crime is THEFT and it occurs almost every hour in a day followed by Battery.
- The Most crimes has occurred on midnight 12.00 AM, followed by 6.00PM.
# Prevention Mechanism suggested:
Increase patrolling size on the suggested time to reduce the movement of the offenders , thus reducing the crime occurring rates.


# Geospatial Analysis:

![image](https://github.com/user-attachments/assets/e79da197-c4df-43a1-a6ca-bfa0909670ed)

- To identify the crime hotspots, across the years, I have used Geospatial maps to see the density of crimes happened across the locations in Chicago.
- Airport and the places surrounded to it, is the found as most crime happened places.
- More crimes occur near the coastal residential building area, as they have high people traction, hence crime offenders see that as a chance to escape after committing the crime.

# Crime Type Analysis:

![image](https://github.com/user-attachments/assets/cff00743-f8c6-4405-bab2-837c9de02688)

- Used Tree map to segregate the whole picture, to see where the crime type stands in a whole picture, rather than numerical representation.
- Non – severe crimes are the most occurring crimes standing at 81.25%. This shows the most offenders make crime to lead their day to day life. 
- Theft is the most happening non-severe crime, followed by Battery. And Assault is the more occurring severe crime followed by Narcotics.
- Narcotics may also be the reason for the non –severe crimes as the offenders need huge money to buy illegal substances.
# Prevention Mechanism suggested:
- Ensure severe laws in place for crimes related to Narcotics and its subsequent crimes to prevent other non-severe crimes in the city.

# Arrest and Domestic Incident Analysis:

![image](https://github.com/user-attachments/assets/e9d49aac-ed01-4274-a2ac-c47bc12b630c)

- By analyzing the Arrest and domestic incidents, more arrest has been happened on Battery crime with 3.69% has been arrested in total reported crimes for battery.
- Comparing domestic and non-domestic, more crimes has happened in non-domestic regions.
- Battery is the most occurred crime in domestic type. And Theft is most occurred crime in Non – domestic type.

# Location-Specific Analysis:

![image](https://github.com/user-attachments/assets/e64b4fc8-0782-4ba8-ab15-e94c3270ba5a)

- According to the location specific analysis, I could see more crimes has happened in the street 165.84k, in which theft stands first. Following Residence with 90.20K.
- 
# Prevention Mechanism suggested:
- Police patrolling in streets and residential areas will help to reduce the crimes in future.

# Seasonal and Weather Impact Analysis:

![image](https://github.com/user-attachments/assets/8a0bf5c7-17d5-4f3a-a9e1-83daf54085c7)

- On Seasonal analysis, offenders prefer Spring as a likely season for more crimes, followed by winter, autumn and summer.
- Every crime type reported follows the same procedure, as Spring has more number of tourist attraction in Chicago.
# Prevention Mechanism suggested:
- Security should be increased on Spring seasons and coastal areas should be focused more.

# Risk Assessment:

![image](https://github.com/user-attachments/assets/997319e3-d82f-4151-bc84-f2208c0a8dd3)

- On conducting risk assessment, I could see that more crimes are registered in the street and residential area, targeting family crowd as they not tend to resist the offenders much rather than saving themselves.
- Also the criminals use most crowded areas for the severe crimes as option to escape from the crimes.
# Prevention Mechanism suggested:
- Segregate the crime spots using the high crime rates and focus deploying more forces in location, ward and districts to prevent and reduce crime rates.
- Setup mobile police stations on highly crime reported areas to prevent non-severe crimes drastically.









