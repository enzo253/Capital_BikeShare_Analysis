# Capital Bikeshare Data Analysis and Prediction

## Project Overview
This project focuses on analyzing Capital Bikeshare data to understand urban mobility trends and predict daily rider counts. The analysis leverages ward shapefiles for spatial data integration, exploratory data analysis (EDA) using Seaborn and Matplotlib for uncovering insights, and machine learning (ML) models for predictive analytics.

## Data Sources
- **Capital Bikeshare Trip Data:** Includes trip details such as start/end station, timestamps, and user types.
- **Ward Shapefiles:** Used to consolidate geographic and station data for enhanced spatial analysis.
- **Weather Data:** Incorporated for environmental factors influencing rider trends.

## Methodology
### 1. Data Consolidation
- Merged Capital Bikeshare data with ward shapefiles for spatial context.
- Cleaned and preprocessed the data to handle missing values, incorrect entries, and outliers.

### 2. Exploratory Data Analysis (EDA)
- Utilized Seaborn and Matplotlib to visualize trip patterns by time of day, day of the week, and seasonal trends.
- Analyzed rider demographics and popular stations to uncover mobility behavior.
- Examined correlations between weather conditions, holidays, and trip volumes.

### 3. Machine Learning Model
- Implemented regression models to predict daily rider counts.
- Evaluated multiple models, including:
  - Linear Regression
  - Random Forest Regressor
  - XGBoost Regressor
- Performance was assessed using RMSE, MAE, and R-squared metrics.

## Key Findings
- **Peak Riding Times:** Weekday commuting hours and weekend afternoons saw the highest activity.
- **Weather Impact:** Temperature and precipitation significantly influenced rider counts.
- **Station Popularity:** Stations near metro hubs and tourist destinations showed increased usage.

## Requirements
Install the following dependencies to run the project:
```bash
pip install pandas numpy scikit-learn geopandas matplotlib seaborn
```

## Usage
1. Clone this repository:
```bash
git clone <repository_url>
```
2. Navigate to the project folder:
```bash
cd capital_bikeshare_analysis
```
3. Open the analysis and prediction notebook:
```bash
jupyter notebook Bike_TypePred.ipynb
```

## Future Enhancements
- Incorporate real-time data for improved forecasting.
- Explore additional factors like traffic data or city events to enhance prediction accuracy.
- Develop a web-based dashboard for interactive insights.

## Author
Enzo Würtele 

## License
This project is licensed under the MIT License.


