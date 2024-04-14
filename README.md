# Data Insights for STEM Advantage

<img src="https://github.com/EddyBoror/Data-Analyst-Visualization-Specialist-at-STEM-Advantage/blob/Analysis-Projects/stem_advantage_cover.jpg" width="1700" height="250" />

# Project Overview

In collaboration with the NVIDIA team and STEM Advantage, I extracted data from the CSU data center, focusing specifically on STEM-related majors across eight designated CSU campuses participating in the STEM Advantage Scholar Program. The scope of the project spanned from 2012 to 2023.

Campuses:
- Cal Poly Pomona
- Cal State Dominguez Hills
- Cal State Fullerton
- Cal State LA
- Cal State Long Beach
- Cal State Northridge
- Cal State San Marcos
- San Diego State University

<br>

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
<img src="https://github.com/EddyBoror/Data-Analyst-Visualization-Specialist-at-STEM-Advantage/blob/Analysis-Projects/Dataset_Sample.JPG"  width="1700" height="750" />
- Downloaded CSU Dataset CSV file comprising 23 CSU system-wide campuses.
- The dataset included pivot tables and multiple worksheets containing varied information on Gender, Age, Campuses, disciplines, majors, and ethnicity.
- Extracted data pertaining to the eight CSU campuses targeted by the STEM Advantage organization, focusing on STEM major information to ensure accuracy in project analysis.
3. Handling missing values.
4. Data cleaning and formatting.

<br>

# Exploratory Data Analysis

### Python Analysis
- Please check here for my cleaning, analysis, and visualization using [Python](https://github.com/EddyBoror/Los-Angeles-County-Arrest-Data-Analysis/blob/main/Final%20Cleaned%20Arrest%20Dataset.ipynb) libraries.

### Geospatial Crime Analysis:

  - Explore trends in arrest frequencies across diverse locations on a geographic map.

<img src="https://github.com/EddyBoror/Los-Angeles-County-Arrest-Data-Analysis/blob/main/Geo%20City.png" width="1000" height="700" />

### Demographic Analysis:
  - Are certain age groups or genders more frequently involved in arrests?

### Arrest Type Breakdown::
  - What is the distribution of arrest types (e.g., misdemeanor, felony) in the dataset?

<img src="https://github.com/EddyBoror/Los-Angeles-County-Arrest-Data-Analysis/blob/main/Gender%20Age%20Arrest.png" width="1000" height="700" />

<br>

# Data Statistical Summary

- The dataset primarily consists of "BOOKING" entries, indicating that a significant portion of the records corresponds to booking-related activities.

- The dataset records 3,772 instances of the common arrest time, around 1:00 PM, indicating a concentrated period for law enforcement activity.

- The most common area for arrests is "Rampart," with 18,632 occurrences, indicating a higher concentration of law enforcement activities in this region.

- The dataset indicates a higher frequency of male persons involved in arrests due to the majority of males (202,282 occurrences). Furthermore, "H," which has been recorded 131,366 times, is the most often occurring descent code, suggesting a concentration of arrests involving people of Hispanic heritage.

# Conclusion Analysis

The analysis of this data can be helpful for both people in the community and law enforcement. For pedestrians, it gives insights into when and where arrests commonly happen, helping them make informed decisions about their safety. Understanding the patterns in arrests, like the higher frequency for males and individuals of Hispanic heritage, can also contribute to a better awareness of law enforcement interactions.

Law enforcement can use the data to find patterns in the locations, timeframes, and kinds of charges associated with arrests. This data allows resources to be allocated more effectively and total operational effectiveness can be raised. Law enforcement can improve its tactics and procedures by better understanding the most frequent charges and the typical outcomes of arrests. Ultimately, this data analysis encourages safety and openness by supporting a more knowledgeable and cooperative interaction between the community and law enforcement.
