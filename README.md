# Fantasy WR Clustering
This project clusters NFL wide receivers (WR) based on their performance metrics to identify similar player profiles. The project uses data from the **nfl_data_py** package and applies k-means clustering after standardizing the data.

## Data
The project uses seasonal performance data for WRs from 2023 to 2024. The data is sourced via the **nfl_data_py** package.

## Methods
  * Data Processing: Filters for WRs only, removes non-numerical columns, and drops missing values.
  * Standardization: Standardizes performance metrics using **StandardScaler** from scikit-learn.
  * Clustering: Uses the k-means clustering algorithm to group WRs based on their performance.
  * Visualization: Provides visualizations using Matplotlib and Plotly to explore clustering results.

### To view the clusters plot, download the html file and open it in any browser.
