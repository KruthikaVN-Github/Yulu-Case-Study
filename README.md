# Yulu - Hypothesis Testing

**About Yulu**  
Yulu is India’s leading micro-mobility service provider, offering innovative vehicles designed for daily commutes. With a mission to reduce traffic congestion, Yulu provides a safe and sustainable commuting solution through its user-friendly mobile app. Yulu zones are strategically located near metro stations, bus stops, offices, residential areas, and corporate hubs, ensuring seamless, affordable first and last-mile connectivity. Recently, Yulu has faced a significant decline in revenue and has enlisted a consulting firm to analyze the factors influencing the demand for its shared electric cycles in the Indian market.  

**Problem Statement**  
The company aims to address the following:  
- Identify the key variables that significantly impact the demand for shared electric cycles in the Indian market.  
- Evaluate how effectively these variables explain the variations in demand.  

| **Column**      | **Description**                                                                                       |
|------------------|-----------------------------------------------------------------------------------------------------|
| **datetime**     | Date and time of the activity                                                                       |
| **season**       | Seasons (1: spring, 2: summer, 3: fall, 4: winter)                                                  |
| **holiday**      | Indicates if the day is a holiday (data extracted from [DC.gov Holiday Schedule](http://dchr.dc.gov/page/holiday-schedule)) |
| **workingday**   | 1 if the day is neither a weekend nor a holiday, otherwise 0                                        |
| **weather**      | Weather conditions categorized into four types:                                                     |
|                  | 1: Clear, Few clouds, partly cloudy                                                                 |
|                  | 2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist                                     |
|                  | 3: Light Snow, Light Rain + Thunderstorm + Scattered clouds                                         |
|                  | 4: Heavy Rain + Ice Pellets + Thunderstorm + Mist, Snow + Fog                                       |
| **temp**         | Temperature in Celsius                                                                             |
| **atemp**        | "Feeling" temperature in Celsius                                                                   |
| **humidity**     | Humidity level                                                                                     |
| **windspeed**    | Wind speed                                                                                         |
| **casual**       | Count of casual users                                                                              |
| **registered**   | Count of registered users                                                                          |
| **count**        | Total count of rental bikes, including both casual and registered users                            |

**Key Objectives**  
- Imported and analyzed the dataset to understand its structure.  
- Explored relationships between the demand variable "Count" and other independent factors.  
- Analyzed the effect of "Workingday" on cycle rentals.  
- Compared rental demand across different seasons and weather conditions.  
- Investigated the dependency of "Weather" on "Season."  
- Formulated null (H0) and alternative (H1) hypotheses for various tests.  
- Checked assumptions of normality and equal variance for hypothesis testing.  
- Proceeded with analysis despite assumption violations, where necessary.  
- Set a significance level (alpha) for hypothesis testing.  
- Computed relevant statistics for each hypothesis and drew conclusions.  
- Generated insights into the factors driving demand for shared electric cycles.  
