# Zomato-EDA
Exploratory data analysis on 51,000+ Zomato Bangalore  restaurants using Python and Pandas — data cleaning,  analysis and visualization of ratings, cuisines and locations.
# Zomato Bangalore Restaurant Analysis

## Tools Used
Python | Pandas | Matplotlib | Seaborn

## Objective
Analyse 51,000+ Zomato restaurant records from Bangalore 
to find patterns in ratings, cuisines, locations and pricing.

## Dataset
- Source: Kaggle — Zomato Bangalore Restaurants by himanshupoddar
- Original rows: 51,717
- Cleaned rows: 43,533
- Note: Dataset not uploaded due to large file size
- Download: kaggle.com/datasets/himanshupoddar/zomato-bangalore-restaurants

## Data Cleaning Steps
- Removed duplicate records
- Handled null values in important columns
- Fixed rate column (removed '/5' and converted to float)
- Fixed cost column (removed commas and converted to float)
- Standardized phone numbers (kept first number only)
- Renamed columns for easier analysis

## Key Findings
- BTM has the highest number of restaurants in Bangalore
- North Indian is the most popular cuisine
- Average cost for two people is ₹595
- Delivery type restaurants are most common
- Average restaurant rating is 3.70 out of 5
- Restaurants with online ordering have higher ratings

## Charts
1. <img width="1181" height="490" alt="chart1_locations" src="https://github.com/user-attachments/assets/111611ee-b4d5-4dc8-b985-05ad83d84b14" />

2. <img width="690" height="1190" alt="chart2_online_orders vs rating" src="https://github.com/user-attachments/assets/b6704251-bef5-4492-a4c1-e7c0be9d9d52" />

3. <img width="1189" height="490" alt="chart3_Top 10 cuisines" src="https://github.com/user-attachments/assets/cf536d89-ea3a-4e79-82e5-34a5d1c68cac" />

4. <img width="553" height="490" alt="chart4_rest types" src="https://github.com/user-attachments/assets/38fa188c-7c56-4dd3-af44-de5e9ccd1b72" />

5. <img width="789" height="490" alt="chart5_avrg cost" src="https://github.com/user-attachments/assets/5596fbab-8e02-442d-aaf9-e4af9e26f130" />

6. <img width="1181" height="490" alt="chart6_avg rating locations" src="https://github.com/user-attachments/assets/561cd4a6-e0ed-4651-b5ad-250f4ff21b65" />
