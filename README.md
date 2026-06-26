# Multi-Channel Marketing Campaign Performance & Optimization (A/B Testing)

## 1. Project Overview

### Interactive Dashboard Demonstration

*Insert your working Power BI dashboard GIF directly below to demonstrate live data visualization capabilities to recruiters.*

![Power BI Dashboard Walkthrough]([Link to your dashboard GIF here])

### Business Problem

As a marketing agency, our primary objective is to maximize the return on investment (ROI) for our clients' advertising campaigns. Having recently executed parallel campaigns on Facebook and Google Ads, we now need to determine which platform yields superior performance across key metrics — clicks, conversions, and cost-effectiveness — to optimize resource allocation and deliver maximum value for our clients.

* **Primary Research Question:** Which advertising platform is better overall—driving higher performance in terms of clicks, conversions, and cost-effectiveness?

---

## 2. Key Findings

### Headline Metrics

* **The Definitive Winner:** Facebook decisively outperformed Google AdWords across all primary acquisition metrics. Despite receiving only **39.41% ($32K)** of the budget, Facebook generated **double the conversions (4K vs. 2K)** and delivered a **5x higher overall funnel efficiency** (0.5% vs. 0.1% total conversion rate) compared to AdWords.
* **Funnel Friction Zones:** Google AdWords generated massive exposure (**1,722K views**) but suffered severe mid-funnel drop-offs, yielding a weak **1% Click-Through Rate (CTR)** and a **10% click-to-conversion rate**. Conversely, Facebook demonstrated superior engagement with a **2.02% CTR** and a remarkable **26.66% click-to-conversion rate**.
* **Efficiency Windows:** Facebook conversions demonstrated strong stability throughout the week, peaking on **Mondays (~660 conversions)**. In terms of seasonality, **October** stood out as a high-efficiency anomaly, driving annual highs in clicks and conversions despite experiencing lower raw impression volumes.

### Campaign Visualizations

* **Platform Budget Allocation vs. Performance Output:**
*Insert **image_d9a320.png** here to instantly show recruiters the massive discrepancy between spend and actual conversions.*
* **Multi-Tier Campaign Funnel Breakdown:**
*Insert **image_d9a33c.png** here to highlight the funnel efficiency variance between channels.*
* **Monthly Cost Per Conversion (CPC) Efficiency Trends:**
*Insert **image_bb3d88.png** here to display the seasonality curves and the downward cost-per-conversion trajectory by Q4.*

---

## 3. Recommendations

* **Budget Reallocation:** Invert the funding structure by transferring **40% of the AdWords budget ($19.6K)** directly into Facebook. This optimization expands standalone Facebook conversions by **61.25% (+2,450 conversions)** and grows total cross-platform conversions by **27.5% at zero additional cost**.
* **Predictive Scaling:** Deploy the linear regression model ($r = 0.87$) to scale Facebook traffic safely to a daily baseline target of **80 clicks**, which predictably forecasts and secures **19.31 daily conversions** with minimal risk.
* **Chronological Bid Optimization:** Restructure the annual budget to favor the high-efficiency second half of the year (specifically July, November, and October peaks) while pulling back during high-cost windows like March. Apply automated day-of-week bid multipliers to favor **Sundays and Mondays**.
* **Pivot AdWords to Inbound Intent:** Do not abandon Google Ads entirely; instead, combine both platforms into a unified funnel. Transition AdWords away from broad view-generation to capture the passive brand awareness built by Facebook later, restricting its scope strictly to **high-purchase-intent, exact-match keywords** while auditing the landing page to repair mid-funnel drop-offs.

---

## 4. Methodology

To deliver institutional-grade certainty, the dataset was processed through a rigorous multi-stage analytics pipeline:

1. **Exploratory Data Analysis (EDA):** Visualized conversion distributions per tier and tracked spending patterns via bubble charts to establish channel linearity and predictability.
2. **A/B Testing & Funnel Profiling:** Chronologically mapped views, clicks, and conversion volumes weekly and monthly for both campaigns to isolate high-efficiency performance windows and key drop-off zones.
3. **Statistical Analysis (Hypothesis Testing):** Deployed a Welch's T-Test to evaluate whether the difference in daily conversion averages between the platforms was statistically significant. The resulting T-statistic of **32.88** and an explicit $p$-value of **$9.35 \times 10^{-134}$** completely rejected the null hypothesis.
4. **Predictive Analysis & Time-Series Cointegration:** Deployed cointegration models to check for stable, long-term equilibrium between spend and conversions, yielding a score of **-14.76** ($p$-value of **$2.13 \times 10^{-26}$**). This was paired with linear regression modeling ($r = 0.87$) to construct a dependable budget forecasting tool.
5. **Marketing Analytics:** Traffic Funnel Optimization (CTR, CPC, Conversion Rates), Client ROI Maximization, and Multi-Channel Attribution Strategy.

---

## 5. Skills Demonstrated

* **Python :** Pandas, Matplotlib, Seaborn, Plotly, Numpy, Writing functions, building a product funnel, statistics
* **Power BI :** Dax, ETL, calculated columns, data visualization, data modeling

---

## 6. Link to Full Report

* Access the complete, comprehensive documentation here: **[View Full Executive Analysis Report](https://www.google.com/search?q=./Executive_Analysis_Report.pdf)**