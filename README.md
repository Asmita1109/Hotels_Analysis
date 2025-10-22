
# 🏨 AtliQ Hotels Data Analysis Project

### 📘 Overview
This project focuses on **analyzing hotel performance and booking data** to uncover trends, identify key performance drivers, and provide actionable insights for business decisions.  
The project is part of the **Hospitality Domain Analytics** initiative, using data-driven techniques to evaluate metrics like occupancy rate, revenue realization, and booking platform performance.

---

### 🎯 Objectives
- Perform **data cleaning, transformation, and exploration** on multiple datasets.  
- Analyze **booking capacity vs. utilization** and identify overbooking or underbooking patterns.  
- Derive **business insights** from aggregated revenue and successful booking data.  
- Visualize key metrics using Python for better decision-making.

---

### 📂 Dataset Description
The project uses five CSV files representing different dimensions of the hospitality data:

| File Name | Description |
|------------|-------------|
| `dim_date.csv` | Contains date-related dimensions like day, month, and year |
| `dim_hotels.csv` | Includes details about individual hotels and their categories |
| `dim_rooms.csv` | Describes different room types, capacities, and rates |
| `fact_aggregated_bookings.csv` | Aggregated data of bookings and capacity utilization |
| `fact_bookings.csv` | Detailed transactional booking data |

---

### ⚙️ Methodology
1. **Data Import & Exploration**
   - Imported all CSV datasets into Pandas DataFrames.
   - Explored data structure, null values, and duplicates.

2. **Data Cleaning**
   - Handled missing values and data inconsistencies.
   - Validated data integrity across dimensions and fact tables.

3. **Exploratory Data Analysis (EDA)**
   - Evaluated bookings vs. capacity trends.
   - Identified records with `successful_bookings > capacity`.
   - Analyzed booking success rate and platform performance.

4. **Visualization**
   - Created **pie charts** and **bar plots** using `Matplotlib` and `Seaborn` for:
     - Revenue realized per booking platform  
     - Property-wise and category-wise performance

5. **Insights Extraction**
   - Determined top-performing hotels and platforms.
   - Highlighted overbooking trends and potential operational inefficiencies.

---

### 💡 Key Insights
- Some properties experience **bookings exceeding capacity**, suggesting the need for tighter inventory control.  
- The **revenue distribution across booking platforms** is uneven, highlighting potential marketing optimization areas.  
- **Occupancy rates** vary significantly by region and hotel type, revealing demand clusters.

---

### 🧠 Technologies Used
- **Python** (Pandas, NumPy, Matplotlib, Seaborn)
- **Jupyter Notebook**
- **Excel/CSV Data Sources**

---

b.com/<your-username>/Hospitality_Domain.git

