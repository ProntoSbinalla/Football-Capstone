# Evaluating Football Team Performance Using Advanced Analytics

## Project Overview
This project analyzes team performance across the top 5 European football leagues using advanced metrics and interactive visualizations. The goal is to help scouts, analysts, and fans quickly identify tactical strengths, weaknesses, and performance patterns through data-driven insights.

📊 **Built entirely in Tableau. Python was used initially only for web scraping from FBref.**

## Dashboard Preview
![Dashboard Screenshot](dashboard/Football_Dashboard.png)

🔗 **Dashboard Link**: [View on Google Drive](https://drive.google.com/file/d/1BZxITeQePPXZG5lEVWv5Vw6qUo1zUzUg/view?usp=sharing)  

🔗 Tableau Public Link: [Football Capstone Dashboard](https://public.tableau.com/app/profile/meshach.samuel/viz/FootballCapstone/Dashboard?publish=yes)  

## 📌 Key Insights Displayed

- **Team Selector Panel**: Interactive sidebar listing all teams in the selected league. Clicking on a team updates the entire dashboard.

- **Team Badge and Name**: Clearly displays the selected club’s name and official crest.

- **Recent Form (Last 5 Matches)**: Shows team’s recent results using colored squares — green (W), red (L), gray (D) — for a quick form snapshot.

- **Top Goalscorer & Assister**: Highlights the team's leading scorer and assister, along with their goal/assist totals.

- **Most Common Formation**: A visual formation layout is shown on a football pitch, based on the team’s most frequently used setup.

- **League Selector**: Dropdown filter allows switching between top European leagues like Premier League, La Liga, Serie A, Bundesliga, and Ligue 1.

- **Scatter Plot – Goals Scored vs. Goals Conceded**:
  - **X-axis**: Goals Conceded
  - **Y-axis**: Goals Scored
  - Each dot represents a team, with the selected team highlighted in orange.
  - Enables quick identification of attacking and defensive efficiency across the league.

## Data Source
- **Website**: [FBref.com](https://fbref.com/) (powered by StatsBomb and Opta)
- **Scraped Stats Include**:
  - Goals, xG, Shots, Shots Inside Box, Shot Conversion %
  - Goals Conceded, xGC, Defensive Duel Success Rate, Aerial Duel Success Rate
  - Possession %, Progressive Passes Completed, Passes in Final Third
  - Opponent Passes into Final Third, Crosses Completed
  - Most Common Formation
  - Top Goalscorers and Assisters (last 5 matches)
  - Form over last 5 matches (e.g., 'WWLDL')

## Leagues Covered
- 🇬🇧 **Premier League**  
- 🇮🇹 **Serie A**  
- 🇪🇸 **La Liga**  
- 🇩🇪 **Bundesliga**  
- 🇫🇷 **Ligue 1**

## Methodology
1. **Data Collection**: Team stats, match results, formations, and player contributions scraped from FBref.
2. **Data Cleaning**: Unnecessary columns removed; data reshaped and formatted.
3. **Data Integration**: Combined multiple FBref tables into a clean Tableau-ready structure.
4. **Visualization**: Built an interactive Tableau dashboard featuring bar charts, scatter plots, and pitch diagrams.

## What Makes This Unique
- Focused entirely on **team-level analysis**, not individual players.
- Provides **tactical and statistical context** — form, formation, and scoring efficiency.
- Built with **clarity and interactivity in mind** for fast, actionable insight.

## Future Enhancements
- Add filters for matchweeks or time ranges
- Incorporate xG/xGA, PPDA, and other advanced team metrics
- Enable cross-league team comparison tools

## Credits
- Data: [FBref](https://fbref.com/)
- Project by: Meshach Samuel
- Tools: Tableau, Python (for data scraping only)