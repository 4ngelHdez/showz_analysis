# LTV, CAC, and ROMI Analysis

### Project Description

In this project, I worked on analytics tasks for Showz, a company specializing in event ticket sales.<br>
The main goal was to optimize marketing spend by analyzing company data from January 2017 to December 2018, which included both order records and marketing expense statistics.<br>

### Objectives:

The project focused on answering key questions:

   * How do customers use the service?
   * When do customers begin making purchases?
   * How much revenue does each customer contribute over time?
   * At what point do generated revenues cover the cost of customer acquisition?

### Methodology:

I used Python as the primary tool for data processing, analysis, and visualization. The workflow included:

   - Exploratory data analysis: cleaning missing values, identifying duplicates, and transforming data for easier analysis.
   - User retention calculations to understand how many customers remain active over time.
   - LTV (Customer Lifetime Value) calculations to estimate revenue per customer across their lifecycle.
   - CAC (Customer Acquisition Cost) calculations to measure the average cost of acquiring a new customer.
   - ROMI (Return on Marketing Investment) calculations to evaluate the financial return of marketing campaigns.

### Key Findings:

   * Average initial cohort revenue was around `$`5 USD, with only two cohorts increasing by more than 100%, while the rest remained below that level.

   * Marketing company 3 brought in the highest number of customers (an average of 5 customers per payment), followed by companies 4 and 5 with an average of 2 customers per payment. Notably, 5 of the campaigns brought in no customers at all.

   * Company 3 was also the most expensive, charging `$`3.90 per customer, followed by campaigns 4 and 5 with CACs of `$`1.67 and `$`1.41 per customer, respectively.

   * Marketing campaigns overall failed to recover their investment, with lower-cost campaigns showing a better ROMI due to reduced spend. Specifically, campaign 3, despite being the costliest and generating the most customers, produced only a 33.64% return, far below expectations. It was estimated that this campaign would need to acquire at least 15 customers per payment to break even.

These findings highlight the need for a comprehensive review of the marketing team’s strategies and channel performance to improve retention and profitability.

### Tools & Technologies:

   * Python (pandas, matplotlib, numpy, seaborn, matplotlib).
   * Jupyter Notebook for workflow documentation.
