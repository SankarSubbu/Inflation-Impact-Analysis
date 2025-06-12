# Impact of Inflation: Case Study
The dataset is in the data folder.

The datasets comprises historical data on the exchange rate between the Indian Rupee (INR) and the US Dollar (USD) from 1980 to 2024, along with corresponding inflation rates for India and the United States. 
The exchange rate data includes the average annual INR/USD exchange rate, while the inflation data captures the annual percentage change in the Consumer Price Index (CPI) for both countries. 
The dataset is structured with columns for the year, exchange rate, and inflation rates for each country, which enables a longitudinal analysis of the relationship between inflation and exchange rates over time.

# Problem
The objective of this analysis is to determine the extent to which inflation rates in India and the United States influence the INR/USD exchange rate over time. 
Specifically, the task is to:
  * Identify the correlation between inflation rates and the exchange rate, considering potential lag effects.
  * Analyze whether the Purchasing Power Parity (PPP) theory holds by comparing the actual exchange rate with the expected exchange rate based on inflation differentials.
  * Explore any deviations from the expected PPP-based exchange rate to uncover other economic factors that may contribute to exchange rate fluctuations.

### 🔍 Objective
This project aims to analyze how inflation rates in India and the United States influence the INR/USD exchange rate over time.

---

### 🧩 Problem Statements and Solutions

#### 1. 📊 Identify the correlation between inflation rates and exchange rate (with lag effects)

**✅ Solution:**  
The code computes year-over-year inflation rates for India and the US and examines their correlation with the INR/USD exchange rate using time-lag analysis.

**📌 Method:**
- Visualized inflation trends alongside exchange rates.
- Calculated Pearson correlation between lagged inflation rates and exchange rates.

  ---

  #### 2. ⚖️ Analyze whether the PPP (Purchasing Power Parity) theory holds

**✅ Solution:**  
Used the initial exchange rate and relative inflation rates to calculate the expected exchange rate based on PPP, then compared it with actual exchange rate data.

**📌 Method:**
- Formula used:  
  \[
  \text{Expected Rate} = \text{Initial Rate} \times \prod \left( \frac{1 + \text{India Inflation}}{1 + \text{US Inflation}} \right)
  \]
- Plotted both actual and PPP-based rates.

---

#### 3. 🌐 Explore deviations from PPP-based expected rate

**✅ Solution:**  
The code calculates the deviation between actual and PPP-based exchange rates to explore external economic influences (like interest rates, capital flows, geopolitical factors).

**📌 Method:**
- Added a new column for deviation.
- Visualized and analyzed spikes and patterns.

---

### ✅ Conclusion

- Inflation trends partially explain exchange rate movements.
- PPP theory gives a strong long-term foundation, but real-world rates deviate due to market forces.
- Future extensions could include interest rate differentials or capital flow data.
