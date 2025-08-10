# Amazon-E-commerce-Analytics
Advanced SQL and ML analytics for Amazon e-commerce data


A comprehensive data analytics project analyzing Amazon e-commerce data using advanced SQL queries, machine learning recommendation systems, and business intelligence dashboards.

An ERD diagram is included to visually represent the database schema and relationships between tables

<img width="1430" height="778" alt="Amazon ERD" src="https://github.com/user-attachments/assets/b08181e2-967a-4dc5-8965-479a82f62853" />

## Project Overview

This project demonstrates end-to-end data analysis of an Amazon-like e-commerce platform, covering:
- **Advanced SQL Analytics**: 22+ complex business problems solved
- **Recommendation Systems**: Multiple ML approaches for product recommendations
- **Business Intelligence**: Interactive dashboards and KPI tracking
- **Database Management**: Stored procedures and automated inventory management

## Project Structure

```
amazon-ecommerce-analytics/
│
├── sql/
│   ├── solutions.sql              # Complete SQL solutions (22 problems)
│   ├── problem_statements.sql     # Business problem definitions
│   └── stored_procedures.sql      # Inventory management automation
│
├── notebooks/
│   └── recommendation_systems.ipynb  # ML recommendation models
│
├── dashboards/
│   ├── executive_summary.png
│   ├── sales_performance.png
│   ├── inventory_management.png
│   ├── customer_analytics.png
│   ├── product_performance.png
│   └── operations_logistics.png
│
├── data/
│   ├── schema/
│   │   └── database_schema.md     # Database structure documentation
│   └── sample_data/               # Sample datasets (if applicable)
│
├── docs/
│   ├── business_requirements.md
│   └── technical_documentation.md


##  Key Features

### Advanced SQL Analytics
- **22 Complex Business Problems** solved with optimized queries
- **Window Functions** for trend analysis and ranking
- **CTEs and Subqueries** for complex data transformations
- **Stored Procedures** for automated inventory management
- **Performance Optimization** techniques

### Machine Learning Recommendation Systems
- **Collaborative Filtering** using cosine similarity
- **Matrix Factorization** with SVD
- **Association Rules Mining** with Apriori algorithm
- **Deep Learning** with Apache Spark ALS
- **Model Evaluation** with RMSE and MAE metrics

### Business Intelligence Dashboards
- **Executive Summary** with key KPIs
- **Sales Performance** tracking and forecasting
- **Inventory Management** with stock alerts
- **Customer Analytics** and segmentation
- **Product Performance** analysis
- **Operations & Logistics** optimization

##  Business Problems Solved

### Sales & Revenue Analysis
1. **Top Selling Products** - Identify best performers by sales value
2. **Revenue by Category** - Category-wise contribution analysis
3. **Monthly Sales Trends** - Time-series analysis with YoY comparison
4. **Average Order Value (AOV)** - Customer value segmentation

### Customer Analytics
5. **Customer Lifetime Value (CLTV)** - Revenue prediction and ranking
6. **Inactive Customers** - Churn identification and re-engagement
7. **Customer Segmentation** - Behavioral analysis and targeting
8. **Cross-sell Opportunities** - Product recommendation insights

### Inventory & Operations
9. **Stock Alerts** - Low inventory identification with restock dates
10. **Shipping Delays** - Logistics performance monitoring
11. **Return Analysis** - Product return rates and patterns
12. **Seller Performance** - Success rate and revenue analysis

### Advanced Analytics
13. **Profit Margin Analysis** - Product profitability ranking
14. **Payment Success Rates** - Transaction analysis by status
15. **Geographic Performance** - State-wise sales analysis
16. **Seasonal Trends** - Time-based pattern recognition

## 🛠️ Technologies Used

### Database & SQL
- **PostgreSQL** - Primary database system
- **Advanced SQL** - Window functions, CTEs, stored procedures
- **Database Design** - Normalized schema with proper indexing

### Python & Machine Learning
- **Pandas & NumPy** - Data manipulation and analysis
- **Scikit-learn** - ML algorithms and model evaluation
- **Apache Spark** - Distributed computing for large-scale ML
- **MLxtend** - Association rules mining
- **Jupyter Notebooks** - Interactive development environment

### Business Intelligence
- **Custom Dashboards** - KPI visualization and monitoring
- **Performance Metrics** - Real-time business insights

## 📊 Sample Insights

### Key Business Metrics
- **Total Revenue**: $3.35M with 75.49% profit margin
- **Customer Base**: 898 total customers with $23.6M lifetime value
- **Inventory Turnover**: 630.82 ratio with 4.50K days of supply
- **Return Rate**: 13.13% overall product return rate

### Top Performing Categories
1. **Electronics** - Highest revenue contributor
2. **Home & Kitchen** - Best profit margins
3. **Sports & Outdoors** - Fastest inventory turnover

### Recommendation System Performance
- **SVD Model**: RMSE 0.5147, MAE 0.1403
- **ALS Model**: RMSE 1.439 (distributed processing)
- **Association Rules**: Identified key product bundles
