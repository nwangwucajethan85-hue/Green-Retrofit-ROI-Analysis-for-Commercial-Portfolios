**Green Retrofit ROI Analysis: NYC Commercial Portfolios**.
This project transforms raw utility data into a **strategic investment roadmap** by bridging the gap between technical chemical engineering principles and high-stakes real estate strategy. Using the **NYC Local Law 84 (LL84) dataset**, this analysis quantifies the financial impact of sustainability, identifying high-priority assets for "Green" retrofits based on payback periods and carbon reduction potential.
________________________________________
## Executive Summary
•	**The Problem**: Commercial portfolios often struggle to link technical sustainability goals with bottom-line financial performance due to a lack of direct "Total Cost" metrics in public datasets.
•	**The Solution**: Developed a **Proxy Energy Cost model** ($0.025 per kBtu) to simulate a 20% efficiency improvement across a portfolio.
•	**The Results**:
  o	Identified "low-hanging fruit" assets with aggressive payback periods as low as **0.16 years**.
  o	Statistically validated the model with a **0.99 correlation** ($p < 0.001$) between energy intensity and operating costs.
  o	Modeled a portfolio-wide cumulative offset of initial CapEx within a multi-year horizon.
________________________________________
## Technical Stack & Methodology
•	**Language**: R.
•	**Libraries**: tidyverse (Wrangling), ggplot2 (Visualization), PerformanceAnalytics (Statistical Validation), and patchwork (Dashboarding).
•	**Engineering Logic**: Applied numerical simulation logic—derived from gas plant design—to property market trends and energy intensity.
•	**Data Source**: NYC Open Data (LL84 Benchmarking dataset, identifier 5zyy-y8am).
________________________________________
## Key Visualizations
### 1. The Efficiency Frontier
This analysis proves the "Green Hypothesis": higher **Energy Star Scores** directly correlate with lower operating expenditures, inherently boosting **Net Operating Income (NOI)**.
### 2. Statistical Correlation Matrix
Using an engineering-grade correlation matrix, the project confirms that "Proxy Cost" calculations are a reliable substitute for actual utility bills ($p < 0.001$).
### 3. Portfolio Payback Waterfall
A "What-If" optimization model visualizing how an initial investment (modeled at $2.50/sq ft) is recovered through cumulative energy savings over a 5-year period.
________________________________________
## Project Structure
•	**analysis_pipeline.R**: The core R script containing data cleaning, proxy cost engineering, and the ROI optimization model.
•	**data/**: Directory for the NYC LL84 dataset.
•	**plots/**: Exported visualizations including the Correlation Heatmap and Portfolio Waterfall.
________________________________________
## Strategic Insights
•	**Right-Skewed Distribution**: A small percentage of massive, energy-intensive buildings account for the majority of portfolio costs and carbon footprints.
•	**Asset-Specific Targets**: Identified properties like **Storage Garage** and **2537 Broadway** as immediate candidates for retrofits due to exceptional ROI.
________________________________________
### How to Run This Project
1.	Ensure you have R and the tidyverse package installed.
2.	Clone the repository.
3.	Run the script to pull the latest **Master LL84 dataset** directly from NYC Open Data.

**Contact**: [CAJETHAN NWANGWU] | [www.linkedin.com/in/cajethan-nwangwu] | [nwangwucajethan85@gmail.com]

