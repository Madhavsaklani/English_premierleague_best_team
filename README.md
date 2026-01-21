# ⚽ EPL 2023/24 Team Performance Analysis Dashboard

## 📌 Project Overview

This project focuses on analysing **English Premier League (EPL) 2023/24**   season data to identify:

* Strong attacking teams
* Defensive solidity across teams
* Overall dominant ("overpower") teams using data-driven insights

The complete workflow covers **data cleaning, analysis, insight generation, and interactive dashboard creation in Power BI**.

---

## 🎯 Objectives

* Convert raw match-level data into team-level insights
* Analyse attack, defence, and overall team dominance
* Build a clean, recruiter-ready Power BI dashboard
* Practice real-world sports analytics workflow

---

## 📂 Project Structure

```
best EPL Team/
│
├── data/
│   ├── raw/            # Raw match-level CSV data
│   └── processed/      # Cleaned & aggregated datasets
│
├── notebook/
│   └── analysis.ipynb  # Data cleaning & analysis notebook
│
├── dashboard/          # Power BI (.pbix) file
│
└── README.md           # Project documentation
```

---

## 🧹 Data Processing

* Raw data contains **match-by-match information** (Home/Away teams, goals, shots, results, etc.)
* Data is aggregated to **team-level metrics** such as:

  * Goals For
  * Goals Against
  * Points
  * Clean Sheets
  * Shot Accuracy
  * Goal Conversion

Processed tables are saved separately to ensure smooth Power BI integration.

---

## 📊 Key Insights & Visuals

### 🔥 Attacking Insight

**"Attacking Efficiency by Team – EPL 2023/24"**

* Goals scored by each team
* Highlights teams with high attacking output
* Visual: **Bar Chart / Table**

---

### 🛡️ Defensive Insight

**"Defensive Strength – Goals Conceded by Team (EPL 2023/24)"**

* Total goals conceded by each team
* Lower goals conceded = stronger defence
* Visual: **Clustered Bar Chart (sorted ascending)**

---

### ⚡ Overpower Insight

**"Overall Team Dominance: Attack vs Defence (EPL 2023/24)"**

* Compares attacking output vs defensive solidity
* Helps identify well-balanced dominant teams
* Visuals:

  * **Scatter Plot (Goals For vs Goals Against)**
  * **Matrix with Conditional Formatting**

---

## 🧠 Analytical Techniques Used

* Team-level aggregation
* Sorting & ranking
* Conditional formatting for pattern recognition
* Multi-metric comparison (Attack + Defence)

---

## 🛠️ Tools & Technologies

* **Python** (Pandas, NumPy)
* **Jupyter Notebook** (EDA & processing)
* **Power BI** (Dashboard & visual storytelling)
* **CSV datasets**

---

## 🚀 Outcomes

* Identified top attacking teams
* Evaluated defensive reliability across the league
* Highlighted overall dominant teams using data
* Created a clean, professional sports analytics dashboard

---

## 📈 Future Improvements

* Add player-level analysis
* Include expected goals (xG) metrics
* Season-to-season comparison
* Automated data scraping pipeline

---

## 👤 Author

**Madhav Saklani**
B.Sc. Computer Science | Sports Analytics Enthusiast


