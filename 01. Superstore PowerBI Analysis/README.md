# Superstore Sales Analysis (Power BI)

## Business Context
Leadership wants to understand what is driving sales and profitability performance in order to identify risks, inefficiencies, and growth opportunities.

## Analytical Objectives
(To be defined after data preparation and validation)

## Dataset Overview
(Completed)

## Analytical Scope & Constraints
(Completed)

## Initial Data Profiling Observations
* Power BI Imported an additional tabled called "Orders$Filters Database" which does not appear to be a business table but rather an Excel artifact.
* No Null or Empty Values were observed in the three tables. (Orders, People Returns).
* Order Date and Ship Dates are correctly identified as date fields.
* The Orders Table each row represents a single item within an order.
* Customer, product, location, and sales information are all stored together, which makes analysis harder without restructuring.

## Data Preparation Decisions
* The extra table created by Excel filters does not add analytical value and will not be used.
* The Orders data contains customer, product, and location details mixed with transaction data, which makes analysis harder without restructuring.
* The Orders table will remain as the main transaction data, keeping dates, quantities, and sales results.
* Customer, product, and location details should be separated so they can be reused across analysis.
* The Returns data indicates whether an entire order was returned, not which individual items were returned, and should be treated accordingly.
* Created a separate customers table from Orders using Customer ID. Customer Tables contains these columns: Customer_ID, Customer_Name and Segment.
* Removed duplicates from Customers Table using Customer_ID Column so each customer only appears once as a result number of rows reduced from 999+ to 793.
* Removed Customer_Name and Segment Columns from Orders Table. Kept Customer_ID column in orders to still be able to link order to customers.
* Created a separate Locations table from Orders table using Postal Code. Locations table containes these columns: Country, City, State, Postal Code and Region.
* Removed duplicates from the Locations Table using Postal_Code Column so each Postal code only appears once, as a result the number of rows reduced from 999+ to 631.
* Removed the following columns from Order Table: Country, City, Region, State and kept only Postal_Code Column to still be able to link orders to their location. 

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
