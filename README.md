# Profitability & Discounting Strategy

## 📌 Objective

To provide actionable commercial recommendations to a leadership team facing margin erosion using order, product and customer data to diagnose the root causes and prioritise the highest-ROI interventions.

<br>

## 💡 Business Context

The business has experienced rapid expansion over the past two years, driven by aggressive promotional activity and product range diversification. Whilst revenue continues to grow, leadership has identified emerging profitability challenges at the product level. Existing reporting infrastructure focuses predominantly on order-level metrics, limiting visibility into the granular drivers of margin erosion, specifically pricing dynamics, promotional effectiveness, and product returns.

<br>

## ✅ Executive Summary

**Undifferentiated discounting and sub-optimal category investment are the primary drivers of margin erosion.**

 1. Despite strong top-line growth, 24% of orders contained at least one loss-making item, and over £550,000 in revenue was unnecessarily lost to discounts on products that don't         need them to sell.
    
<br>

**Two interventions would drive the biggest impact in recovering this loss whilst minimising impact on quantities.**

 1. Shifting from blanket to targeted discounting through removing discounts from the 38% of products with low price sensitivity — this would generate an estimated £127,600 in            additional profit and a 13.5% margin uplift with no change to volume. 
2. Rebalancing category investment toward Sports and Beauty, which deliver superior unit economics (31.1% and 29.7% average margins respectively, with low return rates and low           discount dependency), while rationalising Electronics, Home, Health and Office, which consistently erode margin across all three levers.

<br>

**Returns are a secondary concern being stable at 6.8% year-on-year with no seasonal pattern and should not be the priority.**

<br>

## ⚙️ Tools & Analytical Skills Used

* **SQL**: CTE's,joins, case function, window functions, aggregate functions
* **Tableau**: Table calculations, dashboard creation, LOD's, filters
* **Analytical Skills**: Discount sensitivity analysis, margin modelling, customer behaviour analysis, product/category segmentation,market basket analysis
    
<br>

## 📊 Results & Recommendations

<br>

**1. Shift blanket discounting srategy to focus on products which maintain margin and continue to shift volume when discounted.**

* In the last year the average product was sold at a 16.6% discount, with 24% of orders containing at least one loss making item.

* While discounts are contributing to volume and revenue, the blanket approach is unnecessarily eroding margin across several SKUs causing a loss of over £550,000 in revenue over the last year for low-sensitivity products (38% of range) - removing these discounts will add an additional profit of £127,600, improving margin by 13.5% .

* 6% of the range (15 items) is discount dependent and should be reviewed immediately.
  
<br>

<img width="1896" height="1034" alt="Image" src="https://github.com/user-attachments/assets/63b2d565-5b94-4ae5-b2aa-5c47d64c54aa" />

**Graph:** Shows margin erosion due to returns and heavy discounting. Shows across categories approx 60% margin retained, 35% lost to discounting and 5% to returns.

<br>

**2. Focus on Sports and Beauty as core range, rationalise and minimise underperforming categories.**
* Sports & Beauty outperform on all profit levers with high margins, low return rates, and a lower reliance on discounting to drive sales.

* Sports is already a material revenue and profit driver, contributing 11.6% of total revenue and 12.9% of total profit margin in the last year.

* Beauty is structurally attractive but underinvested in, seeing an average gross margin of 48.2%. To test the potential of the category we should increase marketing and monitor the sales of a selection of high margin, low discount, low returns products. Hair Repair Shampoo Plus, Hydrating Face Cream and Cleansing Gel XL suggested for their high margins, moderate sales and low return rates - minimising operational burden.

* Electronics, Home, Health and Office are the least healthy categories, consistently eroding margin in addition to high discount sensitivity and elevated returns. Other categories observed moderate performance. Any products with <20% margin, >=10% return rates and high discount sensitivity should be reviewed.

<br>

<img width="906" height="610" alt="Image" src="https://github.com/user-attachments/assets/ea716023-cd9c-400d-8ade-082c8ca7d3de" />


**Graph :** Shows Margin vs Discount Sensitivity. Sports and Beauty being high margin, low discount sensitivity. Electronics, Home, Health, and Office being low margin, high discount sensitivity.

<br>

**3. There is no clear driver of returns, having a lower impact on margin than discounts. Focus on range consolidation and discount stategy to improve margins.**

 * Return rate stable YoY at 6.8% in the last year, no notable seasonality trend or significant spikes.

 * Expected trends including higher priced items and first time buyers seeing higher returns are observed.
 
 * There may be potential issues with the marketplace platform fit and US operations with both seeing higher return rates - further information should be collected on returns so we can paint a clearer picture of the issue.

<br>

## 🚀 Next Steps

**1. Develop optimised discounting strategy -** Using product-level discount sensitivity and margin thresholds to set strategy - as an initial step, remove discounts from low-discount sensitivity products - measure and monitor effects to inform future testing.

**2. Increase marketing investment for Beauty -**  Hair Repair Shampoo Plus, Hydrating Face Cream and Cleansing Gel XL recommended as trial products for their high margins, moderate volumes and low return rates. Shift proportion of marketing budget from Electronics, Home, Health, and Office to Beauty expansion.

**3. Rationalise remaining categories to more profitable products -** <20% margin and return rates >=10% suggested to minimise loss from operational costs in addition to those with >70% volume sold at discount to minimise margin erosion from discounting.

<br>

## 📈 Tableau Dashboard
<br>

https://public.tableau.com/app/profile/alexandra7258/viz/ProductPerformanceMarginDiscountSensitivity/MarginDiscountSensitivity?publish=yes
