# Cyclistic_CaseStudy
Data analysis of Q1 2019 and Q1 2020 Divvy bike-share trips to identify differences in usage between annual members and casual riders. Conducted in R (Posit Cloud) using tidyverse, lubridate, and ggplot2. Includes data cleaning, year-over-year trend analysis, visualizations, and marketing recommendations to convert casual riders into members.

## Business Question
**How do annual members and casual riders use Cyclistic bikes differently?**

---

## Key Findings

### 1. Ride Volume by Day of Week
![Average Ride by Day](rides_by_day.png)

- **Members** ride heavily during weekdays (Mon–Fri), suggesting commuting or regular travel.
- **Casual riders** ride far more on weekends, indicating leisure and recreational trips.
- Members consistently take more rides overall compared to casuals.

---

### 2. Average Ride Length by Day
![Rides by Day](avg_ride_by_day.png)

- **Casual riders** take longer rides across all days, with peak ride lengths on weekends (~35+ minutes).
- **Members** average shorter, consistent ride lengths (~11–13 minutes), aligned with quick commutes.

---

### 3. Monthly Rides Year-over-Year
![Monthly Rides by Year](monthly_rides_by_year.png)

- In **Q1 2019** and **Q1 2020**, members maintained higher total ride counts.
- Casual rides grew more sharply in early 2020, especially in March.
- Growth in casual rides could be leveraged for membership conversion campaigns.

---

### 4. Year-over-Year Weekday Patterns
![YoY Weekday Bar by User Type](yoy_weekday_bar_by_user_type.png)

- Weekday riding patterns are stable year-over-year for both groups.
- Weekend ridership for casuals showed stronger growth from 2019 to 2020, indicating leisure demand is increasing.

---

## Interpretation

1. **Members** display consistent weekday usage and shorter trips, likely driven by commuting needs.  
2. **Casual riders** favor weekends and take longer trips, showing a recreational focus.  
3. Casual ride growth in early 2020 highlights an opportunity to capture leisure riders with targeted promotions before peak season.

---
