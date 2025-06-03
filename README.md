# 👨‍💼 HR Analytics Dashboard – Power BI

This project is an **HR Dashboard** built in Power BI to track employee attendance, work-from-home (WFH), and sick leave (SL) data for the months of **April, May, and June 2022**.

---

## 📚 What This Dashboard Does

The dashboard helps you:
- Understand how many employees are present, working from home, or on sick leave.
- Track attendance trends over time.
- See which days of the week have the most or least attendance.
- View attendance for each employee, day by day.

It's perfect for HR teams to get a quick view of employee presence and plan better.

---

## 🛠️ How We Built It

### 1. 🧹 Data Cleaning & Standardization
- We had 3 different Excel files (one for each month).
- In each file, the **dates were set as column headers**, and the structure was different.
- So, we made a **dynamic Power Query function** in Power BI to clean and transform each file into the same format.
- This function works for future files too — just plug them in, and they’ll be ready to use.

### 2. 📊 Merging the Data
- After cleaning, we merged all three months into one master table called `Final Data`.

### 3. 🧮 DAX Calculations
We created custom DAX measures to calculate:
- `Attendance %`
- `Present Days`
- `WFH %` (Work From Home Percentage)
- `SL %` (Sick Leave Percentage)

These measures help generate totals, percentages, and time-based comparisons.

### 4. 📈 Visualizations
We built an interactive dashboard with:
- **KPIs** for Attendance %, WFH %, and SL %
- **Line charts** showing changes in attendance, WFH, and SL over time
- **Tables** showing employee-wise and day-wise breakdowns
- A detailed **calendar view** showing who was present or working from home on which day

---

## 🔍 Key Insights You Can Get

From this dashboard, you can find:
- The **overall attendance rate** is around **94%** for the 3-month period.
- **Work From Home** was used by employees **about 9.1%** of the time.
- **Sick leave** was very low, only **0.4%** overall.
- **Mondays** had the highest attendance, and **Thursdays** had slightly more sick leaves.
- **Fridays** had the most work-from-home activity.

This kind of analysis helps in spotting trends, managing workloads, and improving team productivity.

---


