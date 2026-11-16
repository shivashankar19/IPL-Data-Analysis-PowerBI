# 🏏 IPL Analytics & Performance Intelligence using Power BI

## 📌 Project Overview

IPL Analytics & Performance Intelligence is a data analytics and visualization project developed using Microsoft Power BI. The project focuses on analysing Indian Premier League (IPL) data to understand match outcomes, team performance, player statistics, and season-wise trends.

Using multiple Excel datasets, the project transforms raw cricket data into interactive dashboards that help users explore IPL statistics and discover meaningful insights through data visualization.

## 🎯 Project Objectives

- Analyse IPL match data across different seasons.
- Identify top-performing teams and players.
- Analyse batting and bowling performance.
- Understand match results and winning patterns.
- Explore toss decisions and their relationship with match outcomes.
- Compare team performance using interactive visualizations.
- Present cricket statistics through an interactive Power BI dashboard.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Microsoft Power BI | Dashboard development and visualization |
| Power Query | Data importing and transformation |
| DAX | Calculated measures and KPIs |
| Microsoft Excel | Dataset storage and preparation |
| GitHub | Project source code and version management |

## 📂 Project Structure

```text
IPL-Data-Analysis-PowerBI/
│
├── README.md
│
├── Raw_Data/
│   ├── ball_by_ball_data.xlsx
│   ├── ipl_matches_data.xlsx
│   ├── players-data-updated.xlsx
│   ├── team_aliases.xlsx
│   ├── Team_Logo.xlsx
│   └── teams_data.xlsx
│
├── PowerBI/
│   └── IPL_Analytics_Dashboard.pbix
│
├── Screenshots/
│   ├── Home Page.png
│   ├── IPL Overview.png
│   ├── Match Analysis.png
│   ├── Player Analysis.png
│   └── Team Performance.png
│
└── Presentation/
    └── IPL_Analytics_Project_Presentation.pptx
```

## 📊 Dataset Description

The project uses six Excel datasets:

| Dataset | Description |
|---|---|
| ball_by_ball_data.xlsx | Delivery-level information including batter, bowler, runs, extras, wickets, and innings |
| ipl_matches_data.xlsx | Match details including season, date, venue, teams, toss decisions, and match results |
| players-data-updated.xlsx | Player details including player name, batting style, and bowling style |
| teams_data.xlsx | Team identifiers and team names |
| team_aliases.xlsx | Alternative team names and aliases |
| Team_Logo.xlsx | Team logos, captain images, and team colour information |

## 🔄 Data Preparation and Transformation

The datasets are imported into Power BI and prepared for analysis using Power Query.

The project works with match-level and ball-by-ball-level information to support different types of analysis.

Important data fields include:

- Match ID
- Season ID
- Batter and Bowler
- Batting and Bowling Teams
- Total Runs
- Batter Runs
- Extras
- Wickets
- Match Winner
- Toss Decision
- Venue
- Player of the Match

## 📈 Dashboard Pages and Features

The Power BI report contains five pages:

### 1. Home Page
- Project introduction and navigation.
- Provides access to the analytical dashboard pages.

### 2. IPL Overview
- Total Matches
- Total Runs
- Total Wickets
- Total Sixes
- Average Runs per Match
- Team and season-level performance trends.

### 3. Match Analysis
- Match outcomes.
- Wins by runs and wickets.
- Toss decision analysis.
- City and venue analysis.
- Tied and no-result matches.

### 4. Player Analysis
- Top run scorers.
- Leading wicket takers.
- Player performance comparisons.
- Batting and bowling statistics.

### 5. Team Performance
- Team-wise total runs.
- Team-wise wickets.
- Matches won by teams.
- Comparative team performance.

## 📸 Dashboard Screenshots

The `Screenshots` folder contains images of all five Power BI report pages:

- Home Page
- IPL Overview
- Match Analysis
- Player Analysis
- Team Performance

## 📐 Key Performance Indicators (KPIs)

The dashboard includes important cricket performance indicators such as:

- Total Matches
- Total Runs
- Total Wickets
- Total Sixes
- Average Runs per Match
- Matches Won
- Runs Scored by Teams
- Wickets Taken by Players

## 🔍 Key Insights

The dashboard provides insights into:

1. Overall IPL scoring and match statistics.
2. Team-wise scoring and winning performance.
3. Leading batsmen and wicket takers.
4. Match-winning patterns based on runs and wickets.
5. Toss decision patterns.
6. Venue-wise and season-wise performance trends.

## ⚙️ How to Access the Project

1. Clone or download this GitHub repository.
2. Open the `PowerBI` folder.
3. Download and open `IPL_Analytics_Dashboard.pbix` using Microsoft Power BI Desktop.
4. If Power BI requests the source files, update the data source paths to the files in the `Raw_Data` folder.
5. Refresh the data if required.
6. Explore the report pages and interactive filters.

## 🚀 Future Enhancements

- Add advanced player comparison analysis.
- Include detailed batting and bowling performance trends.
- Develop season-wise team comparison dashboards.
- Add venue-based performance analysis.
- Introduce predictive analytics for match outcomes.
- Integrate additional IPL datasets for deeper analysis.

## 👥 Team Members

| S.No | Name |
|---|---|---|
| 1 | [Kancharla Shiva Shankar] | 
| 2 | [Bayyapu Sameer Reddy] | 
| 3 | [Deekonda Sukumar] |


## 🏁 Conclusion

The IPL Analytics & Performance Intelligence project demonstrates how Power BI can be used to transform raw cricket datasets into meaningful visual insights.

By combining match-level data, ball-by-ball statistics, player information, and team details, the project provides an interactive platform for exploring IPL performance from multiple perspectives.

---

**Project Domain:** Data Analytics

**Tool:** Microsoft Power BI

**Repository:** IPL-Data-Analysis-PowerBI

**Developed as part of:** Team Project
