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

  2. Products to Stop Selling:

     - Identify products that consistently lead to losses, and visualize which products the store should consider discontinuing.

  3. Focus & Stop Selling Subcategories:

     - Determine which 3 product subcategories the store should prioritize and which 3 it should stop selling, based on their profit performance.

Example Visualizations:
  - Heat maps to highlight profit vs loss categories.
![Part 1 1 P L](https://github.com/user-attachments/assets/5cceb2f1-ff72-48f8-813b-f67271581082)

  - Bar charts showing product performance by shipping mode.
![Part 1 2 P L](https://github.com/user-attachments/assets/b19e1567-f708-47a4-9810-019d9e8dbd38)


# Part 2: Advertising Strategy

Here, the goal is to determine the best time and place to invest in advertising. Advertising should be targeted at states and months where the average profit per unit sold is high enough to justify the ad spend.

Questions Answered:

  1. Best States and Months for Advertising:

     - Identify the 3 best combinations of states and months to advertise in, visualizing average profits for each month in these states.

  2. Justify Advertising Costs:

     - Use the Return on Ad Spend (ROAS) ratio to argue how much the store should be willing to spend on advertising for the selected states and months. The rule of thumb for this project is that the store should be willing to spend 1/5 of its profits on advertising.

Example Visualizations:

  - Line charts showing monthly profit trends in top-performing states.
![Part 2 1_](https://github.com/user-attachments/assets/5d4a2ac8-f37b-427d-8619-9eb5f03cb84c)

  - ROAS visualizations to help justify advertising costs.
![Part 2 1 (1)](https://github.com/user-attachments/assets/4d2e31ed-966a-4ed7-b315-859890df362a)

  - Bar Chart showing top sub categories based on Average Return Rate. 
![Part 2 2](https://github.com/user-attachments/assets/f9303dcd-c87b-4239-bffd-69a51758c722)

  - Bar Chart showing return rate through customers based on average return rate.
![Part 2 2 1](https://github.com/user-attachments/assets/78cec7fb-6147-4960-a6c4-809356427a02)


# Part 3: Returned Items

This section focuses on analyzing product return rates and determining whether certain products or customer groups have abnormally high return rates, impacting profitability.

Questions Answered:

  1. Products with Highest Return Rate:

     - Visualize which products have the highest return rates by creating a calculated field to categorize returned items.

  2. Customers with Highest Return Rate:

     - Identify which customers have the highest return rates and examine if these customers are consistently returning high-value items.

  3. Impact of Returns on Profitability:

     - Create a visualization that plots average profit against the average return rate for a specific dimension (e.g., state, shipping mode, product type). Use this visualization to argue whether the superstore should continue or stop doing business in that dimension.

Example Visualizations:

  - Visualization of the average profit against the average return rate on states. 
![Part3 3](https://github.com/user-attachments/assets/bf521d1e-d1f5-4279-878c-f88699259af7)

Tableau Public Link: (https://public.tableau.com/views/ProjectSprint4_/Part1_2PL?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)






# Key Skills Demonstrated

  1. Data Preparation: Combining multiple data sources using LEFT JOIN and creating calculated fields in Tableau.
  2. Data Visualization: Creating insightful visualizations like bar charts, heat maps, and scatter plots to support decision-making.
  3. Profit Analysis: Identifying major profit and loss centers using visual data exploration.
  4. Advertising Strategy: Using ROI calculations to recommend targeted advertising strategies.
  5. Return Rate Analysis: Investigating return rates and their impact on profitability.
