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

Executive Summary
* Outcome: Analyzing GameZone's sales, product, marketing, and fulfilment data shows strong top-line growth. However, there are risks from product concentration and issues with the fulfilment process losing control.
* Key Insights:
    * Sales more than doubled in 2020. However, growth is focused on three SKUs: the 27in 4K Gaming Monitor, Nintendo Switch, and PlayStation 5. These three items make up over 80% of revenue.
    * North America and EMEA lead regional sales, while APAC and LATAM lag, indicating untapped growth markets
    * Direct traffic leads in customer acquisition compared to other channels. This suggests either misattribution or that the marketing mix isn’t fully utilised.
    * Refund rates nearly tripled, rising from under 10% in 2019 to about 30% in 2021. This happened alongside shipping timestamps that were logged before purchase timestamps. This points to problems in the supply chain and data logging.
* GameZone's revenue base is narrow. Also, its fulfilment pipeline is losing margin and trust. Product, Marketing, Finance, and Operations teams can use this to decide where to focus first. This approach helps them avoid spreading their efforts too thin.
* Recommended Next Steps:
    1. Operations — Audit product quality and supply chain to halt rising refund rates (target: <10%)
    2. Product/Sales — Bundle top performers with underperforming accessories to lift AOV and reduce SKU concentration
    3. Marketing — Diversify acquisition beyond direct traffic to stabilise sales and reduce channel dependency



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

### Sales Trends

#### Overall Sales Performance 

- Sales more than doubled in early 2020, with all-time highs at the end of 2020
  
<img width="878" height="522" alt="1 Overall Sales Performance " src="https://github.com/user-attachments/assets/7b6ba2ac-47a6-41c1-8d9a-a395b1befcf9" />


- Large dips in the data seem to be a direct result of the drop in sales performance of the 3 top-performing products

<img width="874" height="525" alt="2 Overall sales performance 2" src="https://github.com/user-attachments/assets/69884026-47a7-4b12-b728-f1478a690a02" />

#### Regional Sales Performance 

- The North American region led in sales, with EMEA next. APAC and LATAM lagged, showing there’s room to grow in those markets

<img width="888" height="541" alt="3 Regional sales performance" src="https://github.com/user-attachments/assets/676a6a55-ce1a-4785-aedc-bdc3c8c3acd4" />

- Sales have dipped and spiked, showing a consistent trend across the region. This trend appears geographically independent and on a macro scale


### Product Performance

#### Top Performing Products 

- The top three products were the (27-inch 4K gaming monitor, Nintendo Switch, and Sony PlayStation 5), which accounted for over 80% of sales. This shows a strong reliance on a small subset of items

<img width="900" height="541" alt="3 Top performing products " src="https://github.com/user-attachments/assets/8d64d645-7d41-4741-a44f-a696f1509622" />

- The Nintendo Switch maintained the highest order volume; however was beat out in AOV by several SKUs. Assess methods to boost AOV, like implementing bundle deals

<img width="886" height="534" alt="4 Top performing products 2 " src="https://github.com/user-attachments/assets/41ef5753-0055-4aa8-92c9-3a0a66721cbe" />


#### Underperforming products

- Gaming mice and the "Razor pro gaming headset" pale in sales volume compared to the other SKUs. These products make up less than 1% of sales. This suggests we should evaluate whether to discontinue them or bundle them with top performers to boost average order value (AOV)

### Marketing Channel Effectiveness 

- Traffic from direct channels is much higher than from other channels. This suggests either a mistake in sales accreditation or represents a big opportunity for the marketing team to explore

<img width="880" height="541" alt="5 Marketing Channel effectiveness" src="https://github.com/user-attachments/assets/aa30fb0c-3475-41d3-b91b-3ae64c2d9f3e" />



### Fulfilment Data Integrity 

- Refund rates rose from less <10% in 2019 to ~30% of revenue by 2021. It seems there may be an issue in the supply chain or a drop in supplier quality

<img width="900" height="541" alt="7  Refund rates" src="https://github.com/user-attachments/assets/9892ad0d-31c3-46b4-a7ca-9fa12109e942" />

- Shipping timestamps are logged before the purchase timestamps in several cases. Highlighting potential errors in the data logging system, indicating the operations team need reassess their data logging process
  

---- 
Assumptions and Caveats 

- Sales data is complete and accurate for the years 2019 and 2020
- External factors (e.g holiday seasons) may have impacted customer behaviour and sales but are not modelled directly
- Shipping data irregularity is a result of poor logging processes and is not falsified data 



--- 

<h2>Technologies Used</h2>
<ul>
<li><strong>Languages & Libraries:</strong> Excel </li>
<li><strong>Tools:</strong> Git, GitHub</li>
<li><strong>Data Visualization:</strong>  Tableau </li>

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
