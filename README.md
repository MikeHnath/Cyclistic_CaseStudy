# Cyclistic Bike-Share Analysis  
*Google Data Analytics Capstone – Case Study 1: How Does a Bike-Share Navigate Speedy Success?*

---

## 📌 Project Overview
This case study analyzes Q1 2019 and Q1 2020 Cyclistic (Divvy) bike-share trip data to identify usage differences between **annual members** and **casual riders**. The objective is to help the marketing team design strategies that convert casual riders into annual members — a more profitable and consistent customer segment.

This project follows the six-phase data analysis process from the Google Data Analytics Certificate: **Ask → Prepare → Process → Analyze → Share → Act**.

---

## 🎯 Business Task
**Key Question:** How do annual members and casual riders use Cyclistic bikes differently?  

From this analysis, actionable insights will support targeted marketing campaigns aimed at increasing annual memberships.

---

## 🗂 Project Structure & Navigation
| Step | File | Description |
|------|------|-------------|
| **1. Ask** | [01_Ask.md](01_Ask.md) | Defines the business problem, guiding questions, and stakeholders. |
| **2. Prepare** | [02_Prepare.md](02_Prepare.md) | Describes data sources, licensing, privacy considerations, and ROCCC evaluation. |
| **3. Process** | [03_Process.md](03_Process.md) | Details the cleaning, transformation, and data integrity checks. |
| **4. Analyze** | [04_Analyze.md](04_Analyze.md) | Contains visualizations, key findings, and interpretation of results. |
| **5. Act** | [05_Act.md](05_Act.md) | Outlines final recommendations and next steps. |

---

## 📊 Featured Visualization
![Monthly Rides by Year](monthly_rides_by_year.png)  
*Members maintain higher ride counts year-round, but casual riders’ rapid growth in March 2020 signals untapped conversion potential.*

### Usage Snapshot: Rides by Day of Week
![Rides by Day of Week](rides_by_day.png)  
*Weekday volume is member-heavy, supporting commuting patterns, while casual ridership spikes on weekends, reflecting leisure-focused use.*

---

## 🛠 Tools & Skills Demonstrated
- **Tools:** R (Posit Cloud), GitHub
- **R Libraries:** `tidyverse`, `lubridate`, `janitor`, `ggplot2`
- **Skills:**
  - Data import, cleaning, and transformation (type standardization, outlier handling)
  - Exploratory data analysis (EDA) & descriptive statistics
  - Year-over-year comparative analysis
  - Data visualization & **storytelling**
  - Reproducible workflow (R → Markdown → GitHub)
  - Business insight generation & **actionable recommendations**

---

## 📈 Key Insights
- **Members** ride more frequently on weekdays, suggesting commuting behavior.  
- **Casual riders** ride more on weekends and take longer trips, indicating leisure use.  
- Casual rider usage grew sharply in early 2020, offering an opportunity for targeted conversion campaigns.

---

## 📊 Quick Insights Summary
| Metric                      |  Casual | Members |
|:----------------------------|--------:|--------:|
| **Total rides** (Q1 2019+20) |  71,138 | 720,126 |
| **Avg ride length** (min)    |   36.5  |   11.4  |
| **Median ride length** (min) |   22.0  |    8.5  |
| **Weekend share of rides**   |  45.0%  |  16.6%  |

**Highlights:**  
- Members ride much more frequently but take shorter trips.  
- Casual riders ride fewer times but for longer durations, with nearly half of rides on weekends.  

---

## 💡 Recommendations Summary
1. **Target high-frequency casual riders** with cost-saving membership messaging.
2. **Convert weekend riders to weekday commuters** through promotions and employer partnerships.
3. **Use geo-targeted ads** near leisure hotspots during peak seasons.

Full recommendations are detailed in [05_Act.md](05_Act.md).

---

## 📜 Data License & Attribution
Data provided by [Divvy Bikes](https://divvy-tripdata.s3.amazonaws.com/index.html), operated by Motivate International Inc., under the [Data License Agreement](https://www.divvybikes.com/data-license-agreement).  
Cyclistic is a fictional company; Divvy trip data was used for educational purposes only.

---

## 👤 Author
**Michael Hnath**  
[LinkedIn](https://www.linkedin.com/in/michaelhnath) | [Portfolio](https://github.com/MikeHnath)

