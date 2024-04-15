# Data Insights for STEM Advantage

<img src="https://github.com/EddyBoror/Data-Analyst-Visualization-Specialist-at-STEM-Advantage/blob/Analysis-Projects/stem_advantage_cover.jpg" width="1700" height="250" />

# Project Overview
STEM Advantage (SA) is seeking assistance extracting, utilizing, and presenting publicly accessible data from CSU (California State University) to extract relevant information to show potential donors. SA's chief goal is to acquire funding from corporations and foundations to support the enrollment of ethnic minority, female, and first-generation students at CSU.

Collaborating with the NVIDIA team and STEM Advantage, I extracted data from the CSU data center, focusing specifically on STEM-related majors across eight designated CSU campuses participating in the STEM Advantage Scholar Program. The scope of the project spanned from 2012 to 2023. Lastly, focus on ethnicity and first-generation status, specifically targeting Hispanic/Latino and African American students.

Campuses:
- Cal Poly Pomona
- Cal State Dominguez Hills
- Cal State Fullerton
- Cal State LA
- Cal State Long Beach
- Cal State Northridge
- Cal State San Marcos
- San Diego State University

<be>

# Issues

- SA’s previous Tableau resource stopped collecting data in 2022. 
- CSU’s public website hosts data visualizations covering all student demographics. However, the lack of transparency -regarding the data source constrains the potential for thorough data analysis.
- The CSU public website provides raw data without filtering based on STEM majors or demographic key performance indicators (KPIs).




# Data Sources

CSU Data: The data utilized for the analysis and cleaning originates from the CSU data center's statistical reports, which specifically concentrate on undergraduate and graduate data
  - [Download here][(https://data.lacity.org/Public-Safety/Arrest-Data-from-2020-to-Present/amvf-fr72/about_data)](https://www.calstate.edu/data-center/institutional-research-analyses/Pages/reports-and-analytics.aspx)
  - Filter: College Year | CSU Undergraduate and Graduate Degrees Granted | Year: 2010 - 2023

<img src="https://github.com/EddyBoror/Data-Analyst-Visualization-Specialist-at-STEM-Advantage/blob/Analysis-Projects/CSU%20Data.JPG"  width="1700" height="550" />


<br>

# Tools

- Excel: Data Source
- Tableau: Building interactive dashboards for comprehensive data representation.

<br>

# Data Cleaning/ Preparation

In the initial data preparation phase, I performed the following tasks in Excel:

1. Data loading and extracting from the original CSU Dataset
- <img src="https://github.com/EddyBoror/Data-Analyst-Visualization-Specialist-at-STEM-Advantage/blob/Analysis-Projects/Dataset_Sample.JPG" width="1700" height="750" />
- Downloaded CSU Dataset CSV file comprising 23 CSU system-wide campuses.
- The dataset included pivot tables and multiple worksheets containing varied information on Gender, Age, Campuses, disciplines, majors, and ethnicity.
- Extracted data pertaining to the eight CSU campuses targeted by the STEM Advantage organization, focusing on STEM major information to ensure accuracy in project analysis.
  <br>
  <br>
  <br>
2. Data formatting
- The original CSU dataset included worksheets irrelevant to the project's objectives. Consequently, I created a new worksheet categorized by campuses and descriptions to streamline the data for analysis.
<br>
<br>
<br>

3. Data Transformation
- Adjusted the worksheet to include a new "Zipcode" column alongside the existing "Campuses" column to enhance future visualization capabilities.
-  Grouped other ethnicities not falling under the two targeted objectives into a category labeled "Others" to ensure accurate analysis
- Created new columns for "Discipline" and "Major," specifically encompassing three STEM categories: Engineering, Information Sciences, and Mathematics.
- <img src="https://github.com/EddyBoror/Data-Analyst-Visualization-Specialist-at-STEM-Advantage/blob/Analysis-Projects/major_fixes.JPG" width="1700" height="750" />

<br>

# Exploratory Data Analysis

### Excel 1 (Non-Technical Data Analysis & Visualization) 
- Created a worksheet named "Undergraduate Degree Granted," which includes data on students earning their undergraduate degrees across eight campuses. It features pivot charts and line charts with filters, enabling STEM Advantage to pinpoint specific years and campuses for their review.

![EXCEL_f8KVcfr5s9](https://github.com/EddyBoror/Data-Analyst-Visualization-Specialist-at-STEM-Advantage/assets/61037075/0b1f065a-0b1a-4d4a-9ec2-84071ec5868b)

- Campus Comparison: CSU Fullerton consistently grants the highest number of degrees throughout the years, followed by CSU Long Beach and CSU Los Angeles. 

- Overall Growth: The total number of degrees granted by CSU has steadily increased over the years, with a notable increase from around 36,500 in 2011-12 to over 57,500 in 2022-23.

### Excel 2 (Non-Technical Data Analysis & Visualization) 

  - Explore trends in arrest frequencies across diverse locations on a geographic map.

![EXCEL_gLA0k4uVha](https://github.com/EddyBoror/Data-Analyst-Visualization-Specialist-at-STEM-Advantage/assets/61037075/03f4bced-0fd5-4ec7-9fac-000e1cbb9cbb)

Gender Distribution by Discipline Category:
- Engineering: There is a significant gender disparity, with more males (31,713) than females (6,548) across all campuses.
- Information Sciences: The gender distribution is more balanced, with 12,902 males and 2,209 females.
- Mathematics: There are more males (2,822) than females (2,321).

Campus Comparison:
- Pomona appears to grant the highest number of degrees across all disciplines, with particularly high numbers in Engineering and Information Sciences.
- Dominguez Hills has the lowest number of degrees granted across all disciplines.

Insight on Female Representation:
- There needs to be more female representation in Engineering across all campuses, with significantly lower numbers than males. This indicates potential areas for improvement in promoting diversity and inclusion in STEM fields.


### Tableau Dashboard
https://github.com/EddyBoror/Data-Analyst-Visualization-Specialist-at-STEM-Advantage/assets/61037075/bdae9ffd-db08-41cd-b4b7-fd47c0fefc58
- I've developed a Tableau Dashboard intended for use on the STEM Advantage website, showcasing potential donors' statistics categorized by STEM discipline, year, and gender. This dashboard will facilitate the creation of a narrative highlighting the areas of focus within CSU served by the organization and the potential impact of donors' contributions on students enrolled in the scholar program.



<br>

# Data Statistical Summary

- The dataset primarily consists of "BOOKING" entries, indicating that a significant portion of the records corresponds to booking-related activities.

- The dataset records 3,772 instances of the common arrest time, around 1:00 PM, indicating a concentrated period for law enforcement activity.

- The most common area for arrests is "Rampart," with 18,632 occurrences, indicating a higher concentration of law enforcement activities in this region.

- The dataset indicates a higher frequency of male persons involved in arrests due to the majority of males (202,282 occurrences). Furthermore, "H," which has been recorded 131,366 times, is the most often occurring descent code, suggesting a concentration of arrests involving people of Hispanic heritage.

# Conclusion Analysis

The analysis of this data can be helpful for both people in the community and law enforcement. For pedestrians, it gives insights into when and where arrests commonly happen, helping them make informed decisions about their safety. Understanding the patterns in arrests, like the higher frequency for males and individuals of Hispanic heritage, can also contribute to a better awareness of law enforcement interactions.

Law enforcement can use the data to find patterns in the locations, timeframes, and kinds of charges associated with arrests. This data allows resources to be allocated more effectively and total operational effectiveness can be raised. Law enforcement can improve its tactics and procedures by better understanding the most frequent charges and the typical outcomes of arrests. Ultimately, this data analysis encourages safety and openness by supporting a more knowledgeable and cooperative interaction between the community and law enforcement.
