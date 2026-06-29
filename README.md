# Player Performance Analytics of T20 World Cup 2022

<img width="1100" height="500" alt="T20 World Cup 2022" src="https://github.com/user-attachments/assets/dbcd537e-8c05-46d1-b528-775c05772cc4" />

## Table of Contents
- [Overview](#overview)
- [Why This Project?](#why-this-project)
- [Tools & Technologies](#tools--technologies)
- [Project Workflow](#project-workflow)
- [Repository Structure](#repository-structure)
- [Getting Started](#getting-started)
- [Key Insights](#key-insights)
- [What This Project Solves](#what-this-project-solves)
- [Key Outcomes](#key-outcomes)
- [Future Improvements](#future-improvements)
- [Conclusion](#conclusion)

## Overview

This project explores player performance and team strategies from the ICC Men's T20 World Cup 2022 using data analytics.

Instead of just looking at basic statistics, the focus was to understand what actually drives success in T20 cricket — whether it's strike rate, consistency, bowling efficiency, or team balance.

The project combines Excel, Python (Jupyter), and Power BI to build a complete analysis workflow from raw data to interactive insights.

<img width="1100" height="500" alt="Analysis Overview" src="https://github.com/user-attachments/assets/acdbea2d-a972-4b11-9111-bdaf090c3000" />

## Why This Project?

Cricket analysis is often limited to surface-level stats like total runs or wickets. But in a fast-paced format like T20, those metrics don't always explain why teams win.

I built this project to:

- Go beyond traditional stats
- Identify high-impact players
- Understand match-winning patterns
- Apply data analytics to a real-world sports scenario

## Tools & Technologies

- **Excel** – Initial data cleaning and validation
- **Python (Jupyter Notebook)** – Data processing, transformation, and analysis
- **Power BI** – Interactive dashboard and visual storytelling

## Project Workflow

### 1. Data Preparation (Excel + Python)
- Imported and cleaned raw match data
- Handled missing values and inconsistencies
- Standardised player names, teams, and metrics

### 2. Data Analysis (Python)
- Analysed batting performance (runs, strike rate, consistency)
- Evaluated bowling metrics (economy, wickets, pressure overs)
- Compared team-level performance across matches

### 3. Data Visualisation (Power BI)
- Built an interactive dashboard to explore insights
- Created KPIs for player performance and team comparison
- Designed visuals for easy interpretation of trends

<img width="1100" height="500" alt="Project Workflow" src="https://github.com/user-attachments/assets/0ec8a82c-8cf6-42a6-b2eb-c16524225c46" />

## Repository Structure

```
t20-world-cup-2022-player-performance-analysis/
├── data/                          # Raw and processed datasets
│   ├── raw/                       # Original match and player data
│   └── processed/                 # Cleaned data ready for analysis
├── notebooks/                     # Jupyter notebooks for analysis
│   ├── 01_data_cleaning.ipynb
│   ├── 02_batting_analysis.ipynb
│   └── 03_bowling_analysis.ipynb
├── dashboards/                    # Power BI files and exports
│   └── t20_analysis.pbix
├── outputs/                       # Generated visualizations and reports
└── README.md                      # Project documentation
```

## Getting Started

### Prerequisites
- Python 3.8+
- Jupyter Notebook
- Power BI Desktop (for viewing dashboards)
- Libraries: pandas, numpy, matplotlib, seaborn

### Installation & Usage

1. **Clone the repository**
   ```bash
   git clone https://github.com/Pradniu/t20-world-cup-2022-player-performance-analysis.git
   cd t20-world-cup-2022-player-performance-analysis
   ```

2. **Install required Python libraries**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the analysis**
   - Open `notebooks/` folder and run Jupyter notebooks in sequence (01 → 02 → 03)
   - Follow the comments in each notebook for detailed explanations

4. **View the dashboard**
   - Open `dashboards/t20_analysis.pbix` with Power BI Desktop to explore interactive insights

### Dataset Information
- **Source:** ICC Men's T20 World Cup 2022 official data
- **Coverage:** All matches, players, and performance metrics from the tournament
- **Format:** CSV files with standardised structure
- **Key columns:** Player name, team, runs, wickets, strike rate, economy rate, match details

## Key Insights

- **A small group of players had a major impact on match outcomes** – Not all players contribute equally
- **Strike rate played a more important role than average in T20 success** – Fast scoring matters more than consistency
- **Teams with strong middle-order performance were more consistent** – Reliable batting depth wins tournaments
- **Certain bowlers performed significantly better during high-pressure overs** – Clutch performance is key
- **Winning teams showed balanced contributions rather than relying on a single player** – Team balance beats individual brilliance

<img width="1100" height="500" alt="Key Insights Dashboard" src="https://github.com/user-attachments/assets/4201bbef-b23a-46d5-9176-9e49441ffe9e" />

## What This Project Solves

This project helps:

- Identify high-impact players instead of just top scorers
- Understand which metrics actually influence winning
- Provide a data-driven view of team strategies
- Translate raw match data into meaningful insights
- Support strategic decision-making for team management

## Key Outcomes

✅ Built an end-to-end analytics workflow from data to insights

✅ Created an interactive dashboard for exploration and discovery

✅ Transformed raw cricket data into actionable recommendations

✅ Demonstrated the power of data-driven sports analytics

## Future Improvements

- [ ] Add player clustering analysis (e.g., aggressive vs anchor batsmen)
- [ ] Include predictive models for match outcome forecasting
- [ ] Expand dataset to multiple tournaments for deeper insights
- [ ] Develop automated data pipeline for live tournament updates
- [ ] Add player comparison and benchmarking features

## Conclusion

This project demonstrates how data can be used to better understand performance and strategy in sports. By combining multiple analytics tools and techniques, we transformed raw cricket data into meaningful, actionable insights that reveal the true drivers of success in T20 cricket.

---

**Author:** [Pradniu](https://github.com/Pradniu)

**Last Updated:** June 2026

**License:** MIT
