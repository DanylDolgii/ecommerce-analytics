# E-commerce Analytics Project

## Overview
This project analyzes user behavior in an e-commerce environment, focusing on funnel performance, traffic source efficiency, and campaign effectiveness.

The goal is to identify key drivers of conversion and revenue, and derive actionable insights for marketing optimization.

---

## Dataset
Synthetic multi-table dataset including:
- events (user interactions)
- transactions (purchases)
- campaigns
- customers
- products

> Raw data is not included due to file size limits.  
> To run the analysis, place all CSV files into the `/data` folder.

---

## Analytical Scope

### Funnel Analysis
- view → click → add_to_cart → purchase
- Conversion rates between each stage

### Traffic Source Performance
- Conversion rate by source
- Funnel comparison across channels

### Revenue Analysis
- Total revenue by traffic source
- Average Order Value (AOV)

### Campaign Analysis
- Revenue and performance by campaign
- Channel-level contribution

---

## Key Insights

- **Paid Search** is the primary revenue driver despite not having the highest conversion rate  
- **Email traffic** demonstrates the highest conversion efficiency, making it ideal for retention strategies  
- **Organic traffic** generates the largest volume but underperforms in conversion → optimization opportunity  
- **Direct traffic** shows weak performance, potentially indicating low brand loyalty or tracking limitations  

---

## Business Implications

- Increasing investment in **Paid Search** can scale revenue  
- Expanding **Email campaigns** can improve overall conversion efficiency  
- **Organic traffic** should be optimized (UX, targeting, landing pages)  
- **Direct traffic** requires further investigation (branding or attribution issues)

---

## Tech Stack
- Python (pandas)
- Jupyter Notebook

---

## How to Run

```bash
pip install -r requirements.txt
