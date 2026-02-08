# Datathon 2026: Access to a Livable Planet

Using EPA AQI data, we apply machine learning and data visualization to uncover hidden air quality risk patterns across U.S. counties.

## Repository Contents

- `data_cleaning.ipynb`  
  Loads, merges, and cleans raw EPA AQI by county data. Handles missing values, invalid ratios, feature normalization, and constructs derived indicators used across all downstream analyses.

- `high_risk_cluster.ipynb`  
  Uses K-Means clustering to group counties based on long-term air quality profiles.  
  Focuses on exposure frequency, pollutant composition, and historical intensity to identify high-risk air quality regimes.

- `extreme_event_early_warning.ipynb`  
  Develops an XGBoost-based early warning model for future extreme AQI events using historical trends and event recency features.  
  Emphasizes interpretability and practical risk signals rather than short-term forecasting accuracy.


## 🔗 Project Links

- **🌐 Website**: [https://runa-1117.github.io/datathon-2026/](https://runa-1117.github.io/datathon-2026/)
- **📁 Google Drive**: [https://drive.google.com/drive/u/0/folders/1e-E_GUNo2w_4CTxRWZUdz8_r0qKi5bW5](https://drive.google.com/drive/u/0/folders/1e-E_GUNo2w_4CTxRWZUdz8_r0qKi5bW5)
- **📊 Tableau Public Dashboard 1**: [https://public.tableau.com/app/profile/anna.huang8759/viz/Datathon2026_17705177818560/Dashboard3#1](https://public.tableau.com/app/profile/anna.huang8759/viz/Datathon2026_17705177818560/Dashboard3#1)
- **📊 Tableau Public Dashboard 2**: [https://public.tableau.com/app/profile/anna.huang8759/viz/Datathon2026-dashboard2-breast-cancer/Dashboard1](https://public.tableau.com/app/profile/anna.huang8759/viz/Datathon2026-dashboard2-breast-cancer/Dashboard1)


Runa He, Marco Guo, Anna Huang, Amelia Li • DubsTech Datathon • 2026