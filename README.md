# Sales Prediction Project

## Project Description
This project analyzes and predicts sales for products across different outlets.  
The goal is to provide actionable insights and accurate sales predictions to help management optimize inventory and marketing strategies.

---

## Part 1 – Load and Inspect Data
- Load the dataset into a pandas DataFrame.  
- Inspect the dataset using `.info()`, `.head()`, `.shape`, and `.dtypes`.  
- Understand the structure, types, and completeness of the data.  

---

## Part 2 – Clean Data
- Remove duplicate rows to ensure data integrity.  
- Handle missing values:
  - Fill missing numeric values (e.g., `Item_Weight`) with 0.  
  - Fill missing categorical values (e.g., `Outlet_Size`) with 'Unknown'.  
- Standardize text and correct inconsistent categories (e.g., `Item_Fat_Content`).  
- Verify cleaning with summary statistics and counts.

---

## Part 3 – Exploratory Data Analysis (EDA)
Focuses on **understanding patterns, distributions, and trends** in the data using visualizations.

### Key Visuals & Insights

**1️⃣ Boxplot of `Item_Outlet_Sales`**  
 
<img width="515" height="463" alt="boxplot for iten outlet sales" src="https://github.com/user-attachments/assets/0b3dd4bc-952f-449a-899f-a0c1b37b81a5" />

  

*Insight:* Most products have moderate sales, while a few products show extremely high sales, indicating potential outliers or high-demand items.

**2️⃣ Countplot of `Outlet_Type`**  
 
<img width="586" height="536" alt="countplot outlet type" src="https://github.com/user-attachments/assets/d0979c9c-8ef0-4f5f-806e-321c40bb35d3" />

*Insight:* Supermarket Type1 outlets are the most frequent, which could influence overall sales trends and inventory planning.

### Additional Visualizations
- **Histograms of numerical features** (`Item_Weight`, `Item_Visibility`, `Item_MRP`, `Item_Outlet_Sales`, `Outlet_Establishment_Year`) to check distributions.  
- **Boxplots of numerical features** to identify extreme values.  
- **Countplots of categorical features** (`Item_Fat_Content`, `Item_Type`, `Outlet_Size`, `Outlet_Location_Type`) to understand class frequencies.  
- **Correlation heatmap** to explore relationships between numerical features.

---

## How to Run
1. Load the CSV data into a pandas DataFrame.  
2. Generate visualizations using Matplotlib or Seaborn.  
3. Analyze the plots to extract insights and prepare the data for predictive modeling.

---

## Recommendations
- Focus on high-performing outlets for promotions.  
- Consider adjusting inventory for outlier products with extreme sales.  
- Use insights from EDA to guide feature selection for predictive models.

---

## Limitations & Next Steps
- Some features have missing values, which may reduce accuracy if not handled properly.  
- External factors (e.g., seasonal trends, regional events) are not included but could influence sales.  
- Next steps: build predictive models (e.g., regression or ensemble methods) and evaluate their performance on unseen data.

---

## For Further Information
For any questions, please contact: israarashed21@gmail.com
