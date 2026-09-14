# Google Play Store Analysis — Power BI Dashboard

## Project Overview
An interactive Power BI dashboard analyzing 7,000+ apps from the Google Play Store, covering installs, ratings, pricing models, and category-level performance.

## Tools Used
- Power BI Desktop - Main data visualization for creation report.
- Power Query - Data transformation
- DAX - Used for Calculated measure, dynamic visual.
- Dataset: Google Play Store Apps (public dataset).

## Business Problem
App publishers and marketers need to make decisions about which category to build in, how to price an app, and where user satisfaction is highest 
— but raw app-store data is too large and unstructured to interpret at a glance. This dashboard turns that data into a decision-support tool.

## Key Insights
- Market Opportunity — Games dominate installs (10.7bn), showing where the largest audience already exists.
- Pricing Strategy — 92.35% of apps are free vs. 7.65% paid, confirming a freemium-first market and informing monetization strategy for new apps.
- Quality vs. Volume Trade-off — High-install categories (Games, Family) aren't always the highest rated. Niche categories like Events and Art & 
  Design post the best average ratings (4.5), pointing to underserved, high-satisfaction segments.
- Engagement Correlation — Installs and reviews move together closely, suggesting organic growth is strongly tied to user engagement (useful for ASO/marketing prioritization).
- Audience Targeting — ~81% of apps are rated "Everyone," showing the market skews toward broad, general-audience design.

## Key KPIs
- Total Installs by Category (Bar Chart)
  Displays total download counts across different app genres, led by Game (10.7bn) and Family (4.5bn).
- Free vs Paid Split (Donut Chart)
  Breaks down the catalog into free apps (92.35%, 6.48K) versus paid apps (7.65%, 0.54K).
- Avg Rating by Category (Column Chart)
  Compares the mean user satisfaction scores across categories, with top niches like Events and Art & Design leading at 4.4–4.5 . 
- Content Rating Distribution (Donut Chart)
  Shows the proportion of apps classified by audience age, dominated by "Everyone" (80.84%, 5.67K) followed by "Teen" (11.1%).
- Reviews vs Installing (Scatter Plot)
  Plots review volumes against total app installations across logarithmic scales.
- App Details Table (Data Grid)
  Provides granular, row-by-row records listing specific app names, categories, star ratings, review counts, install figures, and pricing.
  
## File
- Power BI dashboard file - https://github.com/deepakrajput2622a-dotcom/google-play-store-analysis/blob/main/google%20play%20store.pbit
- Project/dashboard documentation -   https://github.com/deepakrajput2622a-dotcom/google-play-store-analysis/blob/main/google%20play%20store%20project.pdf
  
