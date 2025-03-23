# GPS Data Preprocessing Project

This project processes a GPS dataset containing travel times, speeds, and other metrics, addressing missing values and outliers to prepare it for machine learning analysis.

## Project Overview
The dataset comes from a GPS device with occasional missing or erratic data. The goal is to clean the data by:
- Removing unnecessary columns with excessive missing values.
- Filling missing values using statistical methods and machine learning predictions.
- Identifying and handling outliers in numerical columns.

## Dataset
- **Source**: `travel_times.csv`
- **Columns**:
  - `Date`: Travel date
  - `StartTime`: Departure time
  - `DayOfWeek`: Day of the week
  - `GoingTo`: Destination (work/home)
  - `Distance`: Distance traveled (km)
  - `MaxSpeed`: Maximum speed (km/h)
  - `AvgSpeed`: Average speed (km/h)
  - `AvgMovingSpeed`: Average moving speed (km/h)
  - `FuelEconomy`: Fuel consumption estimate
  - `TotalTime`: Total travel time (min)
  - `MovingTime`: Moving time (min)
  - `Toll`: Toll road usage (Yes/No)

## Requirements
- Python 3.9+
- Libraries: `numpy`, `pandas`, `catboost`, `matplotlib`, `seaborn`, `lightgbm`

Install dependencies:
```bash
pip install numpy pandas flaml matplotlib seaborn
