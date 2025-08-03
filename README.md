# maternal-mortality-rwanda
Capstone project on maternal mortality trends in Rwanda using Big Data Analytics and Power BI

## Introduction
Maternal mortality is a major public health concern in many developing countries. Rwanda, while making significant improvements in health care, still faces challenges related to access, funding, and skilled care. This project investigates the patterns and factors influencing maternal mortality in Rwanda.

## Objectives
- Analyze maternal mortality trends from 2000–2023.
- Study the relationship between maternal mortality and factors such as:
  - Skilled Birth Attendance
  - Antenatal Care Coverage
  - Health Spending
  - Population
- Forecast maternal mortality for 2024–2025 using machine learning and Power BI.
- Present findings via an interactive Power BI dashboard.

  ## Dataset description
The analysis uses publicly available datasets downloaded from the **World Bank** you can see it in the folder above named my-datasets
I used 5datased but i merged them into a final datased called: `final_maternal_data.csv`
You can download all of those dataset using this link:https://data.worldbank.org/indicator/SH.STA.MMRT?locations=RW

  ## Technologies used
- **Python (Jupyter Notebook)**: Data cleaning, analysis, modeling
- **Pandas, Seaborn, Scikit-learn**: For EDA and regression modeling
- **Power BI**: Interactive visualizations, forecasting, DAX
- **DAX (Power BI)**: Calculated KPIs such as % reduction

  ## Methodology
1. **Data Cleaning**: Handled missing values using mean imputation.
2. **Merging**: Combined five datasets on the Year column.
3. **EDA**: Used line plots, bar charts, and correlation matrices.
4. **Modeling**:
   - Trained a Linear Regression model to predict mortality
   - Evaluation: RMSE = 172.15, R² = 0.33
5. **Visualization**:
   - Power BI dashboard with  forecast and slicers
   - Custom DAX measure to calculate % mortality reduction
  
     ## Modeling and Forescating

A linear regression model was used to predict mortality based on multiple features:

- Independent variables: Skilled Birth, Antenatal Care, Health Spending
- Target variable: Maternal Mortality

```python
model = LinearRegression()
model.fit(X_train, y_train).

## Final project dashboard
You can access the final project dashboard by clicking here: https://drive.google.com/file/d/1HS8vXezdfhGvjiEKkihbd1rGFM0e62ez/view?usp=sharing




