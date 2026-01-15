# Superstore Sales Analysis (Power BI)

## Business Context
Leadership wants to understand what is driving sales and profitability performance in order to identify risks, inefficiencies, and growth opportunities.

## Analytical Objectives
* Power BI Imported an additional tabled called "Orders$Filters Database" which does not appear to be a business table but rather an Excel artifact.
* No Null or Empty Values were observed in the three tables. (Orders, People Returns).
* Order Date and Ship Dates are correctly identified as date fields.
* The Orders Table each row represents a single item within an order.
* Customer, product, location, and sales information are all stored together, which makes analysis harder without restructuring.

## Dataset Overview
(Completed)

## Analytical Scope & Constraints
(Completed)

## Initial Data Profiling Observations
(To be populated after profiling)

## Data Preparation Decisions
* The extra table created by Excel filters does not add analytical value and will not be used.
* The Orders data contains customer, product, and location details mixed with transaction data, which makes analysis harder without restructuring.
* The Orders table will remain as the main transaction data, keeping dates, quantities, and sales results.
* Customer, product, and location details should be separated so they can be reused across analysis.
* The Returns data indicates whether an entire order was returned, not which individual items were returned, and should be treated accordingly.

## Data Modeling Decisions
(To be populated)

## Measures & Calculations (DAX)
(To be populated)

## Visual Analysis & Storytelling
(To be populated)

## Key Insights
(To be populated)

## Limitations & Next Steps
(To be populated)
