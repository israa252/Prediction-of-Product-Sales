# Sales Prediction Project

## Project Description
This project aims to analyze and predict sales for products across different outlets.  
It is divided into three main parts:

---

## Part 1 – Load and Inspect Data
- Load the dataset into a pandas DataFrame.  
- Inspect the dataset using `.info()`, `.head()`, `.shape`, and `.dtypes`.  
- Understand the basic structure and types of the data.  

---

## Part 2 – Clean Data
- Remove duplicate rows.  
- Handle missing values:
  - Fill missing numeric values (e.g., `Item_Weight`) with 0.  
  - Fill missing categorical values (e.g., `Outlet_Size`) with 'Unknown'.  
- Standardize text and correct inconsistent categories (e.g., `Item_Fat_Content`).  
- Display summary statistics to verify the cleaning process.

## Part 3 – Exploratory Data Analysis (EDA)
Focuses on **understanding the data** through visualization:

### Key Visuals & Insights

**1️⃣ Boxplot of `Item_Outlet_Sales`**  
![Boxplot of Item_Outlet_Sales]
<img width="515" height="463" alt="boxplot for iten outlet sales" src="https://github.com/user-attachments/assets/0b3dd4bc-952f-449a-899f-a0c1b37b81a5" />

*Interpretation:* Most products have moderate sales, while a few products show extremely high sales as outliers.

**2️⃣ Countplot of `Outlet_Type`**  
![Countplot of Outlet_Type]
<img width="586" height="536" alt="countplot outlet type" src="https://github.com/user-attachments/assets/d0979c9c-8ef0-4f5f-806e-321c40bb35d3" />

*Interpretation:* Supermarket Type1 stores are the most common, which could influence overall sales trends.

### Additional Visualizations
- **Histograms of numerical features** (`Item_Weight`, `Item_Visibility`, `Item_MRP`, `Item_Outlet_Sales`, `Outlet_Establishment_Year`) to understand distributions.  
- **Boxplots of numerical features** to identify outliers.  
- **Countplots of categorical features** (`Item_Fat_Content`, `Item_Type`, `Outlet_Size`, `Outlet_Location_Type`) to understand class frequencies.  
- **Correlation heatmap** for numerical features to check relationships.

---

## How to Run
1. Load the CSV data into a pandas DataFrame.  
2. Use Matplotlib/Seaborn to generate visualizations.  
3. Analyze the plots to derive insights and prepare for modeling.

--
 
