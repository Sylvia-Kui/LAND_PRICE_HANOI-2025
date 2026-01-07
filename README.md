
# Hanoi Land Price Analysis (2025)

## 📌 Project Overview
This project analyzes land prices across districts and wards in Hanoi for the year 2025.  
The dataset contains valuation metrics (`VT1–VT4`) for each ward, which are cleaned, transformed, and visualized to uncover meaningful trends and relationships.

## 📂 Dataset
- **Source**: Land Price in Hanoi 2025 (CSV file)
- **Columns**:
  - `District`: Administrative district name
  - `Ward`: Ward name within the district
  - `VT1–VT4`: Land price valuation metrics (numeric, cleaned from string format)

## 🧹 Data Cleaning
Steps performed:
1. Standardized column names
2. Converted price columns from string (with commas/spaces) to numeric floats
3. Removed missing or invalid rows
4. Verified dataset integrity

## 📊 Visualizations
The notebook generates:
- **Histograms**: Distribution of land prices across VT1–VT4
- **Boxplots**: Detection of outliers in valuation metrics
- **Line Charts**: Average prices per ward
- **Bar Charts**: Average prices per district
- **Correlation Heatmap**: Relationships between VT1–VT4

## 🔍 Key Insights
- Strong correlations between valuation metrics (VT1–VT4), showing consistent pricing logic
- District-level differences highlight urban vs. suburban price gaps
- Ward-level trends reveal hotspots of higher valuation

## ❌ Limitations
- Dataset is descriptive only; it cannot explain *why* prices change (e.g., policy, infrastructure, demand).
- External datasets (economic indicators, urban planning data) are needed for causal analysis.

## 🚀 How to Run
1. Clone this repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
