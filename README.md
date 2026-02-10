User Story: Visualize Scraped Book Data with Power BI

As a data analyst
I want to import and visualize the scraped book data in Power BI
So that I can generate insightful dashboards and perform deeper analysis on book pricing, ratings, and availability trends.

Acceptance Criteria:
Power BI Data Integration
Import the books_data.csv file containing the scraped book data.

Ensure proper data types for each column (e.g., Price as decimal, Rating as integer, Availability as text, etc.).

Clean the data in Power BI (e.g., handle nulls, remove duplicates, trim whitespace).

Charts and Visuals
Trend Chart: Show average price by rating (Bar/Column chart).
Pie Chart: Show proportion of books that are In Stock vs Out of Stock.
Table View: Display all books with conditional formatting on:
High price values (e.g., highlight books over £50 ~ $66).
Low ratings (e.g., 1-2 stars).

Filters and Slicers:
By Rating (1 to 5 stars).
By Stock Availability.
By Price Range.

Calculated Fields and Measures
Create a measure to calculate average book price by rating.
Create a calculated column to categorize books into:
All price values need to be converted to Us dollars
“Budget” (under £20 ~ $26.40)
“Standard” (£20–£50 ~ $26.40-$66)
“Premium” (above £50 ~ $66)

Dashboard
Design a cohesive dashboard with:
Title, filters/slicers, charts, KPIs.
KPI cards: Total Books, Average Price, % In Stock.
Option to drill down from category level (Budget, Standard, Premium) to individual book records.
Documentation and Explanation
Provide detailed documentation for Power BI report usage.
Add descriptive titles, tooltips, and labels in visuals.
Explain all DAX formulas and calculated columns used.

Testing
Test Cases:
Test Case 1: Validate successful import of CSV data into Power BI.
Test Case 2: Validate correct data type assignments.
Test Case 3: Validate filtering by rating and availability.
Test Case 4: Verify calculation accuracy for average price and category grouping.
Test Case 5: Confirm that all visuals update dynamically with slicers.
Test Case 6: Check for consistent data format and no visual errors.
