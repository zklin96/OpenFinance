# OpenFinance
GitHub repository for 2024/2025 MSc Mathematical and Computational Finance dissertation

The 'initial data' folder contains csv files on our initial dataset, comprising income and monthly debt payment data for all 100,000 customers. 

The 'tables for Bayesian imputations' folder contains 2-way and 3-way tables in the csv format, which we use for the purpose of label imputation for 'region', 'SOC occupational code', 'age group' and 'housing tenure'. 

The 'Tables for EDA and plotting' folder contains csv files which are used for exploratory data analysis and graphs plotting.

The 'Output files' folder contains csv files which are produced by the program. In particular:

- 'clustered_df.csv' provides the cluster label from K-means clustering for all 100,000 customers.
- 'analysis_new_4.csv' provides breakdown of useful cash flow, savings, spending habit, financial prudence features across clusters. 
- 'robustness_df2.csv' contains data which is used to analyze the accuracy of our imputations against baseline (Office of National Statistics, Financial Conduct Authority) data
- 'robust_alternatives.csv' contains data which is used for alternative imputation of 'housing tenure' label through the hybrid iterative proportional fitting (IPF) approach. 

