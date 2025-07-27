# **Comprehensive Air Quality Analysis in Indian Cities**

This project provides an in-depth analysis of **Air Quality Index (AQI)** data across major Indian cities using **Python**. It identifies pollution trends, seasonal variations, hourly patterns, and pollutant contributions, aiming to provide actionable insights.

We used two datasets:
- **city_day.csv** – Daily AQI data for multiple cities
- **city_hour.csv** – Hourly AQI data for granular analysis

The objective is to help policymakers, researchers, and environmentalists understand pollution dynamics in India.

---

## **🔍 Detailed Process with Explanation**

### ✅ **Daily Data Analysis**
1. **Top 10 Polluted Cities** – Calculated average AQI per city and visualized the most polluted ones.
   ![Top 10 Polluted Cities](Top%2010%20Cities%20by%20Average%20AQI.png)

2. **Yearly AQI Trend** – Analyzed how AQI changed over the years using line plots.
   ![Yearly AQI Trend](https://github.com/hackeR200364/aqi_data_analysis/blob/main/Yearly%20Trend%20of%20AQI.png)

3. **Seasonal Impact** – Used monthly boxplots to highlight seasonal changes, especially during winter.
   ![Monthly AQI Boxplot](https://github.com/hackeR200364/aqi_data_analysis/blob/main/Air%20Quality%20Index%20by%20Month.png)

4. **AQI Bucket Distribution** – Visualized AQI category distribution (Good, Moderate, Poor, etc.).
   ![AQI Buckets](https://github.com/hackeR200364/aqi_data_analysis/blob/main/Distribution%20of%20AQI%20Bucket.png)

5. **City-Year Heatmap** – Compared AQI across cities over different years.
   ![City-Year Heatmap](https://github.com/hackeR200364/aqi_data_analysis/blob/main/Average%20AQI%20by%20City%20and%20Year.png)

6. **Pollutant Impact Analysis** – Bar chart showing average concentrations of PM2.5, PM10, NO₂, SO₂, O₃, CO.
   ![Pollutant Means](https://github.com/hackeR200364/aqi_data_analysis/blob/main/Mean%20of%20Pollutants.png)

7. **Rolling Average Trend** – 30-day rolling average to smooth daily fluctuations for better visualization.
   ![Rolling Average - Delhi](https://github.com/hackeR200364/aqi_data_analysis/blob/main/Delhi%20AQI%20with%2030-Day%20Rolling%20Average.png)  
   ![Rolling Average - Mumbai](https://github.com/hackeR200364/aqi_data_analysis/blob/main/Mumbai%20AQI%20with%2030-Day%20Rolling%20Average.png)
   ![Rolling Average - Kolkata](https://github.com/hackeR200364/aqi_data_analysis/blob/main/Kolkata%20AQI%20with%2030-Day%20Rolling%20Average.png)  
   ![Rolling Average - Chennai](https://github.com/hackeR200364/aqi_data_analysis/blob/main/Chennai%20AQI%20with%2030-Day%20Rolling%20Average.png)  
   ![Rolling Average - Bengaluru](https://github.com/hackeR200364/aqi_data_analysis/blob/main/Bengalore%20AQI%20with%2030-Day%20Rolling%20Average.png)

### ✅ **Hourly Data Analysis**
1. **Hourly AQI Patterns** – Studied AQI trends across different hours for each city.  
   ![Hourly AQI - Delhi](https://github.com/hackeR200364/aqi_data_analysis/blob/main/Hourly%20Average%20AQI%20in%20Delhi.png)  
   ![Hourly AQI - Mumbai](https://github.com/hackeR200364/aqi_data_analysis/blob/main/Hourly%20Average%20AQI%20in%20Mumbai.png)  
   ![Hourly AQI - Kolkata](https://github.com/hackeR200364/aqi_data_analysis/blob/main/Hourly%20Average%20AQI%20in%20Kolkata.png)  
   ![Hourly AQI - Chennai](https://github.com/hackeR200364/aqi_data_analysis/blob/main/Hourly%20Average%20AQI%20in%20Chennai.png)  
   ![Hourly AQI - Bengaluru](https://github.com/hackeR200364/aqi_data_analysis/blob/main/Hourly%20Average%20AQI%20in%20Bangalore.png)

2. **Top 5 Cities Hourly Comparison** – Compared AQI patterns of the most polluted cities by hour.
   ![Top Cities Hourly](https://github.com/hackeR200364/aqi_data_analysis/blob/main/Hourly%20AQI%20Pattern%20-%20Top%205%20Cities.png)

3. **Month vs Hour Heatmap** – Showed seasonal + hourly combined effect.
   ![Month-Hour Heatmap](https://github.com/hackeR200364/aqi_data_analysis/blob/main/Month%20vs%20Hour%20AQI%20Heatmap.png)

---

## **📌 Key Insights**
- **Delhi, Lucknow, and Patna** rank highest in pollution levels.
- **Winter months** (Nov–Jan) have the worst AQI due to stubble burning, low wind speed, and temperature inversion.
- AQI peaks during **morning (6–10 AM)** and **evening (6–9 PM)** traffic hours.
- **Night AQI > Day AQI** because pollutants remain trapped due to low wind movement.
- **PM2.5 and PM10** are the major contributors, strongly correlating with AQI.

---

## **🛠️ Tech Stack**
- **Language:** Python
- **Libraries:** Pandas, Matplotlib, Seaborn

---

## **📊 Visualizations Summary**
This project includes:
- **Bar charts** (Top polluted cities, Pollutant impact)
- **Line charts** (Yearly AQI, Hourly patterns)
- **Heatmaps** (City-Year, Month-Hour, Correlation)
- **Boxplots** (Monthly AQI distribution)
- **Rolling averages** for time series analysis

---

## **🚀 How to Run**
1. Clone the repository:
   ```bash
   git clone https://github.com/hackeR200364/aqi_data_analysis.git
   cd aqi_data_analysis
   ```
2. Install dependencies:
   ```bash
   pip install pandas matplotlib seaborn
   ```
3. Run the analysis scripts:
   ```bash
   python city_day_analysis.py
   python city_hour_analysis.py
   ```

---

## **📄 Blog Post**
🔗 [Read Full Analysis on Medium](https://medium.com/@rupamkarmakar1238/comprehensive-air-quality-analysis-in-indian-cities-daily-hourly-trends-cdbde06066d1)

---

## **🤝 Connect with Me**
- **LinkedIn:** [Rupam Karmakar](https://www.linkedin.com/in/rupam-karmakar-411157212/)
- **X (Twitter):** [@rupam7803](https://x.com/rupam7803)

---

### ⭐ **If you find this project useful, give it a star!**

---

## **🔮 Future Enhancements**
- Build AQI **prediction models using Machine Learning**.
- Develop **interactive dashboards** using Plotly or Power BI.
- Create a **real-time AQI monitoring system** with alerts.
