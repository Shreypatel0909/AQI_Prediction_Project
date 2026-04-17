# AQI Prediction & Analytics System

This project predicts Air Quality Index (AQI) using historical data (2015–2025) and provides interactive analytics.

##  Tech Stack
- Backend: Flask (Python)
- Frontend: HTML, CSS, JavaScript
- Visualization: Chart.js, Plotly
- Machine Learning: XGBoost Regressor

##  Features
- AQI Prediction based on state, area, month, year
- AQI category classification (Good, Moderate, Poor, etc.)
- Interactive analytics dashboard:
  - Top polluted areas
  - Top polluted states
  - AQI category distribution
  - Monthly trends
  - Heatmap (state vs month)

##  Model
- Algorithm: XGBoost Regressor
- Evaluation: R² Score

##  How to Run

```bash
pip install -r requirements.txt
python app.py