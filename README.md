# 🏏 T20 World Cup Data Analytics — Best XI Player Selection

An end-to-end data analytics project that uses web scraping, Python, Pandas, and Power BI to analyze T20 World Cup (2022) cricket data and identify the best possible playing XI from all participating teams.

---

## 📌 Problem Statement

> **"Assemble the best 11 players from the T20 World Cup 2022 that could beat even an alien team."**

The goal is to use real match data to shortlist players across batting, bowling, and all-rounder roles — based on performance metrics — and build an interactive Power BI dashboard to present the findings.

---

## 🗂️ Project Workflow

```
Web Scraping (Bright Data + ESPN Cricinfo)
        ↓
Data Cleaning & Transformation (Python + Pandas)
        ↓
Data Transformation (Power Query)
        ↓
Data Modeling & DAX Measures (Power BI)
        ↓
Dashboard & Insights (Power BI)
        ↓
Final XI Selection
```

---

## 🔧 Tech Stack

| Tool | Purpose |
|---|---|
| **Bright Data** | Web scraping from ESPN Cricinfo |
| **Python** | Data cleaning and transformation |
| **Pandas** | Data wrangling and analysis |
| **Power Query** | Additional data transformation |
| **DAX** | Calculated measures and KPIs in Power BI |
| **Power BI** | Dashboard building and visualization |

---

## 📊 Data Collected

Data was scraped from [ESPN Cricinfo](https://www.espncricinfo.com/) covering T20 World Cup 2022 matches:

- Match results and summaries
- Batting scorecards (runs, strike rate, boundaries, etc.)
- Bowling scorecards (wickets, economy rate, dot balls, etc.)
- Player profiles

---

## 🧹 Data Processing Steps

1. **Web Scraping** — Collected raw JSON data via Bright Data's scraper on ESPN Cricinfo
2. **Python / Pandas** — Cleaned nulls, standardized player names, computed derived metrics (batting avg, strike rate, bowling economy, etc.)
3. **Power Query** — Merged and shaped tables for the data model
4. **DAX** — Built calculated columns and measures for dynamic KPIs

---

## 📈 Dashboard Highlights

The Power BI dashboard covers 5 player categories:

- 🏏 **Power Hitters / Openers** — High strike rate, boundary % focus
- 🧱 **Anchors / Middle Order** — Batting average and consistency
- 🔥 **Finishers** — Innings at death, SR in last 5 overs
- 🎳 **All-rounders** — Balanced bat + ball contribution
- 💨 **Specialist Bowlers** — Economy rate, dot ball %, wickets

Each category has defined selection criteria and threshold filters built into the dashboard.

---

## 🏆 Final XI Selection

The final 11 players were selected based on a combination of statistical thresholds and visual analysis from the dashboard — balancing batting firepower, bowling variety, and team composition.

---

## 📁 Project Structure

```
├── data/
│   ├── raw/                    # Scraped JSON files from Bright Data
│   └── processed/              # Cleaned CSVs after Python transformation
├── notebooks/
│   └── data_cleaning.ipynb     # Pandas transformation notebook
├── cricket_analytics.pbix      # Power BI dashboard file
└── README.md
```

---

## 🚀 How to Run

### 1. Clone the repository
```bash
git clone https://github.com/souravvrc/t20-cricket-analytics.git
cd t20-cricket-analytics
```

### 2. Install Python dependencies
```bash
pip install pandas numpy
```

### 3. Run the cleaning notebook
Open `notebooks/data_cleaning.ipynb` and run all cells to generate the processed CSVs.

### 4. Open Power BI
Load `t20 analytics dashboard.pbix` in Power BI Desktop and refresh the data source to point to your local processed CSV files.


---

## 💡 Key Skills Demonstrated

- Web scraping with Bright Data
- Data cleaning and wrangling with Pandas
- Power Query transformations
- DAX measures and calculated columns
- Interactive dashboard design in Power BI
- Sports analytics and insight storytelling

---

## 📺 Project Tutorial

This project is based on the [Codebasics End-to-End Cricket Analytics](https://www.youtube.com/watch?v=4QkYy1wANXA) tutorial.

---

## 🙋 Author

**Sourav**  
Electronics & Computer Engineering | KJ Somaiya College of Engineering  
[GitHub](https://github.com/souravvrc) • [Portfolio](https://souravportfolio-nine.vercel.app)
