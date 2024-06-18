# -COVID-19-Data-Analysis
COVID-19 Data Analysis This repository encompasses an analysis of COVID-19 data, with a focus on the conditions contributing to COVID-19 fatalities across various demographics and locations within the United States. 
## COVID-19 Data Analysis

This repository encompasses an analysis of COVID-19 data, with a focus on the conditions contributing to COVID-19 fatalities across various demographics and locations within the United States. The objective was to derive insights into the factors influencing COVID-19 mortality and to offer data-driven recommendations for public health strategies and policy-making.

## Project Overview

This project leverages real-world data on COVID-19 deaths and contributing conditions from the Centers for Disease Control and Prevention (CDC). The aim was to comprehend the impact of different conditions on COVID-19 deaths, assess geographical variations, and create predictive models to aid public health officials and policymakers in effectively targeting interventions.

## Repository Structure

### Project Management: Contains the project brief, outlining the goals and expectations of the analysis.

### Data: Includes a PDF file with links to the datasets and files utilized in the analysis.

### Scripts: Contains all Python scripts used in the data analysis, organized as Jupyter Notebooks.

### 04 Analysis/Visualizations: Houses image files of the visualizations created during the analysis.

### 05 Final Report:Features the Tableau Public storyboard as a PDF file, viewable on Tableau Public [here](link).

### Key Questions Addressed

- Which conditions are most strongly associated with COVID-19 deaths?
- How do COVID-19 death rates differ across states and age groups?
- What are the geographical patterns in COVID-19 death rates and contributing conditions across the United States?
- How can linear regression and clustering analyses predict and understand COVID-19 mortality?
- What are the temporal trends and seasonal patterns in COVID-19 deaths and contributing conditions?

## Tools Used

### Python: Primary programming language for data analysis.
### Pandas: For data manipulation and analysis.
### NumPy: For numerical operations.
### Matplotlib & Seaborn:** For creating data visualizations.
### Scikit-learn: For implementing machine learning models.
### Statsmodels: For time series analysis and ARIMA modeling.
### Geopandas: For geographical data manipulation and visualization.
### Plotly: For interactive visualizations.
### Tableau Public: For crafting interactive visualizations and dashboards.

## Visualizations

This project features a variety of visualizations such as scatter plots, choropleth maps, bar charts, and time-series plots. These visualizations highlight the impact of different conditions on COVID-19 mortality, geographical differences, and temporal trends.

## Analysis Sections

### Initial Data Exploration
Dataset Exploration: Understanding the structure and key statistics.
Data Cleaning and Preprocessing:Handling missing values, outliers, and data type conversions.

### Geographical Analysis
Choropleth Maps:Visualizing total COVID-19 deaths and death rates per 100,000 population across states.
Insights: Identifying high-impact regions and patterns.

### Linear Regression Analysis
Model Building: Developing a regression model to predict COVID-19 deaths based on the number of mentions of conditions.
Performance Evaluation: Assessing the model using Mean Squared Error (MSE) and R-squared score.

### Cluster Analysis
K-means Clustering: Identifying clusters of states with similar COVID-19 impact.
Cluster Interpretation: Analyzing the characteristics and severity of each cluster.

### Time Series Analysis
Trend and Seasonality: Decomposing time series data to identify trends and seasonal patterns.
Stationarity Check: Performing the Dickey-Fuller test and differencing to achieve stationarity.
Autocorrelation Analysis: Using ACF and PACF plots to examine the autocorrelation structure of the time series data.

## Conclusion and Recommendations

The analysis provided actionable insights into the factors contributing to COVID-19 mortality, emphasizing the significance of demographic and condition-specific factors. The findings support targeted public health interventions and resource allocation strategies to better prepare for future health crises.

## Limitations and Potential Biases

Provisional Nature of Data: Data is provisional, and conclusions may require revision as finalized data becomes available.
Reporting Delays: Delays in reporting can affect the completeness of recent data.
Inconsistent Reporting Standards: Variability in state-level reporting standards may impact reliability.
Multiple Conditions: Presence of multiple conditions per death complicates the analysis.
Double Counting Risk: Deaths involving multiple conditions are counted in each relevant category.
Population Data: Analysis is based on 2020 population data, which may not reflect changes over time.

## Recommendations for Future Work

Enhanced Clustering: Perform clustering analyses on additional conditions and demographics.
Predictive Modeling: Develop models to identify high-risk populations and enhance public health strategies.
