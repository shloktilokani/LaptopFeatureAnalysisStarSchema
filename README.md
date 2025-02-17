# Laptop Price Analysis & Prediction

![Laptop Price Analysis](https://github.com/shloktilokani/LaptopFeatureAnalysisStarSchema/blob/main/Res/Recording%202025-02-17%20003235.gif)

## 📌 Project Overview
This project focuses on analyzing laptop pricing trends, brand performance, and market segmentation using a structured dataset. The dataset consists of 823 different laptop models with 19 attributes covering specifications like brand, processor, RAM, storage, OS, graphics, pricing, and user ratings. The structured approach using a Star Schema helps in efficient data querying and business intelligence analysis.

## 📊 Dataset Description
The dataset includes essential laptop attributes categorized into six major sections:

1. **Brand & Processor Specifications** - Brand, CPU manufacturer, processor series, and generation.
2. **Memory & Storage Configuration** - RAM size, type, SSD and HDD storage.
3. **Operating System & Architecture** - Installed OS and system architecture (32-bit or 64-bit).
4. **Graphics & Display Features** - Dedicated vs. integrated GPU, touchscreen support.
5. **Additional Features** - Weight, warranty, MS Office pre-installation.
6. **Pricing & Market Data** - Laptop price, user ratings, reviews, and popularity.

## 🛠 Data Cleaning Process
To ensure data accuracy and consistency, the following cleaning steps were applied:

- **Handling Missing Values** – Removed entries with missing critical details.
- **Removing Duplicates** – Eliminated redundant laptop entries.
- **Fixing Inconsistent Data** – Validated RAM, storage, and removed unrealistic values.
- **Creating Dimension Tables** – Organized categorical data into separate tables for normalization.
- **Creating Fact Table Using VLOOKUP** – Mapped dimension table values for optimized data retrieval.

## 🔗 Star Schema Design
The dataset is structured using a **Star Schema**, consisting of:
- **Fact Table (FactLaptop)** – Stores numerical values and measurable attributes.
- **Dimension Tables (DimBrand, DimOS, DimProcessor, etc.)** – Standardizes key laptop attributes for faster lookups and better query performance.

### **Benefits of Star Schema:**
- Efficient query performance  
- Simple and scalable database structure  
- Fast aggregation and reporting for business intelligence  

## 📈 Insights & Key Findings
### 1️⃣ **Pricing Trends**
- **Minimum Price:** ₹17K | **Maximum Price:** ₹442K | **Average Price:** ₹76.75K
- Apple laptops have the **highest average price**, while Dell has the **lowest.**
- **Higher RAM configurations (16GB, 32GB)** significantly increase laptop prices.

### 2️⃣ **Brand Market Share**
- **ASUS (30.26%)** has the highest market share, followed by HP (18.35%) and Lenovo (17.5%).
- MSI and Apple dominate the premium segment with higher average prices.

### 3️⃣ **Customer Preferences & Ratings**
- **Gaming laptops** with dedicated GPUs receive **higher ratings**.
- **Laptops with SSD storage** are preferred over HDD models.

## 📊 Power BI Dashboard
A **Power BI Dashboard** was created for an interactive visual analysis of:
- **Laptop Price vs. Features** (Brand, RAM, Processor, OS, etc.)
- **Brand Popularity & Market Share**
- **Customer Ratings & Reviews Analysis**
- **Filters for Price, Processor, Laptop Type, OS, and Brand**

## 📌 Business Applications
- **Price Optimization** – Understand how specifications impact pricing.  
- **Market Segmentation** – Identify consumer trends and demand patterns.  
- **Product Portfolio Management** – Stock inventory based on popularity and trends.  
- **Sales & Brand Analysis** – Evaluate brand performance and pricing strategies.  

## 🎯 Conclusion
The structured approach of **data warehousing** and **business intelligence tools** enables businesses to make data-driven decisions regarding **pricing strategies, customer preferences, and product positioning** in the laptop market.

---
### 🚀 Technologies Used
- **Python, Pandas** – Data Cleaning & Preprocessing  
- **SQL** – Database Management & Star Schema Implementation  
- **Power BI** – Dashboard & Data Visualization  

📢 **Future Enhancements:** Implement **Machine Learning Models** for price prediction based on laptop specifications!
