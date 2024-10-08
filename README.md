### New York City Taxi Demand Predictor

This project focuses on predicting taxi demand across different areas of New York City using historical trip data from the NYC Taxi & Limousine Commission (TLC). The objective of the project is to optimize urban mobility by providing insights that help taxi companies, city planners, and authorities enhance service quality, reduce operational costs, and improve traffic management. The predictions are made by applying advanced machine learning models to time-series data, considering various environmental factors and historical trends.

#### Key Features:
- **Data Collection & Preprocessing**: The project retrieves and processes taxi trip data from the TLC for the year 2023 using Python’s requests and BeautifulSoup libraries. Extensive cleaning and feature engineering are performed to ensure the dataset is ready for machine learning. This includes handling missing values, removing outliers, and integrating weather data to capture the influence of environmental conditions on taxi demand.
  
- **Exploratory Data Analysis (EDA)**: EDA reveals insights into taxi usage patterns, such as peak demand hours, geographical hotspots, and the effects of weather and visibility on demand. It also highlights payment preferences and urban travel behaviors.

- **Machine Learning Models**: Multiple regression models were trained and evaluated to predict future taxi demand, including XGBoost, LightGBM, CatBoost, and AdaBoost. The models were optimized using techniques like hyperparameter tuning with Optuna, achieving high predictive accuracy.

- **Real-World Applications**: The predictions from this project can be used by taxi companies for fleet management, urban planners for optimizing traffic flow, and policymakers for improving transportation infrastructure.

#### Results:
The CatBoost model performed best with a Mean Absolute Error (MAE) of 1.5315, showcasing the ability to accurately forecast taxi demand under various conditions. The project highlights the significant impact of weather on demand and uncovers key temporal and spatial demand patterns that can drive strategic decisions in urban mobility management.

