# 🚕 Uber Fares Dataset Analysis with Power BI

## 📊 Project Overview

This project analyzes Uber ride fare patterns using data sourced from [Kaggle](https://www.kaggle.com/datasets/yasserh/uber-fares-dataset). The goal is to extract meaningful insights into ride behavior, fare distribution, time-based patterns, and operational metrics using Python (for cleaning & feature engineering) and Power BI (for interactive dashboarding).

---

## 📁 Project Structure


---

## 🛠️ Tools Used

- Python (Pandas, NumPy, Seaborn, Matplotlib)
- Google Colab
- Power BI Desktop
- GitHub

---

## 📌 Process Overview

### 🔹 1. Data Preparation (Python)
- Loaded raw Uber dataset from Kaggle.
- Cleaned missing values and invalid entries.
- Calculated trip distance using Haversine formula.
- Extracted time features (hour, day, month, weekday).
- Flagged peak vs. off-peak hours.
- Saved final dataset to `uber_enhanced.csv`.

### 🔹 2. Exploratory Data Analysis (Python)
- Analyzed fare statistics (mean, median, std).
- Detected outliers using box plots.
- Visualized fare distributions and correlation with distance.

### 🔹 3. Dashboard Development (Power BI)
- Imported enhanced dataset.
- Created key visuals:
  - Bar chart: Rides by hour
  - Column chart: Rides by day of week
  - Line chart: Rides by month
  - Scatter plot: Fare vs distance
  - Donut chart: Peak vs off-peak rides
  - KPI Cards: Avg fare, total rides, avg distance
- Integrated interactive slicers: hour, month, passenger count, peak flag

---

## 📸 Screenshots

Screenshots are located in the `/screenshots` folder and include:
- Data loading process
- Python cleaning & feature engineering
- Power BI visuals
- Final dashboard layout

---

## 📈 Key Insights

- Peak ride hours are between 7–9 AM and 4–7 PM.
- Most rides occur during weekdays.
- Fare strongly correlates with distance.
- Majority of fares are under $25.
- Peak hours make up a large portion of rides.

---

## ✅ Deliverables

- `uber_enhanced.csv` (cleaned dataset)
- `Uber_Dashboard.pbix` (Power BI dashboard file)
- All required screenshots
- This README documentation

---

## 🧠 Author

- **ASDODJI Le Sage**
- ALX Data Science Program – AUCA
- Instructor: Eric Maniraguha (📧 eric.maniraguha@auca.ac.rw)

---

## 📌 Notes

- This project was completed as part of the "Introduction to Big Data Analytics" course.
- All code and visuals are original and developed independently.
- No personally identifiable information is included in the dataset.

---

## 📤 Submission

✅ Submitted via GitHub (public repo)  
✅ Emailed repo link before Sabbath  
✅ All requirements met (clean data, visuals, report)

---

Thank you for reviewing this project! 🙏

#scrennshot

<img width="1202" height="578" alt="Screenshot 2025-07-25 095456" src="https://github.com/user-attachments/assets/0c2d3cae-8c11-4fce-ab0e-d8ad5936cff3" />

