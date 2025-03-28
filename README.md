# Analysing-Flight-Delays-and-Cancellations

# Overview

This project analyses flight departure delays and cancellations for an airline operating in the Pacific Northwest. Using historical flight and weather data, we explore factors influencing delays and cancellations to improve operational efficiency and passenger experience.

# Objectives

- Identify flight routes with the highest delays and cancellations.
- Determine airlines with the longest average departure delays.
- Assess the impact of weather conditions, particularly wind speeds, on departure delays.
- Provide recommendations for improving flight scheduling and mitigating delays.

# Data Source

The dataset is sourced from the 'pnwflights2022' datasets available from the ModernDive team. It contains:
  - flights2022.csv – Flight details including departure time, delay duration, origin, destination, and airline.
  - flights_weather2022.csv – Flight information along with weather conditions such as visibility and wind gust speeds.

# Tools Used

- Programming: Python
- Libraries: Pandas, Matplotlib
- Data Visualisation: Matplotlib

# Insights

- Routes with the highest mean departure delays were identified.
- Airlines with the most delays and cancellations were analysed.
- Wind speeds above 10 mph tend to increase departure delays at SEA and PDX airports.

![f1](https://github.com/user-attachments/assets/303dfbc3-8c33-4631-900e-db75e532bab7)
![f2](https://github.com/user-attachments/assets/e2a9ced0-62c0-40a0-9b3d-1b9623991939)


# Key Findings

- Certain routes experience significantly higher delays than others, requiring deeper investigation into operational challenges.
- Some airlines consistently face longer departure delays, possibly indicating operational inefficiencies.
- Higher wind speeds are correlated with increased delays, affecting flight schedules.

# Recommendations

- Operational Improvements: Airlines should investigate routes with the highest delays and optimise scheduling.
- Weather Considerations: Improve contingency planning for high-wind conditions to reduce delays.
- Customer Experience: Provide real-time updates and alternative options for passengers affected by frequent cancellations.

# How to Use this Repository

1. Clone the repository and navigate to the project directory.
2. Ensure all dependencies (e.g., Python, Pandas, Matplotlib) are installed.
3. Run the Jupyter Notebook or Python script to explore flight delays and visualisations.
4. Modify parameters to analyse specific routes, airlines, or weather impacts.
