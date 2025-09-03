# Workforce Attendance Analytics – Power BI Project

---

## 🏢 Project Overview

This project analyzes synthetic employee attendance data for 2022–2023.  
Using Power BI, organizational attendance, leave, and work-from-home patterns are visualized and explored to drive data-driven HR decisions.

**All personal and sensitive data is synthetic/masked.**

---

## 📊 Dashboard Preview

![Workforce Attendance Insights](./attendance%20pbi.png)

---

## 🗃️ Dataset

- **Attendance-Sheet-2022-2023_Masked.xlsx**
  - Multiple sheets: each represents one month (e.g., "Apr 2022", "May 2022", "Jun 2022")
  - Rows: Unique employees (`Employee Code`, `Name`)
  - Columns: Daily status, `Total Present Days`, leave type counts

- **Attendance values:**  
  - `P`: Present
  - `WO`: Weekly Off
  - `WFH`: Work From Home
  - `PL`: Paid Leave
  - `SL`: Sick Leave
  - `ML`: Menstrual Leave
  - ...and more (full key in file)

---

## 📈 Dashboard Features & Analytics

- **Main KPIs:**  
  - **Attendance %** (e.g., `94.0%`): Share of total possible workdays present
  - **WFH %** (`9.1%`): Share of work-from-home days
  - **SL %** (`0.4%`): Share of sick leave days

- **Trends (over time and day-of-week):**
  - **Attendance rate trendline:** Reveals seasonal dips and peaks (e.g., April 8th drop, following recovery)
  - **SL trendline:** Highlights sick leave spikes—potentially due to events or illnesses
  - **WFH trendline:** Shows how WFH is utilized, displaying peaks/friday effects

- **Attendance/Leave by Day-of-Week:**
  - Mondays: Highest attendance (96.5%)
  - Fridays/Thursdays: Lower attendance, higher WFH rates (WFH Fri: 12.2%)
  - Thursdays: Most frequent sick leave day (1.3% of cases)

- **Employee Leaderboard/Table:**
  - Attendance percentages for each employee
  - Who works from home most
  - Employees with frequent absenteeism/leave

- **Interactive filters:**
  - By date range/month
  - By employee or leave type

---

## 🧐 Key Insights

- **Stable Attendance:**  
  Overall attendance held steady at ~94% across the period, with minor weekday/holiday fluctuations.

- **Sick Leave & WFH Patterns:**  
  Sick leave is most often taken on Thursdays; WFH is most popular on Fridays (possibly extending weekends).

- **Present vs. Remote:**  
  Work-from-home accounts for 9.1% of all workdays—signifying a partially hybrid workforce.

- **Absentee Spotlight:**  
  Employees Atq-485 and Atq-404 have notably lower attendance (52–71%) and unique leave patterns.

---

## 🔗 How to Use

1. Download/clone the repo.
2. Open `Attendance-Sheet-2022-2023_Masked.xlsx` to inspect source data and keys.
3. Open the Power BI file (`your_dashboard.pbix`) to explore and filter the analysis interactively.

---

## 📂 Files Included

.
├── Attendance-Sheet-2022-2023_Masked.xlsx # Source data
├── image.jpg # Power BI dashboard screenshot
├── your_dashboard.pbix # Power BI file (if available)
├── README.md

text

---

## 🏆 Learning Outcomes

- Translating wide, multi-sheet spreadsheet data into BI models
- Interpreting attendance KPIs for actionable HR insights
- Leveraging Power BI’s filters, trendlines, and slicers for dynamic workforce analytics
- Simulating real-world HR dashboarding with synthetic data

---

## 📧 Contact

Questions, feedback, or want to see more BI demos?  
Find me on [LinkedIn](https://linkedin.com/in/srujanshetty).

---

*All data is synthetic and for demonstrative purposes only.*
