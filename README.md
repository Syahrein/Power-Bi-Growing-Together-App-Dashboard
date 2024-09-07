# Power BI Dashboard - Growing Together App

## Overview
This repository contains a Power BI dashboard designed to track and visualize key metrics of Company B’s app. The dashboard provides insights into user engagement, program participation, and baby health statistics. It consists of two main pages:
- **Overview**
- **Babies Health**

The dashboard is divided into two pages: the first provides an overall view of the program’s key metrics, while the second focuses on the health statistics of babies enrolled in the program. Together, they allow stakeholders to effectively track participation, engagement, and health-related outcomes.

## Dashboard Pages

### 1. Overview
The "Overview" page provides a summary of key metrics from the app, including active users, average age of children, and reasons for drop-off. It also includes satisfaction with the app and cumulative app users over time.

![Overview (clean)](https://github.com/user-attachments/assets/338f07f1-0002-4f97-b3ff-f75509520aa7)

### Dashboard Features:
- **Active Users**: Displays the number of users currently active in the program.
- **Average Age**: Shows the average age (in months) of the users in the program.
- **Number of Children**: Tracks the total number of children enrolled in the program.
  
#### Key Insights:
- **Gender Distribution**: A donut chart showing the gender breakdown of the users (male and female).
- **Years in Program**: A bar chart showing how long users (children) have been enrolled in the program, revealing retention trends.
- **Satisfaction with the App**: A chart visualizing user feedback and satisfaction levels, helping to gauge app performance.
- **Reasons for Drop-off**: Provides insights into the most common reasons why users leave the program, such as "Caretaker stop using" or "No longer a baby." By drilling down into this chart at "Caretaker stop using" bar, we can pinpoint specific stages where user engagement declines. This will enable us to focus on areas like Stage 4, where a higher drop-off rate might indicate the need for UI/UX enhancements or other improvements.

![Overview2 (clean)](https://github.com/user-attachments/assets/005e4bfd-d8a9-4330-b39c-f1cbec28cfd7)

#### Cumulative App Users Over Time:
- **Growth Tracking**: A cumulative line chart tracking the total number of app users over time, helping to identify the program's growth.

### 2. Babies Health
The "Babies Health" page provides insights into health-related statistics of children enrolled in the app, such as average weight, head circumference, and sleep quality.

![Babies Health (clean)](https://github.com/user-attachments/assets/eed02fbc-9f6d-44ad-b73f-2a042cc907d1)

#### Key Metrics:
- **Average Weight (kg) by Stage:** Growth trends of children across different stages.
- **Average Length (cm) by Stage:** Growth patterns in length based on the program stages.
- **Sleep Quality:** Breakdown of children’s sleep quality, categorized into different levels.

## Technologies Used
- **Data Source:** Sample and Batch processing data, extracted from the MySQL database server.
- **SQL:** Utilized to efficiently query and extract relevant data from the MySQL database for use in Power BI.
- **Power BI:** For creating interactive visualizations and data reports.
- **DAX (Data Analysis Expressions):** Utilized in Power BI to create custom measures and enhance the visualizations.
- **Visualization Types:** Bar charts, line graphs, tables, and summary cards.

## Contact Information
Feel free to reach out if you have any questions or would like to discuss the insights from this dashboard:
- **Email:** syahrein01@gmail.com
- **LinkedIn:** [LinkedIn Profile](https://www.linkedin.com/in/syahrein/)
