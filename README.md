# Solar Power Output Prediction Using Linear Regression

## Project Title: **Solar Power Prediction Using Linear Regression**

## Problem Statement:
The goal of this project is to predict solar power generation based on historical weather data using linear regression. The prediction of solar power is crucial for optimizing energy distribution and usage, especially in areas where solar energy is a primary source. By using a linear regression model, we aim to create a predictive model that can help in forecasting the power output based on environmental factors such as temperature, humidity, and solar irradiance.

## Sustainable Green Technology Goal:
This project aligns with the goal of promoting sustainable energy sources by accurately predicting solar power output. The use of predictive models can optimize the deployment of solar energy, reduce reliance on non-renewable energy sources, and help in planning and managing energy distribution efficiently.

## How to Achieve:
1. **Data Collection**: Gather historical weather data including factors like temperature, humidity, and solar irradiance.
2. **Data Preprocessing**: Clean the dataset to remove any missing or outlier values.
3. **Exploratory Data Analysis**: Analyze the relationships between various features and the target variable (solar power output).
4. **Model Development**: Use linear regression to build a predictive model based on the processed data.
5. **Evaluation**: Evaluate the model’s performance using metrics like RMSE (Root Mean Square Error) and R-squared.

## **Week 1 of Internship Done: Data Preprocessing**

### 1. **Importing Necessary Libraries**:
   In this step, essential libraries like `pandas`, `numpy`, `matplotlib`, `seaborn`, and `scikit-learn` are imported to facilitate data manipulation, visualization, and model building.

### 2. **Loading Dataset and Data Accessing**:
   The dataset is loaded into a pandas DataFrame for easy access and manipulation. The dataset includes columns such as temperature, humidity, and solar irradiance, along with the corresponding solar power output.

### 3. **Data Cleaning**:
   The dataset is cleaned by handling missing values, removing duplicates, and detect anomalies in the data to ensure that the analysis is based on accurate and complete information.

### 4. **Data Statistics**:
   Descriptive statistics (mean, median, standard deviation, etc.) are calculated using decribe() and info() to understand the distribution of the dataset and identify potential correlations between the features and the target variable.

### 5. **Exploratory Data Analysis (EDA)**:
   EDA is performed to visualize the relationships between the independent variables and solar power output using various plots like scatter plots, histograms, and correlation heatmaps.

### 6. **Standardization and Normalization**:
   The features are standardized and normalized to ensure that the data is on the same scale before applying the linear regression model, improving the model’s efficiency and accuracy.

## **Week 2 of Internship Done: Exploratory Data Analysis**
In Week 2, I performed Exploratory Data Analysis (EDA) to explore and understand the dataset for solar power prediction. The analysis was structured into Univariate, Bivariate, and Multivariate categories.

### **Univariate Analysis**
1. Histogram & KDE:
      Temperature: Normally distributed, peaking at moderate temperatures.
      Humidity: Right-skewed, showing dominance of high humidity levels.
      Wind Speed: Right-skewed, with frequent low speeds and occasional high speeds.
      Cloud Cover: Multimodal, reflecting different weather conditions.
      Generated Power: Slightly right-skewed, indicating frequent low outputs.
2. Box Plot: Visualized outliers and distribution of power generation.
3. Pie Chart: Displayed the proportions of cloud cover, wind speed, and power generation.

### Bivariate Analysis
1. Scatter Plots:
      Temperature vs. Power: Moderate positive correlation.
      Humidity vs. Power: Negative correlation, as high humidity suggests clouds.
      Wind Speed vs. Power: Slight positive correlation, higher wind speeds indicate clearer skies.
      Cloud Cover vs. Power: Strong negative correlation.
      Radiation vs. Power: Strong positive correlation.
2. Box Plots: Analyzed cloud cover and wind speed impacts on power generation.
3. Correlation Heatmap:
   Positive Correlations:
   Shortwave Radiation (~0.9),
   Temperature (~0.6).
   Negative Correlations:
   Cloud Cover (~-0.7),
   Humidity (~-0.6).

### Multivariate Analysis
1. Pair Plot: Visualized relationships between generated power and other key features.
2. 3D Scatter Plot: Highlighted that power generation strongly depends on radiation, regardless of temperature.
3. Contour Plot: Mapped relationships among azimuth, zenith, and power.

### **Key Insights**
1. Key Drivers: Shortwave Radiation is the strongest influencer for power generation.
2. Negative Factors: Cloud Cover and Humidity reduce power output.
3. Secondary Factors: Temperature and Wind Speed enhance efficiency but are less impactful.
4. Model Focus: Prioritize shortwave radiation and cloud cover in prediction models.

---
## How to Run:
1. Clone the repository:
   ```bash
   git clone https://github.com/monasri001/SolarPowerPrediction-Edunet-Internship.git
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
3. Open the Jupyter Notebook or vs code:
   ```bash
   jupyter notebook
4. Navigate to the preprocessind&modelling.ipynb file and open it.
5. Run the cells in the notebook.


You can follow these steps for running the project in Jupyter Notebook. Let me know if you need further adjustments!
