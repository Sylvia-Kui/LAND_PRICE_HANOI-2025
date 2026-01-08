

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

Each cleaning step was intentional:
- Standardized column names → to avoid mismatches caused by hidden spaces or casing differences.
- Converted strings to floats → original prices were stored as text with commas; conversion made them usable for math/plots.
- Stripped whitespace → values like " 149,88 " became clean numbers (149.88).
- Dropped missing rows → ensured plots and averages reflected real data, not gaps.

📊 Visualizations + Interpretations
Graphs are paired with insights:
- Histograms → Showed that most prices cluster within narrow ranges, with a few wards having much higher values.
- Boxplots → Revealed outliers, especially in VT1, suggesting premium land pockets.
- Line Chart (Ward averages) → Highlighted wards with consistently higher valuations, pointing to localized hotspots.
- Bar Chart (District averages) → District-level disparities emerged, with central districts commanding higher prices.
- Correlation Heatmap → VT1–VT4 were strongly correlated, confirming consistent valuation logic across tiers.

📖 Narrative Additions
What I Learned
- Cleaning messy string-formatted numbers is critical before analysis.
- Correlation analysis can quickly validate whether metrics are redundant or complementary.
- Visualization is most powerful when paired with interpretation.
What Surprised Me
- All four valuation metrics (VT1–VT4) were highly correlated — I expected more variation.
- Some wards had extreme outliers, hinting at unique local conditions.
Limitations
- Dataset is descriptive only; it cannot explain why prices vary.
- No temporal data, so trends over time cannot be analyzed.
- Missing external factors (policy, infrastructure, demand) limit causal insights.
What I Would Do Next
- Merge with urban planning data (new roads, metro lines).
- Add demographic/economic indicators to explain why hotspots exist.
- Explore predictive modeling for future land price trends.

🏁 Conclusion + Next Steps
This project cleaned and visualized Hanoi’s 2025 land price dataset, uncovering correlations, distributions, and spatial disparities.
Next steps include:
- Extending analysis with external datasets for causal insights.
- Building an interactive dashboard (Streamlit) for ward/district exploration.
- Positioning this work as a portfolio piece to showcase data cleaning, visualization, and storytelling skills.


## 🚀 How to Run
1. Clone this repository
2. Install dependencies:
   ```bash
   pip install pandas matplotlib seaborn
  
