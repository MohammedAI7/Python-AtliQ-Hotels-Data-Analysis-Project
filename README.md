
```markdown
# 🏨 AtliQ Hotels Data Analysis Project

## 📑 Table of Contents
- [Project Description](#project-description)  
- [Datasets Used](#datasets-used)  
- [Key Steps](#key-steps)  
- [Insights Generated](#insights-generated)  
- [Requirements](#requirements)  

---

## 📘 Project Description
The **AtliQ Hotels Data Analysis Project** aims to uncover booking patterns, occupancy rates, and revenue trends across various hotel properties and cities. By using Python tools such as **pandas** and **matplotlib**, the project processes, cleans, and analyzes data to deliver valuable insights that can inform operations, marketing strategies, and business decisions.

---

## 📂 Datasets Used
- `dim_date.csv`: Calendar information and type of day  
- `dim_hotels.csv`: Hotel property details (name, category, city)  
- `dim_rooms.csv`: Room class and category mapping  
- `fact_aggregated_bookings.csv`: Daily booking summary data  
- `fact_bookings.csv`: Detailed individual booking transactions  

---

## 🔧 Key Steps

1. **Data Import & Exploration**  
   Loaded all datasets and performed an initial analysis to understand shape, types, and distributions.

2. **Data Cleaning**  
   - Removed invalid records (e.g., negative guest counts, unrealistic revenue)
   - Treated missing values
   - Ensured consistency across datasets

3. **Data Transformation**  
   - Created new calculated fields (e.g., Occupancy %)
   - Merged relevant datasets to enable deeper insights

4. **Insights Generation**  
   Analyzed room-level, city-level, and platform-level trends to uncover actionable business insights.



## 📈 Insights Generated

- **🏨 Room Class Performance**  
  - Presidential class rooms had the highest average occupancy at **59.3%**  
  - Overall room classes ranged from **58% to 59%**

- **🌆 City Performance**  
  - **Delhi** recorded the highest average occupancy rate at **61.6%**  
  - **Mumbai** generated the highest total revenue: **₹668,569,251**

- **📅 Booking Trends**  
  - **Weekends** had a significantly higher average occupancy (**72.4%**)  
  - **Weekdays** trailed at **50.9%**



## 💻 Requirements

- Python 3.x  
- pandas  
- numpy  
- matplotlib  



