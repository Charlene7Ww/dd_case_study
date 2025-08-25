# DoorDash Discounts Case Study (Self-Practice)

## Background
This project is a **self-practice case study**, inspired by the **DoorDash CPG Ads & Promotions case study interview process**. 
The dataset and prompt are adapted from an [open-source GitHub resource](https://github.com/ralfsantacruz/Doordash-Analytics) and restructured purely for **learning and portfolio purposes**.

**Goal:** Evaluate whether discounts improve customer behavior and business outcomes, and identify where such campaigns are most effective.

## Methods
- **Data Prep**: Cleaned data, constructed metrics (Net Revenue Proxy, refund flag, delivery times, tip rate).  
- **Statistical Tests**: Welch’s t-test, Mann–Whitney U, Chi-square, Cohen’s d.  
- **Behavioral Analysis**: Compared orders with vs. without discounts across revenue, tips, refunds, delivery time.  
- **Segmentation**: Regional breakdown (San Jose, Palo Alto, Mountain View).  

## Key Results
- **Net Revenue per order ↓** → discounts reduced short-term profitability.  
- **New Customer Rate ↑** → statistically significant uplift, especially in San Jose (+7pp).  
- **Refund Rate** → no significant impact.  
- **Tips ↓** → discounted customers tipped less, affecting driver incentives.  
- **Delivery Times** → mixed results, no clear consistent effect.  

**Regional differences:**  

- **San Jose** → Best ROI (higher new customers, no revenue loss).  
- **Palo Alto** → Strong acquisition, weaker revenue.  
- **Mountain View** → Low acquisition, revenue decline.  

## Recommendations (Summary)
- **Overall**: Discounts are effective for **acquisition**, but not universally profitable → use selectively.  
- **Platform**: Pair discounts with **LTV/cohort analysis** to confirm long-term ROI.  
- **Restaurants**: Encourage **bundling/upsell** to offset revenue loss.  
- **Dashers**: Consider **tip guarantees or incentives** to protect driver earnings.  
- **Regional Strategy**: Scale in San Jose, optimize in Palo Alto, limit in Mountain View.  

## Limitations
- Dataset is a sample → no long-term retention or demographic info.  
- Net Revenue Proxy excludes marketing/ops costs, so ROI is approximate.  
- External effects (competitor promos, seasonality) not captured.  

## Repo Structure
