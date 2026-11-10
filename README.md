# Superstore Sales \& Profitability Analysis

An exploratory analysis of the Superstore dataset to understand where sales are coming from, what drives profit, and where the business may be losing money. The project looks at product performance, customer segments, regional trends, discounting and financial risk.

## 

## Tools \& data

* **Python:** Pandas, NumPy, Matplotlib and Seaborn
* **Dataset:** [Superstore Dataset (Kaggle)](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)
* **Scope:** 9,994 sales records, covering 2014–2017

The analysis is in `Superstore Dataset Analysis.ipynb`. The notebook downloads the dataset using `kagglehub`.

## 

## Key findings

* **Overall performance:** The business generated **$2.30m in sales** and **$286.4k in profit**, an overall margin of **12.47%**.
* **Sales don't always translate into profit:** Product revenue and profit have a moderate positive correlation (**0.59**). Some high-revenue products still make substantial losses.
* **Product profitability is uneven:** Copiers generated around **$55.6k in profit**, while Tables lost approximately **$17.7k** and Bookcases lost **$3.5k**.
* **Customer value is concentrated:** The top **20% of customers account for 48.15% of sales** and approximately **81.43% of net profit**.
* **Regional performance varies:** The **West** leads in sales and profit, with a margin of **14.94%**. The **Central** region has the lowest margin (**7.92%**) and highest average discount (**24.04%**).
* **Loss-making sales are material:** **20.40% of sales** comes from transaction lines with negative profit. Philadelphia and Houston stand out among the cities with the largest net losses.

## 

## Business recommendations

1. **Review unprofitable products**, especially Tables, Bookcases and high-revenue products that consistently lose money. Check pricing, costs and discount policies before deciding whether to change or discontinue them.
2. **Investigate discounting in the Central region.** Its relatively high average discount and low profit margin make it a sensible starting point for a more detailed review.
3. **Pay attention to valuable customers.** With profit concentrated among a relatively small group, retaining profitable customers matters. At the same time, review customers who generate strong sales but little profit.
4. **Prioritise the largest losses first.** Focus on financially significant loss-making cities and products rather than small transactions with unusually poor percentage margins.



