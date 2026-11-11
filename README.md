
# MongoDB Fitness Tracker Market Analysis

**MongoDB | NoSQL Database | Data Analysis | Aggregation Framework**

## Project Overview

This project focuses on analyzing fitness tracker market data using MongoDB. It involves organizing product information in a NoSQL database and performing analytical queries to explore brands, device categories, customer ratings, and battery life.

The analysis provides useful insights into product performance and market trends, supporting data-driven decisions related to product selection, inventory planning, and marketing strategies.

## Business Objectives

- Analyze average customer ratings across different brands.
- Understand the distribution of fitness tracker device types.
- Identify products offering longer battery life.
- Organize product data in a flexible MongoDB database.
- Explore indexing and query execution plans for database performance analysis.

## Dataset Overview

The dataset contains **565 fitness tracker records** with product-related information, including:

- Brand Name
- Device Type
- Model Name
- Color
- Selling Price
- Original Price
- Display
- Rating (Out of 5)
- Strap Material
- Average Battery Life (in days)
- Reviews

Both CSV and JSON dataset files are included in the repository.

## Database Implementation

**Database:** `fitness_analytics_db`

**Collection:** `fitness_trackers`

MongoDB was selected for its flexible document-based structure and support for semi-structured product data.

The implementation covers:

- Database and collection creation.
- JSON data import using `mongoimport`.
- Data verification and record counting.
- Aggregation pipelines for product analysis.
- Filtering and projection operations.
- Index creation and query execution plan analysis using `explain("executionStats")`.

## Business Analysis

| Analysis | Business Purpose |
|---|---|
| Average Rating by Brand | Compare customer ratings across brands. |
| Device Type Distribution | Understand the distribution of product categories. |
| Battery Life Analysis | Identify products with battery life of 14 days or more. |

## Indexing & Query Performance

Indexes were created on the `Brand Name` and `Rating (Out of 5)` fields.

The `explain("executionStats")` method was used to examine query execution plans and analyze execution statistics before and after indexing.

## Tools & Technologies

- MongoDB
- MongoDB Shell
- MongoDB Aggregation Framework
- JSON
- CSV
- `mongoimport`
- `explain("executionStats")`

## Technical Skills Demonstrated

- NoSQL Database Management
- MongoDB Database Design
- Data Import and Validation
- Aggregation Framework
- Data Filtering and Projection
- Database Indexing
- Query Execution Plan Analysis
- Business Data Analysis

## Repository Structure

```text
MongoDB-Fitness-Tracker-Market-Analysis/
│
├── README.md
├── Business Problems.docx
├── MongoDB Project Documentation.docx
│
├── 01_Dataset/
│   └── Dataset_Fitness_trackers.csv
│
└── 02_MongoDB_Implementation/
    ├── Fitness_trackers_Dataset.json
    └── mongo_queries.txt
```

## Project Files

| File | Description |
|---|---|
| [Business Problems](Business%20Problems.docx) | Business requirements and problem definition. |
| [MongoDB Project Documentation](MongoDB%20Project%20Documentation.docx) | Project methodology and implementation details. |
| [CSV Dataset](01_Dataset/Dataset_Fitness_trackers.csv) | Original fitness tracker dataset. |
| [JSON Dataset](02_MongoDB_Implementation/Fitness_trackers_Dataset.json) | Dataset prepared for MongoDB import. |
| [MongoDB Queries](02_MongoDB_Implementation/mongo_queries.txt) | Database commands and analytical queries. |

## Business Value

This project demonstrates how MongoDB can be used to manage and analyze product-level data. The analysis helps compare brands, understand product categories, identify products with longer battery life, and support inventory and marketing decisions.

## About the Author

**Muhammad Jan**  
Data Analytics & Business Intelligence Specialist

Passionate about transforming raw data into meaningful insights through data analysis, database management, and business intelligence solutions.

- **GitHub:** [Muhammad Jan](https://github.com/Muhammad-Jan)
- **LinkedIn:** [Muhammad Jan](YOUR-LINKEDIN-PROFILE-URL)

---

**Domain:** Fitness & Wearable Technology  
**Database:** MongoDB  
**Project Category:** Data Analytics & Database Management
