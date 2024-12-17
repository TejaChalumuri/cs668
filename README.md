# NYC Gun Violence(HISTORIC:2006-2023)

Tejalakshmi Gangadhar / Chalumuri


* *This work was realized as part of the capstone project of the MS in Data Science at Pace University*
 
* **Abstract:** The current research explores the following: (1) the spatial and temporal patterns of gun violence in New York City's urban neighborhoods from 2006 to 2023. By utilizing a dataset on the shooting incidents obtained from the NYPD Historical Shooting Incidents, the research (2) applies EDA and machine learning methods to investigate the trend, locate high-risk zones, and present demographic distribution of the affected population. Results indicated (3) distinct temporal patterns in shooting incidents, with certain neighborhoods and demographic groups disproportionately affected. Finally, (4) the study concludes that leveraging data-driven insights can inform targeted interventions and recommends integrating predictive analytics to enhance urban safety initiatives.
 
* **Dataset:** The dataset used for this analysis is  from NYC Open Data. It contains detailed records of shooting incidents across New York City from 2006 to 2023, with over 28,000 records and 25 variables.
  * Key Variables: Date, Borough, Location Type, Victim and Perpetrator Demographics
  * Size: 28,562 records × 25 columns
  * Observations: Some columns have high missing values, such as LOC_OF_OCCUR_DESC and LOC_CLASSFCTN_DESC, with about 25,596 missing entries, impacting location-specific analysis. The column LOCATION_DESC  has 14,977 missing entries, which could affect spatial analysis.
  * The dataset is available here: https://data.cityofnewyork.us/Public-Safety/NYPD-Shooting-Incident-Data-Historic-/833y-fsy8/about_data
   
* **Methodology:**
   * Data Preparation: Loading NYC shooting incident data from 2006 to 2023, checking for missing values, examining data types, and generating summary statistics. Temporal fields (e.g., occurrence date and time) are converted to date-time formats to facilitate analysis. 
   * Additional temporal features such as year, month, and weekday are created to support trend analysis.
   * Trend Analysis:
      * Yearly and Monthly Trends: Aggregating incident data by year and month to observe long-term trends and seasonal fluctuations in gun violence.
      * Weekly Trends: Identifying patterns by day of the week, with a particular focus on weekends, which show higher incidents.
  * Spatial and Demographic Analysis:
      * Borough Distribution: Grouping incidents by borough to understand the geographic distribution of shootings and identify areas with higher incident rates, with Brooklyn and the Bronx showing consistently high counts.
      * Victim Demographics: Analyzing the age and gender of victims to highlight demographic groups most affected by gun violence, with males aged 18-44 being predominant victims.
  * Predictive Modeling: Considering machine learning techniques (e.g., random forest) to predict high-risk neighborhoods and times for shootings. Model performance is evaluated using metrics such as accuracy, precision, recall, and F1-score.
* Code : https://github.com/TejaChalumuri/cs668/blob/146d89657259696b3306d7eb3a4ca4a5faf38772/NYC_Gun_Violence(HISTORIC2006_2023).ipynb
 
* **Results:**
  * Annual, Seasonal, and Neighborhood Changes: Gun violence in NYC has been decreasing but some communities remain a feature of concern, similar to the situation in the past. As per the analysis, some peak seasons within the year exist, for example summer, which suggests more time spent on the street.

  * Impact on Certain Neighborhoods and Demographic Groups: According to many sources, Brooklyn and Bronx areas show the most murder/suicide tendencies and are sustained predominantly by males aged 18-44.

  * Timing and Geographies of High Frequency: Nighttime, late hours, especially where there are active social events are likely to have a shooting incident. Recurrent geographical areas of crime and offending neighborhoods are at significantly higher risk suggesting the areas warrant preventive measures. High Risk shooting are and timing have been predicted using Random Forest method with an accuracy of 90%.

 
* Poster (as an image)
  

![NYC Gun Violence(HISTORIC2006-2023)-Poster](https://github.com/user-attachments/assets/4d999f10-6ba0-4bd0-a9ac-6922b33e7f22)

 
 
