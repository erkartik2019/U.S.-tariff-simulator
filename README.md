# U.S.-tariff-simulator
A dynamic Power BI simulator modeling the impact of U.S. tariffs on imports and competitor trade gains, with user-driven tariff scenario analysis at HS-4 product level.

**Purpose and Goal

This project simulates how U.S. imports would change after President Trump announced the Liberation Day tariffs on April 2, 2025, using historical 2024 import data as a baseline.
It allows policymakers, analysts, and businesses to estimate trade losses, sector-wise impacts, and the competitive gains of other countries if Chinese exports collapse.

The simulator also allows user-driven tariff inputs to explore additional scenarios dynamically.

**Objectives
 - Model the expected reduction in U.S. imports by category under the July 9 tariff regime.
 - Allow users to simulate additional tariff scenarios beyond the July 9 baseline.
 - Analyze which partner countries are likely to replace Chinese exports.
 - Visualize trade loss, adjusted imports, and competitive replacement clearly and interactively.

**Data Sources
 - U.S. Imports and Exports 2024 - 	UN Comtrade Data aggregated HS-4 level
 - Tariff Schedule (Post-July 9) - Official White House announcement, supplemented with manual inputs from http://tradecomplianceresourcehub.com/2025/04/24/trump-2-0-tariff-tracker/#country

**Methodology and Assumptions
***Import Elasticity Model

 - Elasticity Assumption: 1% increase in tariff → 1% proportional decrease in import value.

***Competitive Replacement Modeling

 - China’s Trade Loss (post July 9) was assumed to create market gaps.
 - These gaps are proportionally redistributed among top non-Chinese exporters (based on 2024 data).
 - No explicit modeling of trade creation (only trade diversion from China).


**How to Use This Simulator**

 - Select an additional tariff rate (%) using the slider.
 - (Optional) Filter by Partner Country to isolate results.
 - Explore:
    - How imports fall category-wise.
    - How total trade loss % changes.
    - Which countries are poised to replace Chinese exports.

**How to Read This Simulator**
 - KPI Cards:	Show Total Imports, Adjusted Imports (baseline + simulated), and Trade Loss
 - Treemap (Page 1):	Shows which products would see the highest reduction in imports
 - Bar Chart (Page 1)	Compares baseline trade loss and reciprocal trade loss by product
 - Treemap (Page 2)	Shows which countries are most likely to replace China
 - Bar Chart (Page 2)	Matches Competitor Gains vs China Trade Loss by category

**Summary**
The U.S. Tariff Impact Simulator demonstrates that tariff policy shifts can drastically alter trade flows.
It shows how high tariff elasticity can cause imports to collapse — creating opportunities for other trading partners to step in.
The simulator provides an intuitive, dynamic tool to model different tariff scenarios and understand real-world competitive impacts.

Page 1: ![Tariff Simulator_page-0001](https://github.com/user-attachments/assets/78a27095-2a3d-475d-b507-58c4d5f0ec8a)

Page 2: ![Tariff Simulator_page-0002](https://github.com/user-attachments/assets/4bd836c4-db2c-4958-a780-6f67142b178c)

