
# Hanoi Land Price Analysis (2025)
# 🏙️ Hanoi Land Price Analysis (2025)

## 📘 Overview
This project explores land valuation data across Hanoi’s districts and wards for the year 2025.  
It demonstrates **data cleaning**, **visualization**, and **exploratory analysis** using Python, pandas, matplotlib, and seaborn.

## 📂 Dataset
- **File**: `Land Price in Hanoi 2025 new.csv`
- **Columns**:
  - `District`: Administrative district name
  - `Ward`: Ward name within the district
  - `VT1–VT4`: Land price valuation metrics (originally string-formatted, cleaned to floats)

## 🧹 Data Cleaning
Steps performed:
1. Standardized column names
2. Converted string-formatted prices (e.g. `" 149,88 "`) into numeric floats (`149.88`)
3. Removed rows with missing or invalid values
4. Verified dataset integrity for analysis

## 📊 Visualizations
The notebook generates:
- **Histograms**: Distribution of VT1–VT4 prices
- **Boxplots**: Outlier detection
- **Line Chart**: Average prices per ward
- **Bar Chart**: Average prices per district
- **Heatmap**: Correlation between VT1–VT4

## 🔍 Key Insights
- Strong correlations between valuation metrics (VT1–VT4), showing consistent pricing logic
- District-level differences highlight urban vs. suburban price gaps
- Ward-level trends reveal localized hotspots and anomalies

## ❌ Limitations
- Dataset is descriptive only; it cannot explain *why* prices vary
- No temporal or external factors (e.g. infrastructure, policy, demand) included

## 🚀 How to Run
1. Clone this repository
2. Install dependencies:
   ```bash
   pip install pandas matplotlib seaborn
  
