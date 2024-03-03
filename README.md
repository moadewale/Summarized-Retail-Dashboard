# Summarized Retail Dashboard - Power BI Project

## Project Overview

### Title: Summarized Retail Dashboard

**Scope:**
Retail dashboard visualizing the summary aimed at providing an overall picture of how the business is performing.

**Data Sources:**
Microsoft Excel

**Cleaning and Visualization Tools:**
Power Query and Power BI

## Understanding the Information in the Data Source:

### Dataset Overview:

**Three Sheets:**
1. Dim Tables
2. Fact Table
3. Aug Data

#### More Insights:

**Dim Tables:**
- Lookup tables used to group sales data.
- Financial year in Australia runs from July to June.
- Classified dates into financial year, financial quarter, and financial year month.
- Contains information about postcodes, suburbs, states, buyers, and managers.

**Fact Table:**
- The dataset spans from January 2016 to July 2017.

## Importing into Power BI for Transformation and Visualization:

- Converted each sheet to tables in Excel.
- Loaded tables into Power BI.

## Cleaning and Visualization:

### Cleaning:

- Ensured correct data types.
- Added new columns to the sales table for Total Sales, Cost, and Gross Profit.
- Changed data types of new columns to decimal numbers.
- Closed and applied changes in Power Query to load into Power BI.

### Visualization:

1. **Establishing Relationships in the Data Model:**
   - Created relationships between sales, managers, and regions tables.
   - Manually created a relationship between the date table and other tables.
   - Deselected the relationship between regions and the sales table.

2. **Fixing the Summarize Icon for Postcode Fields and the Financial Year Month:**
   - Adjusted summarize settings for postcode and financial year month fields.

3. **Formatting Gross Profit, Cost, and Sales:**
   - Formatted columns to currency and removed decimal places.

### Visualizing the Dataset:

1. **KPI of Sales Figure Over Time:**
   - Utilized a KPI visual and displayed figures in millions.

2. **Sales by State Broken Down by Chain:**
   - Used a clustered column chart.
   - Fields: Sales over region, broken down by chain.

3. **Sales and Gross Margin by Financial Year Quarters:**
   - Created charts for sales, gross profit, and financial year quarters.
   - Changed the gross profit to a line visual.
   - Formatted labels to one decimal place.

4. **Breakdown of Sales by Chain with a Pie Chart:**
   - Utilized a pie chart for chain-wise sales breakdown.

5. **Map View Showing State Performances:**
   - Used a globe map visualization with state and sales against state.
   - Concatenated state and country for specificity.
   - Created a new column using the power pivot module for a more specific state representation.
   - Removed the state field and replaced it with the newly created column (state, country).
   - Note: Higher density of colors indicates higher value.

6. **Sales and Category by Chain Using a Bar Chart:**
   - Utilized a bar chart for sales and category by chain due to long category names.
   - Sorted by the largest category and then by sales.

7. **Visual of Sales and Gross Profit by Category Across Time Using a Bubble Chart:**
   - Created a bubble chart with a play axis for financial quarters.
   - Calculated gross profit percentage and formatted to one decimal place.
   - The gross profit represents the size of the bubble.
   - X-axis had the gross profit percentage.

8. **Slicer for State Filtering:**
   - Created a slicer to enable filtering the dashboard by state.

## POWER BI PROJECT LINK:

[Summarized Retail Dashboard](https://app.powerbi.com/view?r=eyJrIjoiZjEyZThmMWUtMzJlMi00ODQxLTkxMWMtOTk1ZjlkYWVlODZhIiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9)

--- 

