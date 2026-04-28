# Profitability-EDA-for-an-E-Commerce-Business

## 📌 Objective

To identify key drivers of margin erosion and profitability through exploratory data analysis of order, customer, and product data to inform strategic business decisions.

<br>

## 💡 Business Context

The business has experienced rapid expansion over the past two years, driven by aggressive promotional activity and product range diversification. Whilst revenue continues to grow, leadership has identified emerging profitability challenges at the product level. Existing reporting infrastructure focuses predominantly on order-level metrics, limiting visibility into the granular drivers of margin erosion—specifically pricing dynamics, promotional effectiveness, and product returns.

<br>

## ✅ Executive Summary

Undifferentiated discounting and sub-optimal range development are the primary drivers of margin erosion. Discount optimisation and category rebalancing are crucial next steps to improving profit margins.

<br>

**1. Remove blanket discounting -** 
* In the last year the average product was sold at a 16.6% discount, with 24% of orders containing at least one loss making item.
* 38% of products show low discount sensitivity yet are being blanket discounted - resulting in over £550,000 in revenue loss. Removing these discounts will generate an estimated £127,600 in profit, a 13.5% margin uplift.
* 15 items (6% of range) are highly discount senstitive with >70% of volume being sold at a discount, 7 of which have a margin of <20% - these items should be reviewed immediately.

<br>

**2. Invest in Sports and Beauty, rationalise Electronics, Home, Health & Office -** 
* Sports (11.6% of revenue, 12.9% of profit, 31.1% average margin) and Beauty (7.8% of revenue, 8.2% of profit, 29.7% average margin) demonstrate superior unit economics with higher margins, lower returns and lower discount dependancy.
* Electronics, Home, Health, and Office consistently erode margin with lower average margins, higher discount sensitivity and higher return rates.
* Strategic consolidation should target products with margins below 20% and a return rate above 10% in addition to the 15 highly discounted items.
* Sports should be invested in as the core offering whilst increasing investment in beauty as it has the potential to become a profit driving category.

<br>

## ⚙️ Tools Used

* **SQL**: CTE's, Joins, Case, Window functions, Aggregate functions
* **Tableau**: Table Calculations, Dashboard Creation, LOD's, Filters
    
<br>

## 📊 Results & Recommendations

<br>

**1. Shift blanket discounting startegy to focus on products which maintain margin and continue to shift volume when discounted.**

* In the last year the average product was sold at a 16.6% discount, with 24% of orders containing at least one loss making item.

* While discounts are contributing to volume and profit, the blanket approach is unecessarily eroding margin across several SKU's causing a loss of over £550,000 in revenue over the last year.

* 38% of the range have no or low sensitivty to discounts. Assuming these discounts were removed and 90% of volume retained, there will be an expected additional profit of £127,593, improving margin by 13.5% .

* 6% of the range is discount dependant, in addition to being assosiated with higher return rates and margin erosion and should be reviewed immediatley.
  
<br>

**2. Focus on Sports and Beauty as core range, rationalise and minimise remaining categories.**
* Sports & Beauty outperform on all profit levers with high margins, low return rates, and a lower reliance on discounting to drive sales.

* Sports is already a material revenue and profit driver, contributing 11.6% of total revenue and 12.9% of total profit margin in the last year.

* Beauty is structurally attractive but underinvested in, seeing an average gross margin of 48.2%. To test the potential of the category we should increase marketing and monitor the sales of a selection of high margin, low discount, low returns products. Hair Repair Shampoo Plus, Hydrating Face Cream and Cleansing Gel XL suggested for their high margins, moderate sales and low return rates - minimising operational burden.

* Electronics, Home, Health and Office are the least healthy categories, consistently eroding margin in addition to high discount sensitivity and elevated returns. Other categories observed moderate performance. Any products with <20% margin, >=10% return rates and high discount sensitivty should be reviewed.

<img width="906" height="610" alt="Image" src="https://github.com/user-attachments/assets/ea716023-cd9c-400d-8ade-082c8ca7d3de" />

**Graph :** Shows Margin vs Discount Sensitivity. Sports and Beauty being high margin, low discount sensitivity. Electronics, Home, Health, and Office being low margin, high discount sensitivity.

<br>

**3. No clear driver of returns, have lower net impact on margin than discounts. Focus on range consolidation and discount stategy to improve margins.**

 * Return rate stable YoY at 6.8% in the last year, no notable seasonality trend or significant spikes.

 * Expected trends including higher priced items and first time buyers seeing higher returns are obsereved.
 
 * There may be potential issues with the marketplace platform fit and US operations with both seeing higher return rates - further information should be collected on returns so we can paint a clearer picture of the issue.

<br>

## 🚀 Next Steps

**1. Develop Optimised Discounting Strategy -** Using product-level discount sensitivity and margin thresholds to set strategy - as an inital step, remove discounts from low-discount sensitivty products - measure and monitor effects.

**2. Increase marketing investment for Beauty -**  Hair Repair Shampoo Plus, Hydrating Face Cream and Cleansing Gel XL reccomended as trial products for their high margins, moderate volumes and low return rates. Shift proportion of marketing budget from Electronics, Home, Health, and Office.

**3. Rationalise remanining categories to more profitable products -** <20% margin and return rates >=10% suggested to minimse loss from operational costs and those with >70% voulme sold at discount to minimse margin erosion from discounting.

<br>

## 📈 Tableau Dashboard
