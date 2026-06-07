# 🏏 IPL Performance Analytics (2008–2026)

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![SQL](https://img.shields.io/badge/SQL-SQLite-orange?logo=sqlite)
![PowerBI](https://img.shields.io/badge/PowerBI-Dashboard-yellow?logo=powerbi)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

## 📌 Project Overview

An end-to-end data analysis project on 19 seasons of IPL cricket 
(2008–2026) covering 1,212 matches and 288,226 deliveries. 
The project simulates a real-world data analyst role — cleaning 
raw data, performing exploratory analysis, querying with SQL, 
and building an interactive Power BI dashboard.

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| Python (Pandas, NumPy) | Data cleaning & manipulation |
| Matplotlib & Seaborn | Data visualization |
| SQL (SQLite) | Querying & aggregations |
| Power BI | Interactive dashboard |
| Google Colab | Development environment |

---

## 📂 Dataset

- **Source:** Kaggle — IPL Complete Dataset 2008–2026
- **Files:** 5 CSV files (matches, deliveries, teams, players, aliases)
- **Size:** 1,212 matches | 288,226 ball-by-ball deliveries | 19 seasons

---

## ❓ Business Questions Answered

1. Which teams have dominated IPL across all seasons?
2. Does winning the toss actually help win the match?
3. Who are the all-time top run scorers and wicket takers?
4. What is each team's preferred toss decision?
5. How has match frequency changed across seasons?
6. Who are the most aggressive batters by strike rate?
7. Who are the most economical bowlers by economy rate?

---

## 🔄 Project Workflow

Raw Data → Data Cleaning → EDA → SQL Analysis → Power BI Dashboard

### Step 1 — Data Cleaning
- Decoded team IDs and player IDs using lookup tables
- Standardized team names across seasons (e.g. Delhi Daredevils → Delhi Capitals)
- Fixed data types, handled nulls, removed duplicates
- Exported clean datasets for analysis

### Step 2 — Exploratory Data Analysis
- 8 charts covering team performance, toss impact, player stats, season trends
- Strike rate analysis (min. 500 balls faced)
- Economy rate analysis (min. 300 balls bowled)

### Step 3 — SQL Analysis
- Created SQLite database from cleaned dataframes
- Wrote 6 queries covering all business questions
- Used aggregations, CASE statements, and percentage calculations

### Step 4 — Power BI Dashboard
- 2-page interactive dashboard
- Page 1: Team & Match Analysis
- Page 2: Player Analysis
- Slicers for Season and Team filtering

---

## 💡 Key Insights

- **Mumbai Indians** lead all-time with **155 wins** across 19 seasons
- Toss winners win only **51.7%** of matches — toss advantage is minimal
- **66%** of teams choose to field after winning the toss
- **Virat Kohli** is the all-time leading run scorer with **9,050 runs**
- **YS Chahal** leads wicket takers with **228 dismissals**
- **PD Salt** has the highest strike rate (**168.63**) among established batters
- **A Kumble** holds the best economy rate (**6.58**) in IPL history
- IPL has grown from **58 matches** in 2008 to **74 matches** per season

---

## 📁 Repository Structure

```
ipl-performance-analytics/
│
├── IPL_Analysis.ipynb
├── IPL_Performance_Analytics.pbix
├── matches_clean.csv
├── deliveries_clean.csv
├── team_wins.csv
├── season_toss.csv
├── top_batters_final.csv
└── top_bowlers_final.csv
```

---

## 📊 Dashboard Preview

**Page 1 — Team & Match Analysis**
- KPI cards: Total Matches, Total Seasons
- Bar chart: IPL wins by team
- Donut chart: Toss decision breakdown
- Line chart: Matches per season trend
- Slicers: Filter by Team and Season

**Page 2 — Player Analysis**
- Bar chart: Top 10 run scorers
- Bar chart: Top 10 wicket takers
- KPI cards: Kohli 9,050 runs | Chahal 228 wickets

---

## 👩‍💻 Author

**M Nisthula**
B.Tech Computer Science | Ahalia School of Engineering & Technology

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin)](https://linkedin.com/in/nisthula-madhu)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-black?logo=github)](https://github.com/Nisthula268)
