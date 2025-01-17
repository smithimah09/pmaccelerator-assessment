# pmaccelerator-assessment

## Project Overview
Used the Global Weather Repository.csv to predict future weather patterns and demonstrate data science skills using a mix of foundational and advanced methods. This dataset provides daily weather data for cities worldwide, featuring over 40 attributes that capture global weather conditions. The dataset is available on Kaggle at Global Weather Repository, contains 47162 records and 41 columns, including variables like temperature, precipitation, wind speed, and air quality metrics.

## Methodology
Data Preprocessing: The dataset was cleaned and processed to extract meaningful features such as date, time, and weather parameters.

Exploratory Data Analysis (EDA): Visualizations like line plots, scatter plots, and correlation matrices were used to identify relationships between variables.

Model Building: Three models (Gradient Boosting, Random Forest, and Linear Regression) were trained to predict precipitation trends. Their performance was evaluated using MAE, RMSE, and R2 scores. An ensemble model was also created to improve prediction accuracy.

Outlier Detection: Isolation Forest was used to detect outliers in temperature and precipitation data. Outliers were visualized on time-series plots.
Results

EDA Insights: Temperature and precipitation trends showed clear seasonal fluctuations. Wind speed was higher in the Northern Hemisphere, while the Southern Hemisphere had lower speeds.

Model Performance: The Gradient Boosting and Random Forest models outperformed Linear Regression, with R2 scores of around 0.4. The ensemble model showed slightly worse performance than individual models.

Outliers: 2359 outliers were detected in temperature and precipitation data. These outliers were marked and visualized for further analysis.

## Dependencies
pandas
numpy
matplotlib
seaborn
sklearn
plotly
## Conclusion
This analysis provides insights into weather patterns, outlier detection, and prediction models for precipitation trends. The project demonstrates the effectiveness of machine learning models in forecasting weather-related variables.
