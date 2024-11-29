# DSA210PROJECT
Hello I am Halis Cem Şahin (31035) and, I am doing my project on my health data and weather data. 
### **Activity and Weather Relationship Analysis**

#### **Motivation:**
This project explores how weather conditions impact daily activity levels. By analyzing my step count data and weather patterns, I aimed to uncover trends and improve daily routines for better health outcomes.

#### **Data Source:**
1. **Step Count Data:** Extracted from the Apple Health app, providing daily steps for 2024.
2. **Weather Data:** Retrieved from Meteostat, including temperature, precipitation, and weather conditions, merged with step data using dates.

#### **Data Analysis:**
1. Cleaned and merged datasets for consistent analysis.
2. Conducted EDA to visualize step counts across different weather conditions.
3. Examined correlations between step counts and weather variables.
4. Analyzed seasonal trends to understand how behavior changes over time.

#### **Findings:**
- Higher activity levels on sunny days (~30% more steps than rainy days).
- Moderate temperatures (15°C to 25°C) correlated with the most steps.
- Winter months showed a noticeable decline in activity due to weather.

#### **Limitations and Future Work:**
- Single-year data may not reflect long-term trends.
- Adding variables like personal schedules or time of day could enhance insights.
- Future work includes multi-year data analysis and step count prediction models using weather forecasts.

  
#### **Methodology:**
  # Data Collection: 
    - Health Data: Personal data such as step count, heart rate, and sleep patterns will be extracted from the export.xml file exported from Apple Health. 
    - Weather Data: Historical temperature data will be obtained from a reliable weather API or CSV dataset for the corresponding dates will be extracted from the       export.xml file exported from Meteostat. 
  # Data Cleaning and Preprocessing: 
    - Use Python libraries such as Pandas to parse and clean the health data. Synchronize the health data with daily temperature records. 
  # Exploratory Data Analysis (EDA): 
    - Visualize step counts and temperature trends over time using Matplotlib and Seaborn. Compute basic statistics like mean, median, and correlation between step       count and temperature. 
  # Hypothesis Testing:
    - Conduct statistical tests to determine if there is a significant relationship between temperature and step count. 
  # Visualization:
    - Create scatter plots, heatmaps, and line graphs to illustrate findings clearly. 
  # Insights and Recommendations: 
    - Summarize key trends and provide actionable insights based on the analysis.

This project demonstrates how personal data can reveal meaningful insights to optimize daily habits and achieve health goals more effectively.
