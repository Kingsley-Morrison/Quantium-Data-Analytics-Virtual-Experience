Quantium Data Analytics Virtual Experience

📄 Overview

This repository contains the deliverables for the Quantium Data Analytics Job Simulation (via Forage). The project simulates a real-world engagement with a retail client to analyze transaction data, identify customer purchasing behaviors, and evaluate the performance of trial store layouts.

The goal was to act as a Data Analyst to assist the Category Manager in making data-driven strategic decisions.

📂 Project Structure

Task 1: Data Preparation & Customer Analytics

File: Task_1_Data_preparation_and_customer_analytics.ipynb

Objective: Analyze transaction and customer data to identify trends and inconsistencies.

Key Actions:

Performed rigorous data cleaning (handling outliers, correcting data types, removing nulls).

Created new features (e.g., PACK_SIZE, BRAND_NAME) to enrich the dataset.

Segmented customers by LIFESTAGE and PREMIUM_CUSTOMER status.

Outcome: Identified "Mainstream Young Singles/Couples" as a high-value priority segment due to their willingness to pay a premium price per unit.

Task 2: Experimentation & Uplift Testing

File: Task_2_Experimentation_and_uplift_testing.ipynb

Objective: Evaluate the impact of a new trial store layout on sales performance.

Key Actions:

Selected control stores (233, 155, 237) based on similarity to trial stores (77, 86, 88) using Pearson correlations and magnitude distance metrics.

Conducted A/B testing (uplift testing) to measure significant differences in "Total Sales" and "Number of Customers".

Visualized performance trends with 95% confidence intervals.

Outcome: Validated that the trial strategy was successful in Stores 77 and 88, showing statistically significant sales uplift. Store 86 showed no impact, warranting further operational investigation.

Task 3: Commercial Reporting

File: Category Review Chips.pdf

Objective: Synthesize technical findings into a commercial report for stakeholders.

Key Actions:

Translated statistical results into clear business recommendations.

Proposed a rollout strategy for stores resembling the successful trial locations.

Visualized key category drivers and customer affinities (e.g., Tyrrells, Twisties).

🛠️ Tools & Libraries Used

Python: The primary language for analysis.

Pandas & NumPy: For data manipulation and aggregation.

Scipy (Stats): For hypothesis testing (t-tests) and correlation analysis.

Matplotlib & Seaborn: For data visualization and trend plotting.

PowerPoint: For the final executive summary and reporting.

🚀 Key Insights

Sales Drivers: While "Budget Older Families" buy the most packets, "Mainstream Young Singles/Couples" are the most valuable due to population size and price-per-unit willingness.

Trial Success: The new layout strategy delivered a clear ROI in 2 out of 3 trial stores.

Customer Affinity: The target segment has a specific preference for 270g pack sizes (Twisties) and premium brands like Tyrrells, which should be leveraged in future promotions.

Completed by Kingsley Morrison | December 2025
