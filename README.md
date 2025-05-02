# 🚧 Accident Data Analysis and Safety Insight Dashboard

This project analyzes UK accident data to identify **high-risk locations**, **accident causes**, and **temporal trends** with the goal of uncovering **safety improvement insights**. It was developed as part of a data science internship task and fully implemented in **Google Colab** using **Python** and **Plotly** for interactivity.

---

## 📌 Objectives

- Identify **accident hotspots** using geographic mapping
- Analyze **severity trends** over time (hour, day)
- Investigate **causal factors** such as weather, road surface, and vehicle type
- Present the findings in an **interactive dashboard-like notebook**

---

## 🛠️ Tools & Libraries

- Python (Pandas, Plotly, NumPy)
- Google Colab
- Data Source: CSV file stored in Google Drive
- Output: Fully interactive visualizations via Plotly

---

## 📊 Dashboard Features

1. **Interactive Accident Hotspot Map**  
   - Latitude/Longitude-based map showing frequency & severity of accidents by district

2. **Hourly Accident Trends**  
   - Line chart showing peak hours for accidents

3. **Weekly Accident Patterns**  
   - Bar chart comparing accident frequency across weekdays

4. **Weather vs Severity Analysis**  
   - Stacked bar chart showing distribution of accident severity by weather conditions

5. **Top Vehicle Types in Accidents**  
   - Bar chart of the most involved vehicle types

6. **District-Level Summary Table**  
   - Table showing accident count and average severity per district

---

## 📁 Files

- `accident_analysis.ipynb`: Main Google Colab notebook with all code and visuals
- `location_summary.csv`, `hourly_trend.csv`, etc.: Processed data for visualizations
- `README.md`: Project documentation

---

## 📷 Sample Visuals

![accident_by_district](https://github.com/user-attachments/assets/8a81557d-929c-4b72-952b-ebfdf9739490)

---

## ✅ How to Use

1. Clone this repo or upload the notebook to your Google Drive
2. Mount Google Drive in Colab and ensure the dataset CSV is accessible
3. Run the notebook step by step
4. All insights and charts will be generated interactively

---

## 📌 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
