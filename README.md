# 🏃 Garmin Activities Data Analysis

This Jupyter Notebook performs exploratory data analysis (EDA) on personal fitness data exported from Garmin Connect. It uses Python libraries such as **Pandas**, **Seaborn**, and **Matplotlib** to explore trends, visualize activity statistics, and identify patterns in performance.

---

## 📁 Dataset

- **File**: `My Garmin Activities.csv`
- **Source**: Exported from [Garmin Connect](https://connect.garmin.com/)
- **Contents**: Each row represents a fitness activity (e.g., running, cycling).
- **Important columns**:
  - `Date`
  - `Distance` (in miles)
  - `Avg Pace` (min/mile)
  - `Avg HR` (heart rate)
  - `Calories`
---

## 📊 Features & Analysis

### ✅ Data Preparation
- Convert date columns to `datetime`.
- Extract `Year` and `Month` for time-based analysis.
- Clean `Avg Pace` (convert mm:ss to float).
- Handle missing or non-numeric entries.

### 📈 Exploratory Visualizations
- **Yearly Stats**:
  - Total Distance
  - Average Heart Rate
  - Calories Burned
- **Monthly Trends for 2024**:
  - Distance, Heart Rate, Calories (monthly breakdown)
- **Cadence vs. Pace**:
  - Scatter plot showing correlation between `Avg Run Cadence` and `Avg Pace` with regression line.
---

## 📦 Requirements

Make sure you have the following Python libraries installed:

```bash
pip install pandas matplotlib seaborn
