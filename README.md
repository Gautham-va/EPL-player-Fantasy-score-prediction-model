# EPL-player-Fantasy-score-prediction-model
Regression-based model to forecast FPL player scores using historical performance data and feature engineering.
This project predicts Fantasy Premier League (FPL) player scores using regression modeling. It includes data collection from various football websites, feature engineering using rolling stats, exploratory data analysis (EDA), and model training using CatBoost.

## 🚀 Key Highlights
- Merged and cleaned two seasons of player performance data
- Engineered dynamic features: last 5-game stats, cumulative passes/touches
- Built a CatBoost regression model (MAE ≈ 10.7, RMSE ≈ 13.9)
- Visualized insights using Seaborn and Plotly
- Predicted scores for new matches (e.g., ManU vs Arsenal)

## 🛠️ Tech Stack
- Python, Pandas, NumPy
- CatBoost, Scikit-learn
- Seaborn, Plotly, Matplotlib

## 📁 Features Engineered
- Rolling metrics for goals, assists, SoT, tackles, etc.
- Cumulative stats per player
- Positional and team-based features

## 📈 Model Evaluation
- **MAE:** ~10.69  
- **RMSE:** ~13.93  
- Top features: Start, Opponent, Player, Squad, Pos, Saves_Last_5_Games

## 📊 Visual Outputs
- Player performance bar charts
- Correlation heatmap
- Pie chart of average scores by squad
- Boxplot of F_Score distribution

## 🔮 Next Steps
- Add xG/xA data
- Deploy with Streamlit
- Automate weekly match data collection

## 👤 Author
**Gautham V A**  
📍 Kochi, India  
📧 gauthamva2000@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/gautham-v-a-156022255/)
