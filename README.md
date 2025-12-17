# Pricing-Strategy-SKU-Level-Recommendation-Framework
This project implements a data-driven pricing strategy framework for a consumer brand selling eco-friendly tableware products across online marketplaces. The framework analyzes multiple business signals and produces SKU-level recommended prices that are realistic and operationally usable.
Objectives

Study the provided pricing, performance, and operational datasets

Identify key signals influencing pricing decisions

Design a logical, rule-based pricing framework

Generate defensible SKU-level price recommendations

Translate analysis into clear, actionable outputs

Datasets Used

The analysis integrates multiple datasets aligned at the SKU level:

Pricing data (current price, cost, margin)

Competitor pricing data

Inventory health metrics

Advertising performance (ROAS, ACOS, conversion rate)

Historical sales data

Product returns data (7, 30, 60, 90 days)

Analysis Approach

Data Cleaning & Standardization
Ensured consistent SKUs, handled missing values, and standardized numeric formats.

Feature Engineering

Minimum viable price based on cost and margin

Average competitor price

Inventory health indicators

Demand efficiency metrics

Return risk tiers based on 90-day returns

Pricing Logic

Margin protection enforced as a hard constraint

Competitor prices used as market reference

Inventory and demand signals used for adjustments

Return risk used as a validation layer

The approach is intentionally rule-based for transparency and business usability.

Key Outputs

Final recommended price per SKU

Pricing action (Increase / Hold)

Primary pricing rationale

Return risk classification

Executive Pricing Overview Dashboard

Dashboard

An executive-ready dashboard summarizes:

Pricing headroom across the catalog

Distribution of pricing actions

Price increase magnitude for eligible SKUs

SKU-level recommendations with rationale

The dashboard bridges analysis and execution.

Key Insights

Pricing flexibility is selective, not universal

Margin constraints are the primary pricing limiter

Demand efficiency is the strongest driver of price increases

Returns are best treated as a pricing risk signal, not a direct input

Tools Used

Microsoft Excel (analysis, pricing logic, dashboard)
