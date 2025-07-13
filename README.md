
# 🏏 IPL 2024 Match Analysis: RCB vs DC using Python

## 📌 Objective
Compare the performance of **Royal Challengers Bangalore (RCB)** vs **Delhi Capitals (DC)** during their IPL 2024 clash using statistical analysis.

## 📁 Dataset Overview
- Contains both match-level and ball-by-ball data:
  - `Team`, `Players`, `Overs`, `Runs`, `Wickets`
  - `Toss`, `Venue`, `Innings`, `Match Outcome`
- Enables both macro (team) and micro (player/ball) level insights.

## 🛠️ Tools & Technologies
- **Python**: `Pandas`, `NumPy` for data wrangling
- **Visualization**: `Matplotlib`, `Seaborn`
- **Notebook**: Jupyter

## 🧹 Data Preprocessing
- Cleaned inconsistent player/team names
- Merged innings data for comparison
- Extracted phase-based stats: Powerplay, Middle Overs, Death Overs

## 📊 Analysis Performed
- **Run progression** and scoring patterns over 20 overs
- Individual player stats: `Strike Rate`, `Economy`, `Boundaries`
- Fall of wickets and partnerships
- Toss impact and venue-based performance
- Over-by-over comparison of team performance

## 📈 Visualizations
- Line graphs for run rates
- Bar charts for player contributions
- Heatmaps for overs vs runs/wickets

## 💡 Key Insights
- RCB dominated the middle overs, but lost momentum in the final phase.
- DC capitalized on early wickets and bowled tighter lines.
- Toss decision played a significant role on a batting-friendly pitch.

## ✅ Recommendations
- RCB: Rework bowling strategy in **death overs**
- DC: Improve batting consistency in **middle overs**
- Utilize toss strategically with better pitch prediction

## 📦 Deliverables
- 📘 Python notebook with match analysis and commentary
- 📊 Visuals for over-phase breakdowns
- 📝 Tactical report for team strategy refinement
