# Telecom Customer Churn Analysis

A Power BI report looking at why customers leave a telecom provider and how much revenue goes with them.

## Data

- `data/telecom_customer_churn.xlsx`: 7,043 customers
- Sheets: `Main_Data` (demographics, contract, tenure, payment method, churn status and reason), `Broadband`, `Mobile_Service`, `Telecom_TV`

## Dashboard pages

**Overview:** total, active and churned customers, churn rate, average tenure, monthly and total revenue, revenue lost to churn, top 10 cities, churn rate by contract and internet type.

**Churn Analysis:** churn by payment method, churn reasons, and churn by tenure.

## What I found

- Overall churn rate is **26.5%** (1,869 of 7,043 customers).
- Contract type is the biggest signal:

  | Contract | Churn rate |
  |---|---|
  | Month-to-Month | 45.8% |
  | One Year | 10.7% |
  | Two Year | 2.5% |

- The top churn category is **Competitor** (841 customers), well ahead of Dissatisfaction (321), Attitude (314) and Price (211). People mostly left for a better offer, not because of a bad experience.
- Churned customers had brought in about **$3.68M** in total revenue.

**Takeaway:** the cheapest retention win is moving month-to-month customers onto 1-year contracts, for example with a discount or a bundle that matches competitor offers.

## Tools

Power BI (DAX, data modelling), Excel

## How to open

Download `dashboard/telecom_churn_dashboard.pbix` and open it in Power BI Desktop (free).
