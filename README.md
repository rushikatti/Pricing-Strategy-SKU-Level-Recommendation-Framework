# Pricing Strategy & SKU-Level Recommendation Framework

## Overview
This project presents a data-driven pricing framework designed for a consumer brand selling eco-friendly tableware products across online marketplaces. The objective is to move from reactive pricing decisions toward a structured, explainable, and margin-safe pricing approach that can be realistically used by the business.

The framework analyzes multiple business signals and generates SKU-level recommended prices supported by clear rationale and executive-level insights.

---

## Objectives
- Study the provided datasets related to pricing, competition, inventory, demand, and returns  
- Identify key signals that influence pricing decisions  
- Design a logical, rule-based pricing framework  
- Generate defensible SKU-level price recommendations  
- Translate analysis into clear, actionable outputs  

---

## Datasets Used
The analysis integrates the following datasets, aligned at the SKU level:
- Pricing Data (current price, cost, margin)
- Competitor Pricing Data
- Inventory Health Data
- Advertising Performance Data (ROAS, ACOS, conversion rate)
- Historical Sales Data
- Returns Data (7-day, 30-day, 60-day, and 90-day)

---

## Analysis Approach
1. **Data Cleaning & Standardization**  
   Cleaned and validated all datasets, handled missing values, and standardized SKU identifiers and numeric formats.

2. **Feature Engineering**  
   - Calculated minimum viable prices based on cost and margin requirements  
   - Derived average competitor prices for market benchmarking  
   - Created inventory health indicators from supply metrics  
   - Evaluated demand efficiency using ROAS, ACOS, and conversion rates  
   - Classified SKUs into return risk tiers using 90-day return data  

3. **Pricing Logic**  
   - Margin protection enforced as a hard constraint  
   - Competitor prices used as a reference where feasible  
   - Inventory and demand signals applied for price adjustments  
   - Return risk used as a qualitative validation layer  

The framework is intentionally rule-based to ensure transparency and business usability.

---

## Key Outputs
- Final recommended price per SKU  
- Pricing action flag (Increase / Hold)  
- Primary pricing rationale for each decision  
- Return risk classification  
- Executive Pricing Overview Dashboard  

---

## Dashboard
The project includes an executive-ready dashboard that summarizes:
- Pricing headroom across the SKU catalog  
- Distribution of pricing actions  
- Price increase magnitude for eligible SKUs  
- SKU-level recommendations with supporting rationale  

---

## Key Insights
- Pricing flexibility is selective rather than universal  
- Margin constraints are the primary limiter of pricing decisions  
- Demand efficiency is the strongest indicator of safe price increases  
- Returns are best treated as a pricing risk signal rather than a direct pricing lever  

---

## Tools Used
- Microsoft Excel (data analysis, pricing logic, and dashboard creation)

