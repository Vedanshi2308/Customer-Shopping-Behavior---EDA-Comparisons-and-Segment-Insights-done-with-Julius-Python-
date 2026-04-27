Customer Shopping Behavior - EDA, Comparisons, and Segment Insights (done with Julius + Python)

I recently experimented with a new AI tool for data analysis - Julius (Python in a notebook) to explore a customer shopping behavior dataset and translate it into business-facing insights.

The dataset included ~3,900 purchase events across 18 features, covering customer attributes, purchase details, commercial levers (discounts, shipping, subscriptions), and behavioral outcomes.

Since there was no timestamp available, I focused on:
• Segment-based comparisons (e.g., category, subscription status, discounts)
• “Trend-like” patterns using ordered fields like Season and Purchase Frequency
• Customer-level aggregation to better understand value and behavior

🔍 A few insights that stood out:

• Category performance was driven more by volume than differences in order value - Clothing dominated, suggesting merchandising and cross-sell matter more than pricing shifts
• Slightly higher spend appeared in Fall/Winter vs Spring/Summer, hinting at stronger seasonal buying moments
• Subscribers didn’t spend more per order, reinforcing that subscriptions are more about retention than basket size
• Discounts and promo codes didn’t increase order value they likely impact conversion or purchase frequency instead
• Geographic differences existed, but only became meaningful after applying minimum sample thresholds

💡 Business takeaways:

• Position subscriptions as a retention lever (loyalty, perks, early access)
• Move from blanket discounts to targeted lifecycle strategies (win-back, seasonal, category-specific)
• Align merchandising and campaigns with stronger seasonal periods (especially Fall/Winter)
• Treat geo insights carefully - validate with volume and test before scaling

⚠️ One important limitation:
Without timestamps, true time-series analysis (e.g., revenue trends over time) wasn’t possible. The “trends” here are based on ordered categories, not actual temporal data.

Overall, this was a great exercise in turning imperfect data into actionable insights - which is often the reality in business settings.

Curious to hear how others approach analysis when key fields (like time) are missing 👇

#DataAnalytics #DataScience #BusinessAnalytics #AI #MachineLearning #Python #CustomerInsights #Ecommerce #DataDriven #AnalyticsProjects #LearningInPublic
