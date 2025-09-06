
# 📊 Analysis of International Tourist Arrivals in Turkey (2008–2020)

**Authors:**  
- Situma Patrick Nyongesa  

**Institution:**  
Kirinyaga University — Department of Statistics  

**Date:**  
2023  

---

## 📖 Project Overview
This project analyzes the patterns of **international tourist arrivals in Turkey between 2008 and 2020**, focusing on the effects of geopolitical events, economic crises, and the COVID-19 pandemic. Using **descriptive statistics, correlation analysis, ANOVA, paired t-tests, and time series modeling (ARIMA)**, the study investigates how external shocks influenced tourism trends.

---

## 📑 Table of Contents
- [Introduction](#introduction)  
- [Research Questions](#research-questions)  
- [Expected Outcomes](#expected-outcomes)  
- [Data Overview](#data-overview)  
- [Results and Analysis](#results-and-analysis)  
  - [Descriptive Statistics](#descriptive-statistics)  
  - [Trend Analysis](#trend-analysis)  
  - [Correlation Analysis](#correlation-analysis)  
  - [T-Test](#t-test)  
  - [ANOVA](#anova)  
  - [Time Series Analysis](#time-series-analysis)  
- [Discussion](#discussion)  
- [Conclusion](#conclusion)  
- [Future Research Directions](#future-research-directions)  
- [Repository Structure](#repository-structure)  
- [How to Use This Repository](#how-to-use-this-repository)  
- [License](#license)  

---

## Introduction
Tourism is a critical driver of Turkey’s economy. This project investigates how **international arrivals fluctuated between 2008 and 2020**, with emphasis on external factors such as the **2016 coup attempt**, the **2018 currency crisis**, and the **2020 COVID-19 pandemic**.

---

## Research Questions
1. How did the number of international tourists change between 2008–2020?  
2. Which nationalities experienced the largest declines, and why?  
3. What seasonal patterns existed before and after crises?  
4. How did political instability, economic crises, and global pandemics affect arrivals?  
5. Which nationalities recovered faster, and what explains this?  

---

## Expected Outcomes
- Sharp declines in 2016 and 2020.  
- European tourists declined more than Middle Eastern ones.  
- Seasonal peaks reduced after 2016.  
- Major events linked to steep drops.  
- Neighbouring countries showed quicker recovery.  

---

## Data Overview
- **Period:** 2008–2020  
- **Variables:** Tourist arrivals by country & year  
- **Size:** 151 valid observations  
- **Total Arrivals (2008–2020):** 395,153,133 tourists  

---

## Results and Analysis

### Descriptive Statistics
- **Mean arrivals per year:** ~2.6M (SD = 1.42M)  
- **Min arrivals:** 47,971 (2020)  
- **Max arrivals:** 6.9M (2015)  

### Trend Analysis
- Growth (2008–2015) → Sharp decline (2016) → Recovery (2017–2019) → Major collapse (2020).  

### Correlation Analysis
- Weak correlation between **Year** and **Arrivals** (r = 0.034, p = .680).  
- Strong inter-country correlations (Germany, Russia, France, USA highly linked).  

### T-Test
- Significant decline in arrivals:  
  - t(150) = -18.94, p < .001  
  - Cohen’s d = -1.54 (large effect size)  

### ANOVA
- Significant differences across years: F(12, 138) = 1.909, p = .038  
- Variations stronger for China, India, Russia, USA  

### Time Series Analysis
- **Model:** ARIMA(0,0,2)  
- **R² = 0.737** → explained 73.7% of variance  
- **MAPE = 106%** → high error → external factors missing  

---

## Discussion
- Declines closely tied to **geopolitical & global events**  
- Some countries (e.g., Russia, Germany) had steep drops in 2016  
- 2020 (COVID-19) caused unprecedented collapse  
- Resilience observed among neighbouring and Middle Eastern markets  

---

## Conclusion
- Turkey’s tourism was **significantly disrupted** by global events  
- Statistical evidence confirms **large, meaningful declines**  
- Policymakers should adopt **adaptive recovery strategies**:  
  - Flexible visa policies  
  - Crisis management frameworks  
  - Diversification of tourist source markets  

---

## Future Research Directions
- Long-term resilience of tourism after global shocks  
- Impact of **digital visas** on recovery  
- Role of **climate change** on seasonal flows  

---

## Repository Structure

