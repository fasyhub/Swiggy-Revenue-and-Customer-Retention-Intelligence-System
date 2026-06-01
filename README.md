This project analyzes Swiggy restaurant-level data to uncover key insights about customer satisfaction, delivery performance, ratings, pricing patterns, and revenue behavior.
The analysis includes Univariate, Bivariate, Multivariate Analysis, Correlation Study, Pairplot Exploration, VIF, and Principal Component Analysis (PCA).
All insights are focused on supporting business decision-making.

Dataset :

The dataset contains the following important columns:
- Price
- Avg_ratings
- Total_ratings
- Delivery_time
- Estimated_revenue
- Satisfaction_score
- Cuisine_count
- ID

Data Cleaning Steps :
- Removed duplicates
- Handled missing values
- Corrected data types
- Outlier checks using boxplots
- Cleaned categorical and numerical inconsistencies

Exploratory Data Analysis (EDA) :

1. Univariate Analysis
- Distribution of numeric features
- Price variations
- Satisfaction score distribution
- Delivery time spread
- Ratings behavior

2. Bivariate Analysis
- Price vs Ratings
- Delivery_time vs Satisfaction_score
- Cuisine_count vs Estimated_revenue
- Avg_ratings vs Satisfaction_score
- City vs Price (if applicable)

3. Multivariate Analysis
- Correlation heatmap
- Pairplot to visualize relationships
- VIF analysis to detect multicollinearity
- PCA to reduce dimensional dependency

Technologies Used : 
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Google Colab

 Google Sheets Link : https://docs.google.com/spreadsheets/d/14DmNAlpWll55waEJVBLWsJKneMYaQBSrffBTrBbz11g/edit?usp=sharing
 Google Colab Link : https://colab.research.google.com/drive/1x2V8p0mImIOBuS7XWZf4fWyN0weePmpO?usp=sharing
 Tableau Dashboard : https://public.tableau.com/views/SwiggyRevenueCustomerRetentionIntelligenceDashboard/SwiggyRevenueCustomerRetentionDashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

INSIGHT SUMMARY :

1️. Customer Satisfaction Drivers :
- Delivery time is the strongest determinant of customer satisfaction.
- Satisfaction drops sharply once delivery time exceeds 40 minutes.
- Deliveries under 30 minutes consistently achieve the highest satisfaction scores.

2️. Ratings Influence Behavior :
- Higher average ratings are strongly linked with higher satisfaction.
- Restaurants with high total ratings also tend to generate significantly higher revenue.

3️. Revenue Patterns :
- Revenue is highly correlated with:
- Total ratings
- Estimated popularity
- Customer engagement metrics
- Price has a mild effect, meaning customer volume matters more than premium pricing.

4️. Price Dynamics :
- Cities have similar median price ranges except a few outliers.
- Higher prices do NOT guarantee higher ratings or satisfaction.
- Price is not a strong driver of customer sentiment compared to delivery speed & rating quality.

5️. Delivery Time Analysis :
- Longer delivery times consistently reduce both:
- Satisfaction score
- Rating behavior
- After around 80 minutes, satisfaction stays at a low baseline — delays beyond this point do not add additional damage.

6️.Cuisine Impact :
- More cuisine variety correlates with:
- Higher customer engagement
- Slightly higher satisfaction
- But it is not a top-tier driver compared to delivery and ratings.

7️. PCA (Dimensional Analysis) Findings :
- PCA confirms the feature structure:
- PC1 (Overall Popularity Component): Ratings, total ratings, revenue
- PC2 (Service Quality Component): Delivery time vs satisfaction
- PC3 (Pricing Component): Price behavior
- PC4 (Diversity Component): Cuisine variety
- ~85% of total variance is explained by top components, proving the relationships are strong and structured.

8️. Key Takeaways :
- Speed + Rating Quality = Best Predictors of Success
- Pricing ≠ Customer happiness
- High-rating restaurants with optimized delivery outperform rest on revenue and satisfaction.
 -Data reveals clear patterns that Swiggy can optimize for operational improvement.




































