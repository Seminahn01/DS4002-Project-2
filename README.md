# **Predicting Egg Prices Using Time Series Modeling**

## **Overview**  
This project applies **time series forecasting** using the **ARIMA model** to predict future egg price trends based on historical data from the **U.S. Bureau of Labor Statistics**. The analysis explores price fluctuations, stationarity, and model performance using **RMSE and MAE** metrics.

## **Table of Contents**  
- [Software and Platform](#software-and-platform)  
- [Repository Structure](#repository-structure)  
- [Reproducing Results](#reproducing-results)  
- [License](#license)  
- [References](#references)  

---

## **Software and Platform**  
**Software Used:**  
- **R** – Statistical computing and time series analysis  
- **RStudio** – Recommended IDE for running R scripts  

**Required R Packages:**  
```r
install.packages(c("forecast", "tseries", "astsa", "ggplot2"))

 Predicting_Egg_Prices  
 ┣  DATA  
 ┃ ┣ egg prices.csv # Original dataset  
 ┃ ┗ data_appendix.pdf  # Data description  
 ┣ SCRIPTS  
 ┃ ┣ EggPrice_ARIMA # installing packages, data processing and cleaning, ARIMA modeling, hypothesis testing, and evaluating the model
 ┣ OUTPUT  
 ┃ ┣ ACF and PACF of Transformed Egg Prices.png 
 ┃ ┣ Forecasted Egg Prices.png 
 ┃ ┣ Time Series of Differenced and Long Transformed Egg Prices.png
 ┃ ┣ Time Series of Egg Prices.png
 ┃ ┗ Time Series of Log Transformed Egg Prices.png
 ┣ README.md  # This file  
 ┣ LICENSE.md  # MIT License  
```

## **Reproducing Results**
Follow these **step-by-step instructions** to replicate the analysis and forecast future egg prices.

### **1. Clone the Repository**
First, download the project files to your local machine. This includes the "egg prices.csv" found in the DATA folder and the "EggPrice_ARIMA" found in the SCRIPTS folder. 

## **2. Install Required Software and Dependencies**
This project requires **R** and **RStudio**. Ensure they are installed before proceeding.

### **Install the required R packages:**
```r
install.packages(c("forecast", "tseries", "astsa", "ggplot2"))
```
## 3. Run Code in the SCIRPTS folder
Execute the code under SCRIPTS folder. All code is included within the "EggPrice_ARIMA" script. 

The **Data Processing and Cleaning** section will load in and clean the data.

The **Exploratory Data Analysis** section will make an initial time series plot to check for stationarity then log transform and difference the data to make it stationary, creating time series plots for each. An Augmented-Dickey Fuller Test as well as an ACF and PACF plot will be made to confirm stationarity and evaluate possible ARIMA orders. 

The **ARIMA Modeling** section will test possible ARIMA models and find the best one.

The **Hypothesis Testing and Evaluating Model** section will conduct a Box-Ljung Test for Residuals and forecast the next 12 months in order to find the RMSE and MAE to evaluate the model. 

## **Verify Results**
Once all scripts are executed, check the OUTPUT folder for:
- Forcasted Egg Prices
- ACF and PACF of Transformed Egg Prices
- Time Series of Differenced and Log Transfomred Egg Prices
- Time Series of Egg Prices
- Time Series of Log Transformed Egg Prices

