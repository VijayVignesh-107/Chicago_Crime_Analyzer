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






