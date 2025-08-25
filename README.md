# Amazon-Air-Conditioner-Analysis
Amazon Air Conditioner dataset: cleaning, analysis, and visualization with Power Query

## 📖 Objective
The purpose of this project is to **analyze Amazon air conditioner products** to identify trends across brands, pricing, and product performance.  
The analysis focuses on comparing brands, identifying the most expensive and most affordable products, and determining which brands dominate in terms of quantity and pricing strategy.

## 🛠️ Tools & Technologies
- **Excel:** For initial data handling and preparation.  
- **Power Query:** For data cleaning and transformation, including handling missing values and standardizing columns.  
- **Power BI:** For creating dashboards and visualizing brand comparisons, price distributions, and sales insights.  

## 📊 Dataset
- **Source:** Air Conditioners.csv
- **Structure:** Contains attributes such as:  
- Name
- Main Category
- Sub Category
- Image
- Link
- Ratings
- No of Ratings
- Discount price
- Actual Price 

## 🔎 Process
1. **Data Cleaning**  
   - Replaced missing values in price columns with averages by brand or product category.  
   - Removed duplicate or irrelevant columns.  
   - Ensured consistency in product and brand names.  

2. **Transformation**  
   - Organized data for comparative analysis by brand and price.  
   - Created measures for highest, lowest, and average product prices.  

3. **Analysis & Visualization**  
   - Identified the most expensive and least expensive air conditioners.  
   - Compared number of products per brand.  
   - Highlighted the brands with the highest sales presence.  
   - Visualized discount price vs. final product price distributions.  

## 📈 Results
- The brand with the largest number of products was identified.  
- Significant price differences between brands were observed.  
- Discount strategies varied, showing how some brands rely more on discounts than others.  
- The dashboard allows filtering by brand to compare prices and availability.

## 📂 Repository Structure
-	Raw dataset -> Air Conditioners.csv
-	Cleaned dataset -> Airs_clean.csv
-	Power BI Dashboard -> Air Conditioner Dashboard.pbix / Air Conditioner Dashboard PDF.pdf
-	Data Insights Presentation -> PT Amazon Air Conditioner Analysis.pdf
