# Profitability-EDA-for-an-E-Commerce-Business

## 📌 Objective

To identify key drivers of margin erosion and profitability through exploratory data analysis of order, customer, and product data to inform strategic business decisions.


## 💡 Business Context

The business has experienced rapid expansion over the past two years, driven by aggressive promotional activity and product range diversification. Whilst revenue continues to grow, leadership has identified emerging profitability challenges at the product level. Existing reporting infrastructure focuses predominantly on order-level metrics, limiting visibility into the granular drivers of margin erosion—specifically pricing dynamics, promotional effectiveness, and product returns.


## ✅ Executive Summary

Undifferentiated discounting and suboptimal range development are the primary drivers of margin erosion. Discount optimisation and category rebalancing are crucial next steps to improving profit margins.

**1. Implement targeted discounting startegy -** 38% of products show low discount sensitivity yet experience blanket discounting, resulting in over £550,000 in revenue loss. Removing discounts on these items would generate an estimated £127,593 in incremental profit, 13.5% margin uplift. An additional [X] products (6% of range) are discount-dependent with high return rates and require urgent review.

**2. Invest in Sports and Beauty, rationalise Electronics, Home, Health & Office -** Sports (11.6% of revenue, 12.9% of profit,[X%] average margin) and Beauty ([X%] of revenue, [X%] of profit, 48.2% average margin) demonstrate superior unit economics with lower returns and lower discount dependancy. Electronics, Home, Health, and Office consistently erode margin with lower average margins, higher discount sensitivity and higher return rates. Strategic consolidation should target products with margins below 20%, with urgent review for products below 15% margin and an above 10% return rate. Sports should be invested in as a the core offering with addtional investment in beauty as it has the potential to become a profit driving category.


## ⚙️ Tools Used

* **SQL**: CTE's, Joins, Case, Window functions, Aggregate functions
* **Tableau**: Table Calculations, Dashboard Creation, LOD's, Filters
    

## 📊 Results & Recommendations


**1. Shift blanket discounting startegy to focus on products which maintain margin and continue to shift volume when discounted.**

* The average product has been sold at a 16.6% discount in the last year, with 24% of orders containing at least one loss leading item.

* While discounts are contributing to volume and profit, the blanket approach is unecessarily eroding margin across several SKU's causing a loss of over £550,000 in revenue over the last year.

* 38% of the range have no or low sensitivty to discounts. Assuming these discounts were removed and 90% of volume retained, there will be an expected additional profit of £127,593, improving margin by 13.5% .

* 6% of the range is discount dependant, in addition to being assosiated with higher return rates and margin erosion and should be reviewed immediatley.
  

**2. Focus on Sports and Beauty as core range, rationalise and minimise remaining categories.**
* Sports & Beauty outperform on all profit levers with high margins, low return rates, and a lower reliance on discounting to drive sales.

* Sports is already a material revenue and profit driver, contributing 11.6% of total revenue and 12.9% of total profit margin in the last year.

* Beauty is structurally attractive but underinvested in, seeing an average gross margin of 48.2%. To test the potential of the category we should increase marketing and monitor the sales of a selection of high margin, low discount, low returns products. Hair Repair Shampoo Plus, Hydrating Face Cream and Cleansing Gel XL suggested for their high margins, moderate sales and low return rates - minimising operational burden.

* Electronics, Home, Health and Office are the least healthy categories, consistently eroding margin in addition to high discount sensitivity and elevated returns. Other categories observed moderate performance. Any products with <20% margin should be reviewed in the consolidation process with any products observing a <15% margin with >10% returns rate being flagges for urgentt review.

  
**3. No clear driver of returns, have lower net impact on margin than discounts. Focus on range consolidation and discount stategy to improve margins.**

 * Return rate stable YoY at 6.8% in the last year, no notable seasonality trend or significant spikes.

 * Expected trends including higher priced items and first time buyers seeing higher returns are obsereved.
 
 * There may be potential issues with the marketplace platform fit and US operations with both seeing higher return rates - further infomation should be collected on returns so we can paint a clearer picture of the issue.


## 🚀 Next Steps

**1. Develop Optimised Discounting Strategy -** Using product-level discount sensitivity and margin thresholds to set strategy - start with low disocunt sensitivty and loss leading products, measure and monitor effects.

**2. Increase marketing investment for Beauty -**  Hair Repair Shampoo Plus, Hydrating Face Cream and Cleansing Gel XL reccomended as trial products for their high margins, moderate volumes and low return rates.

**3. Rationalise remanining categories to more profitable products -** >20% margin, return rates >10% suggested to minimse loss from operational costs.


## 📈 Tableau Dashboard
