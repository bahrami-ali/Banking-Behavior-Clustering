# Patterns in Banking Behavior

## Goal
 - Use banking data to cluster and segment the customers across demographics and banking behavior
 - Determine which client segments are bringing in the most revenues and pose the most risk for the bank
 - Provide the marketing department product recommendations for each customer segment


## File Directory
1. **data:** contains the raw data (csv and sql database). Cleaned data in final_data.csv
2. **banking_data_preprocessing.ipynb:** clean the data and store in databases
    - *Tools used:* numpy, pandas, SQL
3. **banking_behavior.ipynb:** main notebook. Find clusters and patterns in demographics and banking behavior
    - Unsupervised learning:
        - K-means clustering and elbow method
        - Principal component analysis (PCA) to reduce dimensions
        - *Tools used:* Sklearn (standardscaler, Kmeans, PCA)
    - Plots: bar charts, histograms, scatter plots, and radar charts
        - *Tools used:* matplotlib, seaborn and plotly
4. **presentation:** Contains the presentation file (jupyter notebook slides)

## Data Summary
- twm_customer - information about customers
- twm_accounts - information about accounts
- twm_transactions - information about financial transactions
- other: separate files for each accounts and transactions category
