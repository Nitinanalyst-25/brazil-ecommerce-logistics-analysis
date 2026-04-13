# Market Analysis: Brazil E-Commerce Logistics & Friction Gaps

![Project Status](https://img.shields.io/badge/Status-Complete-green?style=for-the-badge)
![Tableau](https://img.shields.io/badge/Tableau-Public-orange?style=for-the-badge&logo=tableau)
![Python](https://img.shields.io/badge/Python-3.12-blue?style=for-the-badge&logo=python)

## Project Overview
This project investigates the complexities of the Brazilian e-commerce landscape, focusing on the relationship between shipping costs and delivery efficiency. By analyzing **100k+ orders** from the Olist dataset, I identified "Logistics Friction Gaps"—regions where higher freight costs fail to guarantee faster delivery due to structural and geographical challenges.

The analysis follows a hybrid workflow: **Python** for data preparation and predictive modeling, and **Tableau** for spatial storytelling and executive-level visualization.

---

## Interactive Dashboard
The final interactive "Logistics Control Dashboard" and Storyboard can be accessed here:
[**View My Tableau Public Portfolio**](https://public.tableau.com/app/profile/nitin.dhiman8857/viz/Analysis-BrazilianE-CommerceLogisticsFriction/Storyboard)

---

## Technical Toolkit
* **Data Manipulation:** SQL (CTEs, Window Functions), Python (Pandas, NumPy).
* **Statistical Analysis:** Correlation analysis and Feature Importance using Scikit-Learn.
* **Visualization:** Tableau (LOD Expressions, Parameter Actions, Geospatial Mapping).
* **Environment:** Anaconda / Jupyter Notebook.

---

## Key Insights & Methodology

### 1. The "Friction Gap" Hypothesis
Using Python, I analyzed the correlation between freight price and delivery time. I discovered that while a positive correlation exists globally, it breaks down in specific regions (North/Northeast), suggesting that infrastructure—not just cost—is the primary driver of delay.

### 2. Regional Benchmarking
I utilized **Tableau LOD Expressions** to benchmark all Brazilian states against the logistics "Best State" (São Paulo). This allows businesses to see exactly how much "logistics tax" they pay in terms of time when shipping to remote states.

### 3. Predictive Narrative
The project concludes with a **4-point Tableau Storyboard** that guides stakeholders from raw delivery data to a "What-If" simulator, allowing for data-driven logistics planning.

---

## Dataset Used
* `data/`: https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce
---
## Final Results & Business Impact

Through this analysis, several critical findings were uncovered that directly impact e-commerce strategy:

* **The 45% Delivery Gap:** In the North and Northeast regions, delivery times were found to be **45% higher** than in the South, despite freight costs being comparable. This confirms that infrastructure is a greater bottleneck than pricing.
* **Friction Identification:** Identified a "High-Friction Zone" in the North where shipping costs and delivery times have a **low correlation (r < 0.3)**, meaning paying for "Express" shipping often fails to yield faster results.
* **Optimal Hub Selection:** Analysis suggests that a decentralized warehouse strategy (moving stock closer to the North/Northeast) could reduce overall delivery lead times.
* **Operational Readiness:** Developed a benchmark tool that allows stakeholders to identify "underperforming" carriers by comparing their actual delivery times against the regional average.
