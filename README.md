# Formula 1 Race Outcome Prediction and Performance Analysis (1950–2024)

## Project Overview
This project analyzes historical Formula 1 data from 1950 to 2024 and applies machine learning techniques to predict race outcomes such as podium finishes, race wins, and DNFs.

## Objectives
- Understand the structure of Formula 1 historical data
- Perform exploratory data analysis on drivers, constructors, and races
- Create meaningful historical and performance-based features
- Build machine learning models for:
  - Podium prediction
  - Winner prediction
  - DNF prediction

## Dataset
The dataset includes multiple relational tables such as:
- drivers
- constructors
- races
- results
- qualifying
- lap times
- pit stops
- standings
- status

## Project Structure
- `data/raw/` → original CSV files
- `data/processed/` → processed analytical datasets
- `notebooks/` → all analysis and machine learning notebooks
- `README.md` → project summary

## Notebook Flow
1. Data Understanding
2. Data Cleaning
3. Data Merging
4. Exploratory Data Analysis
5. Advanced Analysis
6. Feature Engineering
7. Podium Prediction
8. Winner Prediction
9. DNF Prediction
10. Model Evaluation

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## Key Outputs
- `f1_merged.csv`
- `f1_features.csv`

## Future Improvements
- Add time-aware train/test split
- Add XGBoost or LightGBM models
- Create Streamlit dashboard
- Add SHAP explainability
