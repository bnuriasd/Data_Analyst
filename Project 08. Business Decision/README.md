# Business Decision-Making Based on Data
## Project Description
You are a data analyst at a major online store. Along with the marketing team, you have compiled a list of hypotheses to help boost revenue. Now, your task is to prioritize these hypotheses, conduct A/B testing, and analyze the results.

## Data Description
**Data used in the first part of the project:**

`/datasets/hypotheses_us.csv (Download dataset)`

- Hypotheses — a brief description of the hypotheses
- Reach — user reach, on a scale from one to ten
- Impact — impact on users, on a scale from one to ten
- Confidence — confidence in the hypothesis, on a scale from one to ten
- Effort — resources required to test the hypothesis, on a scale from one to ten. The higher the Effort value, the more resource-intensive the testing.
  
**Data used in the second part of the project:**

`/datasets/orders_us.csv (Download dataset)`

- transactionId — order ID
- visitorId — user ID who placed the order
- date — order creation date
- revenue — order revenue
- group — A/B test group where users belong

`/datasets/visits_us.csv (Download dataset)`

- date — date
- group — A/B test group
- visitors — the number of visitors on the specified date in the designated A/B test group
- visits — the number of visits on the specified date for the designated A/B test group
  
We are going to preprocess the data first. It's possible that the original dataset you have might contain errors, for example, some visitors might be in both group A and group B.
