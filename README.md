# 🚲 Cyclistic Bike-Share Analysis
### How do casual riders and annual members use Cyclistic bikes differently?

**Author:** Adrian Willis | **Tools:** Python · Excel · BigQuery SQL · Jupyter Notebook · Tableau

---

## Project Overview
This project is the Google Data Analytics Professional Certificate capstone case study.
As a junior data analyst for the fictional bike-share company Cyclistic, I was tasked
with analyzing 12 months of ride data to uncover behavioral differences between casual
riders and annual members — and use those insights to recommend a marketing strategy
to convert casual riders into members.

The analysis follows the full data analysis process: **Ask → Prepare → Process →
Analyze → Share → Act.**

---

## Key Findings

🏖️ **Casual riders take significantly longer trips** — casual rides averaged
131 minutes compared to 84 minutes for members, meaning casuals ride for
nearly 56% longer on average, strongly suggesting leisure and recreational
use rather than functional commuting.

📍 **Casual riders cluster near tourist and lakefront stations** — the highest
volume casual start stations were concentrated near Chicago's Millennium Park,
Navy Pier, and the lakefront trail, while member hotspots centered around
office districts and transit hubs.

❄️ **Casual ridership is highly seasonal** — casual rides dropped from
432,000 in peak summer months to just 117,000 in winter, a decline of over
70%. Member ridership remained comparatively stable year-round, confirming
that casual use is weather and leisure driven.

📊 **Members dominate overall ride volume** — members accounted for 3,552,430
rides across the year versus 1,994,749 for casual riders, making up 64% of
all trips taken on the network.

---

## Recommendations

1. **Launch a seasonal or weekend membership pass** targeting casual riders
   who ride heavily in summer and on weekends. With casual rides peaking at
   432,000 in summer, there is a large addressable audience to convert before
   ridership drops off in winter.

2. **Place targeted marketing at high-traffic casual stations** near tourist
   and lakefront locations, using messaging that highlights membership savings
   based on observed casual usage frequency.

3. **Trigger in-app conversion prompts** after a casual rider's 3rd or 4th
   ride, showing a personalized estimate of how much they would save annually
   with a membership at their current usage rate.

---

## Tools and Process

| Phase | Tool | Task |
|---|---|---|
| Prepare | Excel | Initial file inspection and safe CSV import |
| Process | Python + Jupyter Notebook | Cleaning and combining 5.5 million rows of data |
| Analyze | BigQuery SQL | Aggregations, trends, and summary table creation |
| Share | Tableau | Interactive dashboards for executive presentation |

---

## Data Source
12 months of Cyclistic trip data provided by Motivate International Inc. under a
public license. The dataset contained 5,547,179 rows of individual ride records
across Chicago's bike-share network, reduced to 5,547,179 after cleaning.

> **Note:** Data-privacy restrictions prohibit the use of personally identifiable
> information. Individual riders cannot be tracked across sessions or linked to
> demographic data.

---
## Dashboards
📊 Visualizations created in Tableau — see charts below

1. Ride Behavior Overview
<img width="1535" height="883" alt="ride_behavior_overview" src="https://github.com/user-attachments/assets/60a6ba0f-cd53-4c01-a1d9-a64f06d936c5" />
 
2. Time Patterns
<img width="1533" height="882" alt="time_patterns" src="https://github.com/user-attachments/assets/f0786b28-f2cb-49f6-867e-b8b4ae76717f" />

3. Ride Length Patterns
<img width="572" height="849" alt="ride_length_patterns" src="https://github.com/user-attachments/assets/30c490d3-0e6b-4d5d-becc-8c067f6cf0a1" />

---

