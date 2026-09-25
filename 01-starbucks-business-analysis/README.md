# Starbucks Business Analysis — Q3 FY2026

## 1. Overview

This case study analyzes Starbucks' business performance by understanding how the company generates sales and how key business metrics can be used to evaluate performance.

The analysis focuses on:

* Business model
* Revenue drivers
* Transactions
* Average ticket
* Comparable-store sales
* Customer segments
* Business questions and hypotheses
* Data required for deeper analysis

The objective is not only to understand the numbers but also to think about **why the numbers changed and what a business analyst would investigate next.**

---

## 2. What Does Starbucks Sell?

Starbucks primarily sells:

* Coffee and beverages
* Food and bakery products
* Branded merchandise
* Other retail products

The company operates through a global network of coffeehouses and also generates revenue through other channels such as licensed stores and consumer products.

---

## 3. Who Are Starbucks' Customers?

Some possible customer segments that could be analyzed include:

* Daily commuters
* College students
* Remote workers
* Brand-loyal customers
* Families and groups

These are **analytical customer segments**, not necessarily Starbucks' official customer classifications.

Different customer segments may have different purchasing patterns, visit frequencies, preferred products, and average spending.

---

## 4. How Does Starbucks Make Money?

Major revenue sources include:

### Company-operated stores

Customers purchase beverages, food and other products directly from Starbucks-operated stores.

### Licensed stores

Starbucks also receives revenue from licensed locations.

### Consumer products

Starbucks generates revenue through products sold outside its coffeehouses, including packaged products and other retail channels.

---

# 5. Important Business Metrics

## Revenue

Revenue is the total amount of money generated from selling products and services before deducting expenses.

## Transactions

Transactions represent the number of customer orders or purchases.

Higher transactions generally indicate that more purchases are taking place.

## Average Ticket

Average ticket represents the average amount spent per transaction.

A simple way to think about it is:

**Average Ticket = Total Sales ÷ Number of Transactions**

## Comparable-Store Sales

Comparable-store sales help measure sales performance of comparable existing stores rather than simply measuring growth from opening new stores.

This helps analysts understand whether existing stores are performing better or worse.

---

# 6. Starbucks North America Performance

The North America results analyzed were:

| Metric                 | Result |
| ---------------------- | -----: |
| Comparable-store sales |  +8.1% |
| Transactions           |  +4.5% |
| Average ticket         |  +3.5% |
| Net revenue            |  $7.4B |
| Net revenue growth     |    +7% |

### What does this tell us?

The combination of higher transactions and a higher average ticket suggests that Starbucks' existing North American stores generated stronger comparable sales.

In simple words:

**More purchases were happening, and customers were also spending more per purchase.**

This means the sales growth was being supported by **both transaction growth and higher spending per transaction.**

---

# 7. Why Track Transactions and Average Ticket Separately?

Starbucks should track these metrics separately because they answer two different questions.

### Transactions

**How many purchases are customers making?**

This helps Starbucks understand customer traffic and demand.

### Average Ticket

**How much is being spent in each purchase?**

This helps Starbucks understand spending per transaction and changes in product mix, pricing, or add-on purchases.

Looking at both metrics helps explain **how sales are changing**, rather than only looking at total revenue.

For example:

* Transactions ↑ + Average Ticket ↑ → sales can increase through both drivers.
* Transactions ↑ + Average Ticket ↓ → more customers, but lower spending per purchase.
* Transactions ↓ + Average Ticket ↑ → fewer purchases, but higher spending per purchase.

---

# 8. Business Thinking Scenario

### Scenario

Suppose:

* Transactions increase by 8%
* Average ticket decreases by 5%

The increase in transactions looks positive, but the decrease in average ticket raises an important business question:

**Why are more customers purchasing, but spending less per transaction?**

As a business analyst, I would investigate:

### 1. Promotions and discounts

Did Starbucks introduce discounts or promotional offers?

Promotions could increase the number of transactions while reducing the average amount spent per order.

### 2. Product mix

Are customers moving from expensive products toward cheaper products?

For example, customers may be purchasing basic beverages instead of premium beverages or food combinations.

### 3. Food and add-on purchases

Are customers buying fewer food items or add-ons with their beverages?

This could reduce the average ticket.

### 4. Customer mix

Did the increase in transactions come from a different customer segment with lower average spending?

### 5. Store or ordering experience

Did longer waiting times, operational issues, or ordering problems affect what customers purchased?

These questions would need to be tested using actual data rather than assumptions.

---

# 9. Is 10% Revenue Growth Automatically Good?

**No.**

Revenue growth is an important metric, but it does not tell the complete story.

A business analyst should also investigate:

### Profit and costs

If revenue increases by 10% but operating costs increase even more, profitability could decline.

### Source of growth

Did growth come from:

* Existing stores?
* New stores?
* Higher transactions?
* Higher average spending?
* Other revenue sources?

### Market performance

How did the company perform compared with the overall market and competitors?

Therefore:

**Revenue growth tells us that sales increased, but we need additional metrics to understand the quality and sustainability of that growth.**

---

# 10. Testing a Business Hypothesis

### Hypothesis

"More delivery sales may increase average ticket."

To test this hypothesis, I would need transaction-level data.

### Useful columns

* Transaction ID
* Order channel
* Total amount spent
* Number of items
* Date
* Store
* Product/category
* Customer segment, if available

### Analysis approach

First, separate orders by channel:

* Delivery
* In-store
* Drive-through
* Mobile/app

Then calculate:

**Average Ticket = Total Sales ÷ Number of Transactions**

for each channel.

For example:

| Channel  | Average Ticket |
| -------- | -------------: |
| Delivery |            $15 |
| In-store |             $8 |

If delivery orders consistently have a higher average ticket, this would support the hypothesis.

However, this alone would not prove that **delivery caused** the higher ticket. Other factors such as order size, customer type, product mix, or promotions would also need to be considered.

---

# 11. Customer Segmentation Analysis

Three possible customer segments I would analyze are:

## College Students

Possible metrics:

* Discount usage rate
* Afternoon transaction volume
* Average food items per order
* Visit frequency
* Average ticket

### Business question:

Are students mainly visiting for affordable beverages, or are they also purchasing food and other products?

---

## Daily Commuters

Possible metrics:

* Morning transaction volume
* Drive-through vs. mobile/app usage
* Visit frequency
* Average ticket
* Order/pickup time

### Business question:

How important are speed and convenience to commuter customers?

---

## Weekend Families

Possible metrics:

* Average ticket
* Items per transaction
* Non-coffee product sales
* Cold beverage sales
* Weekend transaction volume

### Business question:

Do family/group visits generate larger transactions and different product mixes?

---

# 12. Key Business Insights

Based on the analysis, the main observations are:

### Insight 1 — Sales growth has multiple drivers

North America comparable-store sales increased 8.1%, while transactions increased 4.5% and average ticket increased 3.5%.

This indicates that sales growth was supported by both **more transactions and higher spending per transaction.**

### Insight 2 — One metric is not enough

Looking only at revenue or comparable sales does not explain what is driving the change.

Breaking sales into transactions and average ticket provides more useful business information.

### Insight 3 — Business analysts should investigate causes

A change in a KPI is only the starting point.

The next step is to ask:

**Why did it change?**

### Insight 4 — Data is needed to test assumptions

Statements such as "delivery customers spend more" or "students spend less" should not automatically be treated as facts.

They should be tested using transaction-level data.

---

# 13. Business Analyst Framework Used

For this analysis, I followed:

**Business Problem**

↓

**Understand the Business**

↓

**Identify Important Metrics**

↓

**Observe Changes**

↓

**Ask Why**

↓

**Create Hypotheses**

↓

**Identify Required Data**

↓

**Analyze**

↓

**Generate Business Insights**

↓

**Recommend Action**

This framework can be applied to sales, marketing, customer retention, operations, HR and other business problems.

---

# 14. What I Learned

Through this analysis, I learned that business analysis is not just about calculating numbers.

A business analyst needs to understand:

* What the business sells
* How the business makes money
* Which metrics matter
* What changed
* Why it might have changed
* What data is required to investigate it
* How the findings could support business decisions

The biggest learning from this case was:

> **Don't stop at "What happened?" Ask "Why did it happen?" and "What data would prove it?"**

---

## Source

Starbucks Q3 FY2026 financial results and business information were used as the basis for this case study.

## Note

Some customer segments, hypotheses and investigation questions in this case study are my own analytical ideas and are not presented as official Starbucks classifications or explanations.
