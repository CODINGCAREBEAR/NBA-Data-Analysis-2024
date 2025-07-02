# 🏀 NBA Data Analysis (2004–2024)

This project involves collecting, transforming, and visualizing seasonal NBA data for players and teams from **2004 to 2024**. The data is sourced from [Basketball Reference](https://www.basketball-reference.com/) and the key objectives are to:

- Build Tableau dashboards for player and team stats visualization  
- Predict NBA awards (MVP, DPOY, ROY, etc.) using ML models and visualize player comparisons for players considered for awards
- Analyze trends across 20+ years of NBA history  

---

## 🔗 Live Dashboard

View the Tableau dashboards here:  
- [🔍 NBA Player Stats](https://public.tableau.com/app/profile/carey.harrell/viz/NBAPlayerAnalysis_17104712376710/PlayerOverTime)
- [🔍 NBA Award Prediction Using Machine Learning](https://public.tableau.com/app/profile/carey.harrell/viz/NBAAwardsPrediction/PlayerOverTime)
- [🔍 NBA Award Historical Analysis](https://public.tableau.com/app/profile/carey.harrell/viz/NBAAwardsAnalysis/PlayerOverTime)
- [🔍 NBA League Trends](https://public.tableau.com/app/profile/carey.harrell/viz/NBALeagueTrends/PlayerOverTime)

I later developed a Power BI dashboard equivalent for player stats that can be found here:
- [🔍 NBA Player Stats](https://app.powerbi.com/view?r=eyJrIjoiODU1MjE2MGQtOTk1ZC00N2UwLTk5ZTUtMTMwZTUxOTFkMzJjIiwidCI6IjljZjNkNGIxLTBiZTYtNGI4NS1iOTVkLWY4NjRkMmUxN2Q2OCIsImMiOjF9)

---

## 📁 Project Structure

This project is organized into several directories and key files for efficient data handling, transformation, and analysis:

| Folder/File Name                            | Description                                                                 |
|--------------------------------------------|-----------------------------------------------------------------------------|
| `Complete NBA Analysis.ipynb`              | Main Jupyter notebook for compiling and analyzing NBA data                 |
| `NBA Player Awards/`                        | Contains award data such as MVP, DPOY, ROY, 6MAN, MIP, All-NBA, etc.       |
| `NBA Playoff Results/    | Playoff performance results and team standings                             |
| `NBA Rookies/`                              | Data related to rookie seasons and special rookie notes                    |
| `NBA Standings/`                            | Year-by-year regular season team standings                                 |
| `Player Stats/`                             | Full breakdown of player statistics (basic, advanced, shooting, play-by-play) |
| `Team Stats/`                               | Full breakdown of team statistics and opponent data                        |
| `All Player and Team Stats from 2003–2023.xlsx` | Aggregated player and team stats over 20+ years                            |
| `All Team Stats from 2003–2023 - March 15.xlsx` | Aggregated team stats over 20+ years                            |

## 🧠 Data Sources & Structure

Data ranges from **2003 to 2024** and is categorized into:

### 🔹 Player Data

**Regular Season:**
- Basic Player Stats  
- Advanced Player Stats  
- Play-by-Play Stats  
- Shooting Stats  

**Playoffs:**
- Basic Player Stats  
- Advanced Player Stats  
- Play-by-Play Stats  
- Shooting Stats  

**Awards:**
- MVP (Most Valuable Player)  
- DPOY (Defensive Player of the Year)  
- ROY (Rookie of the Year)  
- 6MAN (Sixth Man of the Year)  
- MIP (Most Improved Player)  
- ALL DEFENSE  
- ALL NBA  
- FINALS MVP  

---

### 🔹 Team Data

**Regular Season:**
- Basic Team Stats  
- Opponent Stats (Basic + Shooting)  
- Advanced Team Stats  
- Team Standings  

**Playoffs:**
- Basic Team Stats  
- Opponent Stats (Basic + Shooting)  
- Advanced Team Stats  
- Team Standings  

---

## 💾 Data Sources

- **Source**: [Basketball Reference](https://www.basketball-reference.com/)
- **Format**: CSV files
- **Location**: `raw_extracted_source_data/`

---

## 🛠️ Tools & Methodologies

This project utilizes a combination of programming tools, data analysis libraries, and machine learning techniques to extract insights from NBA data and build predictive models.

### 🧰 Tools

| Tool / Technology   | Purpose                                                        |
|---------------------|----------------------------------------------------------------|
| **Python**          | Core programming language for data analysis and ML modeling   |
| **Jupyter Notebook**| Interactive environment for data exploration and documentation|
| **Pandas / NumPy**  | Data manipulation and numerical analysis                      |
| **Scikit-learn**    | Machine learning model building and evaluation                |
| **Tableau**         | Data visualization and dashboard creation                     |
| **Excel**           | Data review, aggregation, and manual adjustments              |

---

### ⚙️ Methodologies

| Category                 | Approach / Technique                                                  |
|--------------------------|----------------------------------------------------------------------|
| **Data Collection**       | Gathered stats from Basketball Reference and other historical data sources |
| **Data Cleaning**         | Removed nulls, standardized formats, transformed columns             |
| **Feature Engineering**   | Created new variables (e.g., per-minute stats, efficiency metrics)    |
| **Statistical Analysis**  | Identified trends and performance patterns over seasons              |
| **Predictive Modeling**   | Trained classification models (e.g., logistic regression, random forest) to predict award outcomes |
| **Visualization**         | Built Tableau dashboards for insights on player/team performance     |


---


