# Dynamic Financial Model – Excel

## Project Overview
This Excel-based financial model provides a dynamic, scenario-driven analysis of a business’s financial performance from 2023 to 2027. It incorporates revenue, cost of goods sold (COGS), operating expenses, and tax implications, allowing users to evaluate both upper and lower case scenarios for strategic planning and decision-making.  

---

## Key Features

1. **Income Statement Projection**  
   - Forecasts revenue, COGS, gross profit, operating expenses, operating profit, taxes, and net profit for a five-year period.  
   - Calculates key financial ratios such as Gross Profit Margin and Operating Profit Margin.  

2. **Live Case Inputs**  
   - **Revenue Drivers:**  
     - Number of orders per year  
     - Order growth rate  
     - Average order value  
   - **Cost Drivers:**  
     - Manufacturing cost per order  
     - Order fulfillment cost per order  
   - **Operating Expenses:**  
     - Warehouse rent  
     - Salaries & payroll  
     - Marketing  
     - Other expenses  
   - **Tax Rates:** Corporate tax rates applied annually.  

3. **Scenario Analysis**  
   - **Upper Case (Scenario 1):** Optimistic projections with higher orders and revenue per order.  
   - **Lower Case (Scenario 2):** Conservative projections with lower orders, revenue, and higher per-order manufacturing costs.  

4. **Dynamic Calculations**  
   - Automatically updates financial statements when live case inputs or scenario assumptions are changed.  
   - Supports detailed year-over-year growth analysis and profitability forecasting.

---

## Model Structure

| Sheet | Description |
|-------|-------------|
| **Income Statement** | Calculates revenue, COGS, gross profit, operating expenses, operating profit, taxes, and net profit for all years. |
| **Live Case Inputs** | Contains all user-input assumptions for order volume, growth rates, average order value, and costs. |
| **Scenario 1 – Upper Case** | Optimistic scenario for strategic planning and revenue potential analysis. |
| **Scenario 2 – Lower Case** | Conservative scenario for risk management and cost planning. |

---

## Model Flow Diagram


Live Case Inputs
├─ Number of Orders
├─ Average Order Value
├─ Manufacturing Cost per Order
├─ Order Fulfillment Cost per Order
├─ Operating Expenses (Rent, Payroll, Marketing, Other)
└─ Tax Rate
│
▼
Revenue = Orders × Avg Order Value
│
▼
COGS = (Manufacturing + Fulfillment) × Orders
│
▼
Gross Profit = Revenue − COGS
│
▼
Operating Profit = Gross Profit − Operating Expenses
│
▼
Taxes = Operating Profit × Tax Rate
│
▼
Net Profit = Operating Profit − Taxes

---

## Assumptions & Notes

- All amounts are in USD.  
- Revenue is calculated as:  

Revenue = Number of Orders × Average Order Value

- COGS is calculated per order and summed across all orders.  
- Operating profit is calculated before tax:  

Operating Profit = Gross Profit − Total Operating Expenses

- Taxes are applied according to the corporate tax rate for each year.  
- Gross profit and operating profit margins are expressed as percentages of revenue.  

---

## Potential Applications

- Strategic financial planning and forecasting  
- Scenario analysis for risk management  
- Decision-making support for investment and budgeting  
- Sensitivity analysis on key revenue and cost drivers
- 

> **Note:** This model was created following guidance from [KenjiExplains](https://www.youtube.com/@kenjiexplains) on YouTube.
