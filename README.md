# Rakamin-Big-Data-Analytics-KimiaFarma

1. Project Overview

This repository contains several files, including SQL scripts, dashboard links, and the final project presentation for the **Big Data Analytics Project-Based Internship by Rakamin**, hosted by **Rakamin Academy** and **PT Kimia Farma Tbk**.

2. Tools/Platform
   
    - Data Processing : Google Big Query
    - Query Langguage : SQL
    - Data Modeling (Data Table) : Quick DBD (ERD)
    - Visualization : Google Data Studio/Looker Studio

3. Workflow Phase

  **Phase 1:Setup Data**

The first stage in this project is setting up the project and dataset in Google BigQuery, then importing the four main CSV files: `kf_final_transaction`, `kf_inventory`, `kf_kantor_cabang`, and `kf_product`. The purpose of this stage is to store all raw data in the BigQuery database so that the data can be managed, checked for column structure, and processed using SQL. Once the datasets have been imported into BigQuery, the next analysis processes, such as table joining, analysis table creation, and dashboard visualization, can be carried out in a more structured and efficient way.

   **Phase 2: Data Processing (Join)**

The second stage is creating `tabel_analisa` using SQL syntax in BigQuery. In this stage, the four previously imported datasets are combined based on `branch_id` and `product_id` to produce one main table containing transaction, product, branch, location, rating, and stock information. In addition to the JOIN process, several calculated columns are also created, such as `discount_rate`, `persentase_gross_laba`, `nett_sales`, and `nett_profit`, so the data is ready to be used for business performance analysis.

The purpose of this stage is to create an integrated data source that can be used as the foundation for dashboard development. With `tabel_analisa`, the process of calculating sales, profit, product performance, branch performance, province performance, and transaction ratings becomes easier, more consistent, and more efficient.


**Phase 3: Data Visualization**

The third stage is creating the Kimia Farma Performance Analytics Dashboard 2020–2023 using Google Looker Studio based on the tabel_analisa table created in BigQuery. This dashboard displays key metrics such as total nett sales, total nett profit, total transactions, and total customers. It is also supported by visualizations such as sales trends, profit distribution by province, yearly sales contribution, top provinces by transactions and nett sales, as well as a comparison between branch rating and transaction rating.

The purpose of this stage is to present the analysis results in a visual, interactive, and informative format that is easy to understand. Through this dashboard, Kimia Farma’s business performance can be monitored more efficiently to support decision-making related to sales, profitability, priority regions, and branch service quality.

4. Final Result: Dashboard Perfomance Analytics Kimia Farma (2020-2023)

   Click here for more detail about Google Data Studio Dashboard:
   https://datastudio.google.com/reporting/bdeead85-d852-48be-87f4-f4db738be02a 
