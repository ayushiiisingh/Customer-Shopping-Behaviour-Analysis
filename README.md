### Customer Shopping Behavior Analysis
### Overview

This project analyzes customer shopping behavior using a dataset of 3,900 purchases to uncover insights on spending patterns, customer segments, and product preferences.
The full analytics pipeline includes Python-based data preparation, SQL-based querying, Power BI dashboarding, and a final PPT deck made in Gamma.

### Dataset
Attribute	Value
Rows	3,900
Columns	18
Includes	age, gender, location, subscription status, items purchased, category, amount spent, season, size, color, discount, promo codes, shipping, product ratings
Tools Used
Area	Tools
Programming	Python
Databases	PostgreSQL
Visualization	Power BI
Presentation	Gamma
Python Libraries	pandas, numpy, matplotlib, seaborn, sqlalchemy
### Steps Performed

### Data Loading & EDA → imported data using pandas, explored structure & summary stats

### Data Cleaning → handled missing values (37 missing ratings filled using category-wise median)

### Feature Engineering → created age_group and purchase_frequency_days to enrich behavioral insights

### Database Integration → loaded cleaned table into PostgreSQL for advanced SQL querying

### Visualization → built interactive Power BI dashboard highlighting revenue, segments, products & behavior

### Final Reporting → created a Gamma PPT summarizing final insights & recommendations

### Insights

Male customers generated 68% revenue ($157,890) vs females ($75,191)

Customer base segmentation shows 3,116 loyal customers driving the majority of purchases

Top-rated products include Gloves, Sandals, Boots, Hat, Skirt

Discounts don’t always mean low spend → 839 high spenders still used discounts

Subscription status has minimal spend difference → benefit structure needs improvement

Revenue contribution across age groups is balanced, indicating broad market appeal

### Dashboard

The Power BI dashboard includes:

Revenue by gender / age / category

Customer segment breakdown

Top-rated products

Discount vs spend behavior

Recommendations

Strengthen subscription perks

Build loyalty reward campaigns

Optimize discount strategy to balance margins

Highlight top-rated products in campaigns

Target high revenue age groups + male shoppers
