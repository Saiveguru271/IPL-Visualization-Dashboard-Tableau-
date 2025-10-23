# IPL-Visualization-Dashboard-Tableau-
Interactive Tableau dashboard analyzing IPL data (2008–2017) using match and ball-by-ball datasets. Visualizes toss impact on match results, Orange/Purple Cap trends, and season-wise team performance. Includes integrated datasets and a presentation summarizing key insights and patterns.
IPL Visualization Dashboard (2008–2017)

This project showcases an interactive Tableau dashboard built using IPL match and ball-by-ball data from 2008–2017. The goal is to uncover trends, patterns, and performance insights related to teams, players, and match outcomes. The dashboard visually highlights toss impact, Orange/Purple Cap leaders, and season-wise team performance, supported by a summary report for data storytelling.

📌 Key Insights & Objectives

The dashboard helps answer important analytical questions, such as:

Does winning the toss influence winning the match?

Who were the consistent top performers (Orange & Purple Cap) across seasons?

Which teams dominated each season, and how did their performance evolve?

How do toss decisions (bat/field) affect match outcomes?

📊 Dashboard Visuals

The Tableau dashboard includes:

Visualization	Purpose
Toss vs Match Outcome	Compare toss winners vs match winners
Orange Cap Trends	Top run scorers across all seasons
Purple Cap Trends	Top wicket-takers by season
Season-wise Team Performance	Team consistency and dominance patterns
📂 Project Structure
/data
   ├── matches.csv
   ├── deliveries.csv
/dashboard
   ├── IPL_Tableau_Dashboard.twb
/reports
   ├── IPL_Insights_Presentation.pptx
README.md

🛠️ Tools & Technologies

Tableau – Dashboard & visual analytics

Excel/CSV – Basic cleaning & preparation

PowerPoint – Final insights report

🧹 Data Preparation

Combined matches.csv and deliveries.csv using match_id

Removed duplicates and irrelevant fields

Extracted features for team and player-level insights

Aggregated runs, wickets, wins, and toss stats

🚀 Outcome

Interactive IPL dashboard for exploratory analysis

Clear visual patterns for player and team performance

Improved data storytelling and visualization skills

🔮 Future Enhancements

Add seasons beyond 2017

Deploy as a web dashboard using Plotly/Power BI/Dash

Add winner prediction using ML models
