# Airbnb Data Analytics Project (End-to-End)

## 📌 Project Overview
Airbnb operates across multiple locations and room types, hosting a large number of property listings with varying prices, availability, service fees, and host characteristics.  
This project focuses on performing **end-to-end data analytics** to clean raw Airbnb data, explore meaningful patterns, and present business-relevant insights through an interactive dashboard.

The project follows a structured **ETL → EDA → Visualization** pipeline to support data-driven decision-making.

---

## 🎯 Business Problem
Decision-makers lack a clear, data-driven understanding of:
- Pricing stability and seasonal price behavior  
- Room-type monetization  
- Availability patterns and booking pressure  
- Host composition and cancellation policy distribution  

Without this visibility, it becomes difficult to optimize pricing strategies, identify high-value segments, and support strategic planning using reliable data.

---

## 🧩 Project Objectives
- Clean and transform raw Airbnb listing data  
- Handle missing values, outliers, and inconsistencies  
- Analyze pricing trends and seasonal patterns  
- Compare average price and service fees by room type  
- Understand availability behavior and host distribution  
- Present insights using an interactive Power BI dashboard  

---

## 🔄 Project Pipeline
1. **Extract**
   - Loaded raw Airbnb CSV data into Python using Pandas

2. **Transform**
   - Removed duplicates  
   - Handled missing values (median for numerical, mode for categorical)  
   - Cleaned currency symbols and converted data types  
   - Fixed categorical inconsistencies (e.g., neighbourhood names)  
   - Handled outliers using logical business rules  
   - Parsed and validated date fields  

3. **Load**
   - Stored the cleaned dataset into a MySQL database using SQLAlchemy  

4. **EDA (Exploratory Data Analysis)**
   - Distribution analysis of numerical variables  
   - Pricing trend analysis (yearly and monthly average price)  
   - Room type comparison (price and service fees)  
   - Availability pattern analysis  
   - Host identity and cancellation policy analysis  
   - Location-based listing analysis  

5. **Visualization**
   - Built an interactive Power BI dashboard to present final insights

 **Dashboard Views**
 ![Dashboard](Airbnb_Dashboard.png)

---

## 🛠️ Tools & Technologies
- **Python** (Pandas, NumPy, Matplotlib, Seaborn)
- **SQL / MySQL**
- **SQLAlchemy**
- **Power BI**
- **Jupyter Notebook**

---

## 📊 Key Insights
- Average listing prices remain relatively stable over time, indicating pricing maturity  
- Seasonal patterns exist, with moderate price variation across months  
- Hotel rooms have the highest average price and service fees, positioning them as a premium segment  
- Most listings fall under low availability, suggesting high booking pressure or part-time hosting  
- Brooklyn and Manhattan contribute the highest number of listings  
- Host verification and cancellation policies are almost evenly distributed  

---

## 📁 Repository Structure
| Folder / File | Description |
|---------------|-------------|
| `Airbnb_Problem_Statement.md` | Business problem definition and project objectives |
| `airbnb_raw_data.csv` | Raw Airbnb dataset used for analysis |
| `Airbnb_EDA.ipynb` | Jupyter Notebook containing ETL and EDA steps |
|`EDA_Report.pdf` | PDF summary of exploratory data analysis and insights |
| `Airbnb_Dashboard.pbix` | Interactive Power BI dashboard file |
| `Airbnb_Dashboard.png` | Static preview image of the Power BI dashboard |
| `README.md` | Project overview, methodology, and key insights |


---

## 📌 Files Included
- **Airbnb_Problem_Statement.md** – Business problem and objectives  
- **Airbnb_EDA.ipynb** – Complete ETL and EDA process  
- **EDA_Report.pdf** – Summary of analysis and insights  
- **Airbnb_Dashboard.pbix** – Interactive Power BI dashboard  
- **Airbnb_Dashboard.png** – Dashboard preview image  
- **airbnb_raw_data.csv** – Original dataset  

---

## 🚀 Conclusion
This project demonstrates an **end-to-end data analytics workflow**, from raw data cleaning to business insight generation and dashboard storytelling.  
It highlights strong analytical thinking, metric selection, and clear communication of insights for decision-making.

---

## 👤 Author
**Ravi Kumar Gupta**  
Aspiring Data Analyst  


