# Time Series Analysis for Store Sales
This project uses Python and various data analytics libraries to analyze, visualize, and forecast sales trends for a grocery chain.


## Project Summary:

This project analyzed, visualized, and forecasted sales across Favorita stores (a large grocery chain), focusing on various key metrics such as store types, product clusters, and various time frames.  Using Python and libraries like Pandas, Plotly, and Statsmodels, this project covered time series analysis of store-wide sales, in-depth examination of average sales over time, the impact of store types, holidays, and seasons on sales, and then created a forecasting model that can predict future sales based on existing data.


## Key Information:

**Data Set**:  54 stores, 33 product types, 56 months duration.

**Tools**: Python, Pandas, Plotly, Statsmodels, ARIMA model.

**Techniques**: Data Preprocessing, Visualization, Feature Engineering, Time Series Forecasting.  

**Project Goals**:

* Forecast Favorita store sales and aid in inventory management.

* Understand sales trends and patterns over varying time frames.

* Visualize and analyze the impact of store types, holidays, and other metrics on sales.

* Improve decision-making in business strategy and operations.



## Key Steps:

### Data Import and Preparation:

* Loaded and merged data sets including sales transactions, holidays, oil prices, and store details.

* Created new features and organized data based on time and other parameters.

### Data Visualization:

* Utilized Plotly to create a range of visualizations, such as bar plots, pie charts, and line graphs (see graphs below).

* Visualizations allowed for insights into sales by product family, store type, clusters, and sales over different time frames, to better understand sale trends and patterns.

### Multi-Dimensional and Initial Analysis:

* Aggregated and summarized sales data by time frames (yearly, monthly, weekly)

* Evaluated key metrics and generated visualizations to aid understandings of data patterns and trends.

### Sales Trend Analysis:

* Investigated how sales trends vary based on holidays, store types, and other key parameters.

* Implemented statistical tests and visualizations to identify significant patterns.

### Forecasting:

* Utilized ARIMA models to forecast future sales based on historical data..

* Evaluated the performance of the model using RMSE and MAE.


## Key Results:

**Sales Performance:**

Top-selling products are Grocery and Beverages, with Store Type A and Cluster 5 showing highest sales.

**Time-based Trends:**

Sales peak in December and are lowest in February; highest on weekends, particularly Sundays.

**Impact Analysis:**

Sales peak during Transfer Holidays and Store Type A consistently performs the best regardless of holiday type or season.

**Forecasting Accuracy:**

RMSE is 1419.49 and MAE is 480.55, indicating high accuracy of the ARIMA model given the sales data range of 124717.0.
