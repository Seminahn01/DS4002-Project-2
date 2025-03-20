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
 ┃ ┣ egg_prices_raw.csv  # Original dataset  
 ┃ ┣ egg_prices_clean.csv  # Processed dataset  
 ┃ ┗ data_appendix.pdf  # Data description  
 ┣ SCRIPTS  
 ┃ ┣ # Data cleaning & transformation  
 ┃ ┣ # Exploratory data analysis  
 ┃ ┣ # ARIMA model fitting  
 ┃ ┣ # RMSE & MAE calculations  
 ┃ ┗ # Forecasting egg prices  
 ┣ OUTPUT  
 ┃ ┣ forecast_plot.png  # Forecast visualization  
 ┃ ┣ residual_diagnostics.png  # Residual analysis  
 ┃ ┗ model_performance_metrics.txt  # RMSE & MAE results  
 ┣ README.md  # This file  
 ┣ LICENSE.md  # MIT License  
```


## **Reproducing Results**
Follow these **step-by-step instructions** to replicate the analysis and forecast future egg prices.

### **1. Clone the Repository**
First, download the project files to your local machine.

git clone https://github.com/your-repo-link
cd Predicting_Egg_Prices

## **2. Install Required Software and Dependencies**
This project requires **R** and **RStudio**. Ensure they are installed before proceeding.

### **Install the required R packages:**
```r
install.packages(c("forecast", "tseries", "astsa", "ggplot2"))
```
## 3. Run Scripts in Order
Execute the R scripts in SCRIPTS folder in the following order:

### Step 1: Data Processing
### Step 2: Exploratory Data Analysis 
### Step 3: Fit AIRMA Model
### Step 4: Evaluate Model Performance
### Step 5: Forecast Future Egg Prices

## **Verify Results**
Once all scripts are executed, check the OUTPUT folder for:
