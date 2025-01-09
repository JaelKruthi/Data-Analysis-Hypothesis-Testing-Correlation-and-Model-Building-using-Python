# Business Case
The project analyzes historical flight data from New York to three major nearby airports: Dulles International Airport (IAD), Baltimore/Washington International Thurgood Marshall Airport (BWI), and Ronald Reagan Washington National Airport (DCA). 
The goal is to look at patterns with respect to flight delays, cancellations, and the factors influencing them. 
The analysis covers flight performance, weather conditions, federal holidays, and other factors such as aircraft types, airport performance, and airline reliability. 
By using this analysis, local authorities, airlines, and insurers can make more informed decisions to improve safety, reduce operational inefficiencies, and enhance customer satisfaction.

# Goal
Understand flight performance

Identify key factors influencing cancellations and delays

Optimize flight operations and customer satisfaction

Predict future delays and cancellations

Economic Impact Assessment

# Deliverables

Data Cleaning and Merging- Code to load and merge datasets like flight data, weather data, federal holidays, and airline details, Preprocessing steps to filter for relevant airports (IAD, BWI, DCA).

Data Analysis- Code for analyzing total seats available by airport, identifying the busiest days in terms of flights and seat availability, correlation between cancellations and weather conditions using hypothesis testing, calculate cancellation ratios for airlines and identify the most and least reliable airlines.

Visualizations- Plots to show daily average delays, the impact of holidays on delays, and seat availability over time, Pie charts, bar graphs, and line plots for the analysis of delays, cancellations, and airline performance.

Hypothesis Testing and Statistical Models- Code for hypothesis testing to understand the impact of weather on cancellations, Code to assess the relationship between federal holidays and cancellations.

Predictive Modeling- Linear Regression model for predicting arrival delays based on various features, Logistic Regression model for predicting cancellations on test data.

# Results and Evaluation
Flight and Seat Analysis

Cancellation Analysis

Arrival Delay Analysis

<img width="300" alt="image" src="https://github.com/user-attachments/assets/0c2ad688-3c30-450e-83ff-d56f79d10c82" />

Predictive Models
The Linear Regression model showed a good fit for predicting delays based on features like departure time, weather, and distance.
The Logistic Regression model effectively predicted cancellations with a high degree of accuracy based on variables like weather conditions, flight time, and holidays.

<img width="300" alt="image" src="https://github.com/user-attachments/assets/74761612-c8f2-4bc3-99a4-05c253a7cfe0" />

# Business Impact
By identifying the most and least reliable airlines, airports, and flight times, airlines can optimize schedules and allocate resources more efficiently.

Understanding when delays and cancellations are most likely to occur enables airlines to proactively manage customer expectations and improve the travel experience. This could lead to fewer complaints and higher customer satisfaction.

By analyzing the correlation between flight delays and weather conditions, airlines can adjust their schedules to reduce delays during adverse weather conditions.

Insurers can use this data to identify risk factors and optimize pricing for flight-related policies. This could help them assess potential compensation claims for flight cancellations more accurately.

Local authorities can use the findings to improve infrastructure and manage traffic flow at the busiest airports, particularly during holidays and peak seasons.

# Next Steps
Implement a real-time flight monitoring system that uses weather data and historical trends to provide real-time predictions for delays and cancellations.

Develop optimization algorithms for flight scheduling that minimize the impact of weather conditions and federal holidays on operations, while maximizing resource utilization.

Expand the analysis to other airports beyond IAD, BWI, and DCA, to build a nationwide model for flight performance optimization.
