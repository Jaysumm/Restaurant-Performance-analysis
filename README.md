# Restaurant Performance Analysis

End-to-end exploratory and business analysis of Bangalore restaurants listed on Zomato, aimed at identifying the major factors driving restaurant success and delivering data-driven recommendations to the business.

## Project Objective

Perform an end-to-end exploratory and business analysis of Bangalore restaurants listed on Zomato to identify the major factors influencing restaurant success and provide data-driven recommendations that improve customer satisfaction, strengthen restaurant partnerships, and support strategic business decisions.

## Project Structure

| Phase | Status | Description |
|---|---|---|
| 1. Data Cleaning | ✅ Done | Duplicates removed, missing values handled, rating field cleaned, cost field converted to numeric, cuisine names standardized |
| 2. Exploratory Data Analysis | ✅ Done | Summary statistics, distributions, correlations, outlier detection |
| 3. Business Analysis | ✅ Done | Customer behavior, restaurant performance, pricing, cuisine, location, online ordering, table booking |
| 4. Interactive Dashboard (Tableau / Power BI) | 🔜 Next | KPI cards, bar charts, maps, treemaps, scatter plots, heatmaps, filters, rankings |
| 5. Final Recommendations | 🔜 Upcoming | Expansion, pricing, promotions, cuisine strategy, customer engagement |

## Business Questions Answered

1. **Top performers** — restaurants with the highest ratings and customer votes identified
2. **Ratings vs. engagement** — moderate positive correlation (r ≈ 0.4); a "funnel" pattern where high engagement almost guarantees decent ratings, but low engagement is unpredictable
3. **Online ordering vs. popularity** — no meaningful effect (3.59 vs. 3.65 average rating)
4. **Table booking vs. ratings** — real gap (3.57 vs. 4.11), likely a proxy for premium dining rather than a direct cause
5. **Best-performing restaurant types** — Bar/Pub/Fine Dining combinations outperform the dominant Quick Bites/Casual Dining categories
6. **Highest restaurant concentration** — tech corridors: Whitefield, Electronic City, BTM, HSR, Marathahalli
7. **Highest-rated locations** — central Bangalore (Lavelle Road, St. Marks Road, Church Street); Koramangala 5th Block stands out as both high-volume and high-quality
8. **Cuisine popularity vs. rating** — North Indian / Chinese / South Indian dominate by volume, but niche international cuisines (Japanese, Mediterranean, European) rate higher
9. **Pricing vs. satisfaction** — modest positive relationship (r ≈ 0.33); premium pricing acts as a "quality floor"
10. **Highest-growth market segments** — premium and niche segments consistently outperform saturated mass-market segments across type, location, and cuisine — the cross-cutting synthesis finding

## Key Takeaways

- Engagement (votes) is a stronger predictor of rating reliability than any single feature — low-engagement restaurants are the least predictable in quality
- Online ordering availability does **not** move the needle on ratings; table booking does, but likely reflects restaurant tier rather than causing better service
- Premium and niche positioning (cuisine, type, pricing) consistently outperforms saturated, mass-market segments
- Restaurant density and restaurant quality are concentrated in different areas — tech corridors have volume, central Bangalore has quality

## Deliverables

1. Cleaned dataset
2. EDA notebook/report (summary stats, distributions, correlations, outliers)
3. Business analysis write-up (customer behavior, performance, pricing, cuisine, location, ordering, booking)
4. Interactive Tableau/Power BI dashboard
5. Final business recommendations report

## Business Impact

This analysis is intended to help Zomato:

- Improve restaurant recommendations shown to customers
- Identify high-performing locations and cuisines
- Optimize marketing campaigns
- Strengthen restaurant partnerships
- Support expansion strategies
- Enable data-driven decision making across the business

## Next Steps

- Build the interactive dashboard (Tableau or Power BI) covering KPIs, location maps, cuisine treemaps, and rating/engagement scatter plots
- Translate findings into final recommendations for expansion targets, pricing strategy, promotional focus, and cuisine mix
