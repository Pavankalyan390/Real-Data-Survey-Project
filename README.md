# Real Data Survey Project

# 📊 Data Professional Survey Breakdown Dashboard
- This interactive Power BI dashboard provides a comprehensive breakdown of survey responses from 630 data professionals across various job titles and countries.
- The dashboard was created to explore trends in salaries, work-life balance, programming language preferences, and the challenges of breaking into the data field.
  
# 🚀Project Overview
- The goal of this project is to provide clear insights into the current state of the data profession by visualizing key metrics from survey data.
- The dashboard was designed for quick interpretation and storytelling through intuitive visuals.



## 👨‍💻 Why This Project?
- This project demonstrates the ability to clean and analyze survey data, design user-friendly dashboards, and provide actionable insights for aspiring and current data professionals.



# Things I did in Preprocessing
- Eliminated 3+ unwanted columns using Power Query.

- Created a separate column for Country. Grouped countries with fewer responses under “Others” to avoid clutter.

- Used DAX to calculate the average salary based on regional base pay.

      ([#"Q3 - Current Yearly Salary (in USD)"] + [#"Q3 - Current Yearly Salary (in USD)"]) / 2
- Now That's all I needed to design my dashboard.
  

# 🌟 Key Insights
  - 👥 Survey Size: 630 respondents with an average age of 29.87 years.

- 💼 Job Titles & Salaries:

- Data Scientists have the highest average salary.

- Students/Entry-level professionals reported the lowest salaries.

- 🌎 Country Representation: Major responses from the United States, India, Canada, and the United Kingdom.

### 💻 Programming Language Preference:

- Python is the dominant favorite among data professionals.

- R comes second, with other languages like JavaScript and C++ trailing behind.

### ⚖️ Work-Life Balance & Salary Satisfaction:

- Average work-life balance rating: 5.86/10

- Average salary satisfaction rating: 5.61/10

### 🛣️ Breaking into Data:

- 42% of respondents find it “neither easy nor difficult” to enter the field.

- 25% found it difficult, while only a small fraction found it very easy.

# 📌 Features
Interactive visualizations with slicers and filters.

- Treemap to show country representation, I tempt to use Map visual but I felt kinda like I had to zoom in too much that's why I used a Treemap for quick view of country.

- Bar charts for salary comparison and programming language preferences.

- Donut chart for visualizing difficulty levels of entering the data field.

- KPI indicators for quick metrics overview

# 🛠️ Tools Used
- Power BI for data visualization.

- DAX for calculated measures and metrics.

- Data preprocessing with Power Query.

# 🎯 What I Learned:
- Designing user-centric dashboards for storytelling.

- Cleaning and transforming real-world survey data efficiently.

- Using DAX for advanced calculations and insights.

- Choosing appropriate visualizations for better user experience.

# Dashboard Preview
<img width="1182" height="786" alt="Screenshot (58)" src="https://github.com/user-attachments/assets/cae90a6b-db2d-457d-885b-edb51227bf28" />
