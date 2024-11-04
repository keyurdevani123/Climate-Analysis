# Climate Analysis

This project provides an analysis of climate-related data, exploring various environmental attributes such as temperature, CO₂ emissions, precipitation, humidity, and wind speed. The goal is to understand the relationships between these attributes and their potential impact on sea level rise.

## Project Overview
The analysis includes:
- Data cleaning and preprocessing
- Exploratory data analysis with visualizations
- Statistical analysis and correlation heatmaps
- Outlier detection and handling
- Building regression models to predict sea level rise based on climate data

## Data
The dataset includes the following columns:
- `Temperature`: Average temperature readings.
- `CO₂ Emissions`: Levels of carbon dioxide emissions.
- `Precipitation`: Precipitation measurements.
- `Humidity`: Humidity percentage.
- `Wind Speed`: Average wind speed.
- `Sea Level Rise`: Observed or predicted rise in sea level.

## Notable Features
- **Exploratory Data Analysis (EDA)**: Visualizations and summaries of climate attributes.
- **Correlation Analysis**: Heatmaps to show relationships between attributes.
- **Outlier Detection and Handling**: Identification and removal of outliers to improve model accuracy.
- **Regression Models**: Comparison of Linear Regression, Random Forest, Decision Tree, and Support Vector Regression models.

## Results
The models are evaluated based on:
- Mean Squared Error (MSE)
- R² Score (goodness of fit)
  
After evaluation, we determined that the best model for predicting sea level rise was selected based on the lowest MSE and highest R² Score.

## Getting Started
To run the notebook:
1. Install necessary libraries if not already installed:
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn
    ```
2. Open the notebook in Jupyter:
    ```bash
    jupyter notebook "climate-analysis.ipynb"
    ```
   
3. Run the cells sequentially to perform data loading, analysis, and model training.

## Repository Structure
- `climate-analysis.ipynb`: Main notebook with data analysis and model training.
- `README.md`: Project overview and instructions.

## License
This project is licensed under the MIT License.

---

