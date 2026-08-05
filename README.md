# **Gamezone-Analysis**
---

## Table of Contents

- Background & Overview 
- Dataset
- Executive Summary
- Recommendations
- Analysis and Visualisations
- Assumptions and Caveats 
- Technologies Used
- Installation

---

## Background & Overview 

GameZone is a fictitious video game marketplace and retailer, created to simulate a realistic e-commerce environment for analytical purposes.

The dataset combines anonymised real-world data with AI-generated data to replicate the complexity of genuine business data, including a range of business metrics and dimensions, as well as realistic imperfections such as missing values, nulls, and inconsistent records. This project analyses the data to uncover actionable insights and deliver recommendations across the finance, product, sales, marketing and operations teams 

Insights and recommendations are provided on the following key areas:


- **Sales Trends**: Evaluation of historical sales patterns, focusing on Revenue, Order volume, and Average Order Value (AOV)

- **Product Performance**: An analysis of the different product lines, understanding their impact on sales

- **Marketing Channel Effectiveness**: Analysed customer acquisition sources to measure their effectiveness

- **Fulfilment Data Integrity**: Evaluation of refund data to improve operational visibility and reduce refund volume  


--- 

## Dataset

North Star metrics:<br>
Total Sales<br>Average Order Value (AOV)<br>Refund Rates<br>Total Order Count

[Original Dataset can be found here]()<br>
[ERD of Dataset can be found here]()<br>
[Excel workbook for analysis and more detailed insights can be found here]()

---

## Executive Summary 

- Summarise the outcome of your analysis
- What are the main insights or takeaways?
- How could this analysis inform decision-making?
- Recommendations or next steps for further analysis



---
## Recommendations 


| Action | Owner | Expected Impact |
| :--- | :---: | ---: |
|**Bundle high performers with low performers:**<br> Pair main revenue drivers (27in 4K Gaming Monitor, PlayStation 5, Nintendo Switch) into promotional bundles with underperforming accessories like gaming mice and  "Razor Pro Gaming Headset"|Product/<br>Sales Team|Increase sales of low performing SKUs<br><br>Increased AOV on orders|
|**Diverify acquisition beyond direct sales:**<br> Expand and optimise other digital channels (Social media, Email, Affiliate), to reduce reliance on Direct Traffic| Marketing Team | Reduce sales dips / Stabilise fluctuations |
|**Review profitability for lower performing product lines:**<br> Conduct sanity checks on price-to-volume models across low volume product categories (especially gaming mice, which account for <1% of sales)| Finance Team | Potential discontinuation of product SKU <br> or <br> Inclusion as part of a bundle |
|**Audit quality & Supply chain:**<br>Conduct sanity checks focusing on (Product quality, Packaging, Supplier Stability) | Operations Team| Halt and lower rapidly rising refund rates from ~30%<br>**(Target: <10%)**|
|**Clean up fullfilment Data logging:**<br>Resolve nonsenseical timestamps in shipping logging system | Operations Team| Restore realiable tracking and operational visibility|



--- 

## Analysis & Visualizations

Summarise your findings, insights, and visualisations:

- Describe the key trends and patterns you observed
- Show charts, graphs, and tables
- Include important observations or correlations found in the data


---- 
Assumptions and Caveats 





--- 

<h2>Technologies Used</h2>
<ul>
<li><strong>Languages & Libraries:</strong> Python, Pandas, NumPy, SQL, Matplotlib, Seaborn</li>
<li><strong>Tools:</strong> Jupyter Notebook, VS Code, Git, GitHub</li>
<li><strong>Data Visualization:</strong> Power BI / Tableau (if applicable)</li>
</ul>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
<img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas">
<img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy">
<img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=matplotlib&logoColor=white" alt="Matplotlib">
<img src="https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge&logo=seaborn&logoColor=white" alt="Seaborn">
</p>

---

## Installation

Example of step-by-step instructions to set up the project locally:

- Clone the repository
git clone <https://github.com/YOUR_USERNAME/YOUR_REPO.git>

- Navigate to the project folder
cd YOUR_REPO

- Install dependencies
pip install -r requirements.txt

- Launch Jupyter Notebook
jupyter notebook

---
​
## Usage

Instructions for using the project:

1. Open the main notebook (analysis.ipynb)
2. Run each cell sequentially to reproduce the analysis
3. Visualisations and results will be generated automatically
   
Include screenshots of your visualisations if available:

---

## License

This project is licensed under the MIT License – feel free to use and modify it.
