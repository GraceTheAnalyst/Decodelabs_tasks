# Decodelabs_tasks

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Findings](#findings)
- [Recommendations](#recommendations)
- [Limitations](#limitations)
- [About Me](aboutme)


## Project Overview

This data explores 1,200 online orders (January 2023 to June 2025) to find patterns, trends and unusual orders. The work covers basic statistics, how orders are spread across categories, outliers, and how sales change over time.

## Data Sources
The dataset was provided by DecodeLab Internship program

## Tools
 Microsoft Excel

## Exploratory Data Analysis

- **Statistics and counts:** 
- **Outliers:** I used a standard rule. An order is an outlier if its total is more than 1.5 times the spread of the middle half of orders above the 75th percentile (or below the 25th). I then checked each flagged order to see whether it was an error.
- **Trends:** I compared January to June of each year, because the data stops in June 2025 and a full-year comparison would not be fair. For monthly patterns I divided each month's total by the number of years it appears in.
- **Charts:** Every chart axis starts at zero so differences are not exaggerated.

## Findings

1. **Sales are falling.** Comparing January to June each year, revenue went from $287K (2023) to $257K (2024) to $232K (2025). That is about 10% lower each year. Both fewer orders and smaller orders caused it. The average order fell from $1,137 to $1,004.
2. **Most orders do not reach the customer.** Only 19% of orders were delivered. 41% were cancelled or returned. Another 20% are still pending.
3. **A few large orders pull the average up.** The average order is $1,054 but the middle order is $824. Most orders are under $1,000 and only 34 are above $3,000.
4. **Only 8 orders are outliers.** They are above $3,330 and together they make up 2.1% of revenue.
5. **June is the busiest month and September the slowest.** Each month has only two or three years of data, so this is a lead, not a firm rule.
6. **Products, payment methods, coupons and referral sources look alike.** Orders are spread almost evenly across all of them and average order size differs by less than 15% between groups.

<img width="740" height="421" alt="Screenshot (229)" src="https://github.com/user-attachments/assets/2b2c2d6b-8dc8-4238-a7ea-068371f488bf" />



## Recommendations

- Find out why so many orders are cancelled or returned.
- Understand why the average order is getting smaller.

## Limitations

The data looks artificial. Prices do not match products, every address is on "Main St" and almost no customer orders twice. The results describe this dataset, not real shopper behaviour.

## About Me

I am Yetunde Grace Ajayi, a data analyst building my portfolio. I work with SQL, Power BI, Excel and Python.
 - LinkedIn: [linkedin.com/in/yetundegraceajayi](https://linkedin.com/in/yetundegraceajayi)
 - GitHub: [github.com/GraceTheAnalyst](https://github.com/GraceTheAnalyst)
