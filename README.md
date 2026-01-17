# DataCo Supply Chain Analysis: Methodology Demonstration

## Project Overview

This project demonstrates comprehensive analytical methodology applied to supply chain operations data, showcasing skills in data cleaning, exploratory analysis, geospatial visualization, machine learning, and time series analysis. While the dataset exhibited synthetic characteristics that limited business insights, the project successfully demonstrates end-to-end analytical capabilities suitable for authentic business applications.

## Dataset Information

**Dataset:** Refined DataCo Supply Chain Geospatial Dataset  
**Source:** [Kaggle](https://www.kaggle.com/datasets/aaumgupta/refined-dataco-supply-chain-geospatial-dataset) 
**Original Authors:** Fabian Constante, Fernando Silva, and António Pereira  
**Records:** 180,519 supply chain transactions  
**Time Period:** January 1, 2015 - January 31, 2018  
**Geographic Scope:** Global operations across 164 countries  

The dataset contains comprehensive transaction records from a multichannel e-commerce and logistics platform serving three customer segments: Consumer (51.8%), Corporate (30.4%), and Home Office (17.9%). Data includes customer orders, product information, shipping logistics, and delivery performance metrics.

## Research Questions

The analysis was designed to investigate:
- What predicts a late delivery?
- Which orders result in negative profits?
- What patterns or trends exist across regions?
- Which categories sell best in each market?
- How do sales and profitability vary by customer segment?
- Can we identify distinct customer segments based on purchasing behavior?
- Do late deliveries affect profitability?
- How has order volume and delivery performance changed over time?

## Key Findings

**Data Quality Discovery:** Early analysis revealed synthetic data characteristics including uniform 55% late delivery rates across all geographic regions and identical products appearing in contradictory performance clusters. Rather than generate misleading business conclusions, the analysis pivoted to demonstrate methodological capabilities.

**Technical Achievements:**
- Successfully processed and cleaned 180,519 transaction records
- Implemented linear regression models with train/test validation methodology
- Applied K-means clustering identifying 4 distinct order types  
- Created interactive geospatial visualizations with parameter controls
- Applied time series analysis with seasonal decomposition and stationarity testing
- Built comprehensive Tableau dashboard with storytelling narrative

## Repository Structure
```
├── Scripts/
│   ├── DataCo_exploration_and_cleaning__6_1_.ipynb
│   ├── Data_Visualization_Exploration__6_2_.ipynb
│   ├── Geospatial_Analysis__6_3_.ipynb
│   ├── Supervised_Machine_Learning__6_4_.ipynb
│   ├── Unsupervised_Machine_Learning__6_5_.ipynb
│   └── Time_Series_Analysis__6_6_.ipynb
├── Data/
│   ├── Original Data/
│   │   ├── DataCoSupplyChainDatasetRefined.csv.zip
│   │   ├── DescriptionDataCoSupplyChainRefined.csv
│   │   ├── dest_points.geojson
│   │   ├── routes.geojson.zip
│   │   ├── src_points.geojson
│   │   └── world_countries.json
│   └── Prepared Data/
│       ├── dataco_cluster_summary.csv
│       ├── dataco_country_stats.csv
│       ├── dataco_daily_timeseries.csv
│       ├── dataco_department_stats.csv
│       └── dataco_main_clustered.csv.zip
├── Visualizations/
└── README.md
```

## Technologies Used

- **Python**: pandas, numpy, matplotlib, seaborn, scikit-learn
- **Machine Learning**: Linear regression (supervised), K-means clustering (unsupervised)
- **Geospatial Analysis**: folium, geopandas, choropleth mapping
- **Time Series**: statsmodels, seasonal decomposition, stationarity testing
- **Visualization**: Tableau Public, interactive dashboards and storytelling

## Analysis Results

**Tableau Storyboard:** [DataCo Supply Chain Analysis](https://public.tableau.com/views/DataCoSupplyChainAnalysis_17682497658410/DataCoAnalysis)

The interactive storyboard presents key methodology demonstrations and findings. Note that this storyboard focuses on analytical techniques and data quality assessment rather than traditional business insights due to the synthetic nature of the dataset.

## Key Learnings

This project reinforced the critical importance of early data quality validation in analytical workflows. The ability to identify synthetic data patterns and adapt analytical approach accordingly represents essential professional competency for business analytics roles.

## Data Sources & Citations

- **Primary Dataset:** Refined DataCo Supply Chain Geospatial Dataset, Kaggle
- **Original Work:** Constante, F., Silva, F., & Pereira, A. DataCo Smart Supply Chain For Big Data Analysis

## Contact

**Stephen Helvig**  
stephenhelvig@gmail.com

---

*This project was completed as part of the CareerFoundry Data Analytics Immersion Program, Achievement 6: Advanced Analytics.*
