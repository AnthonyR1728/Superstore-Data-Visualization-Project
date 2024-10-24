## Superstore-Data-Visualization-Project


# Project Overview
  Welcome to the Superstore Data Visualization project! As a consultant, your task is to analyze Superstore's operations to identify areas of profit and loss, recommend advertising strategies, and assess return rates to increase profitability and avoid bankruptcy. The analysis will be visualized using Tableau, allowing for clear and actionable insights based on the available data.

  This project will be divided into three parts:

  1. Profit & Loss Analysis: Identifying the major centers of profit and loss across different product categories and regions.
  2. Advertising Strategy: Recommending the best states and months for targeted advertising.
  3. Returned Items Analysis: Evaluating return rates and their impact on profitability.

The data used for this project is from the Superstore.xls file provided by Tripleten.

# Dataset

The dataset contains multiple sheets, including:

  1. Orders: Contains detailed order information including products, sales, profits, and more.
  2. Returns: Information on returned items.
  3. People: Contains details on the employees managing different regions.

  These data sources are joined together in Tableau to conduct the analysis.

## Project Breakdown
   
   # Part 1: Profits & Losses

   In this section, the goal is to identify the key areas where the superstore is making the most profits and where it is incurring the most losses. This involves analyzing combinations of dimensions like product subcategories, shipping modes, and regions.

Questions Answered:
  
  1. Biggest Profit Centers and Loss-Makers:

    - Visualize the two largest profit centers and two largest loss-makers by analyzing combinations of dimensions (e.g., subcategory + region or shipping mode + product ID).
Products to Stop Selling:
Identify products that consistently lead to losses, and visualize which products the store should consider discontinuing.
Focus & Stop Selling Subcategories:
Determine which 3 product subcategories the store should prioritize and which 3 it should stop selling, based on their profit performance.
Example Visualizations:
Heat maps to highlight profit vs loss categories.
Bar charts showing product performance by region.
Part 2: Advertising Strategy
Here, the goal is to determine the best time and place to invest in advertising. Advertising should be targeted at states and months where the average profit per unit sold is high enough to justify the ad spend.

Questions Answered:
Best States and Months for Advertising:
Identify the 3 best combinations of states and months to advertise in, visualizing average profits for each month in these states.
Justify Advertising Costs:
Use the Return on Ad Spend (ROAS) ratio to argue how much the store should be willing to spend on advertising for the selected states and months. The rule of thumb for this project is that the store should be willing to spend 1/5 of its profits on advertising.
Example Visualizations:
Line charts showing monthly profit trends in top-performing states.
ROAS visualizations to help justify advertising costs.
Part 3: Returned Items
This section focuses on analyzing product return rates and determining whether certain products or customer groups have abnormally high return rates, impacting profitability.

Questions Answered:
Products with Highest Return Rate:
Visualize which products have the highest return rates by creating a calculated field to categorize returned items.
Customers with Highest Return Rate:
Identify which customers have the highest return rates and examine if these customers are consistently returning high-value items.
Impact of Returns on Profitability:
Create a visualization that plots average profit against the average return rate for a specific dimension (e.g., state, shipping mode, product type). Use this visualization to argue whether the superstore should continue or stop doing business in that dimension.
Example Visualizations:
Bar charts for product return rates.
Scatter plots showing profit vs return rate by state or product type.
Part 4: Submission Instructions
To submit your project, ensure the following:

Tableau Public Link:

Publish your Tableau dashboard on Tableau Public.
Include a link to your published dashboard here.
Superstore Tableau Dashboard

Project Files:

Submit a ZIP archive containing all your project files.
Ensure all files are under 9 MB in size.
How to Use the Repository
Clone the Repository: Clone this repository to your local machine.

bash
Copy code
git clone https://github.com/yourusername/superstore-tableau-analysis.git
Tableau Workbook: Open the Tableau workbook file in Tableau Desktop to explore the visualizations or access the published version on Tableau Public.

Analysis: Use the visualizations to explore different aspects of the Superstore's operations and answer the key questions posed in the project.

Key Skills Demonstrated
Data Preparation: Combining multiple data sources using LEFT JOIN and creating calculated fields in Tableau.
Data Visualization: Creating insightful visualizations like bar charts, heat maps, and scatter plots to support decision-making.
Profit Analysis: Identifying major profit and loss centers using visual data exploration.
Advertising Strategy: Using ROI calculations to recommend targeted advertising strategies.
Return Rate Analysis: Investigating return rates and their impact on profitability.
Next Steps
Further Analysis: Explore additional dimensions and metrics (e.g., shipping delays, customer segments) for deeper insights.
Optimization Strategies: Based on your findings, recommend further strategies to improve profitability and reduce return rates.
