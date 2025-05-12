# 🚧 Prediction of Longwall Periodic Weighing and Local Fall Interval

This repository presents an analytical project aimed at understanding roof behaviour in longwall coal mining using machine learning-based visualization tools. Instead of building predictive models, this study uses ML methods to interpret complex shield pressure data and visualize zones prone to **periodic roof weighting** and **local roof falls**.

## 🧠 Project Objective

- **Enhance safety** in underground mining by identifying zones of potential roof failure.
- **Improve productivity** through insights into periodic weighting intervals.
- **Optimize resource use** by identifying stress-prone areas for better support layout.

## 📊 Methodology

### 1. Data Collection
- Data sourced from **Jhanjra Longwall Panel-8**, including:
  - Hydraulic shield pressures
  - Face advancement metrics
  - Geo-mining parameters

### 2. Data Processing
- Averaged pressure from dip and rise legs of each shield
- Aggregated shift-wise and daily pressure readings
- Calculated **Mean Load Density (MLD)** to assess stress per support unit

### 3. Data Analysis
- Generated **heatmaps** and **time-series plots** to visualize high-pressure zones
- Identified **periodic roof weighting** patterns
- Correlated shield pressure trends with recorded fall events using Python (`matplotlib`, `seaborn`)

## 📍 Key Insights

- **Mid-panel zones** showed the most intense and frequent periodic weighting.
- A **mainfall event** was recorded at 126 m face progress with a 54 m fall span.
- **20 periodic falls** were identified, typically occurring every 15–30 meters.
- **Heatmaps** effectively visualized roof stress build-up prior to events.

## 🔧 Technologies Used

- Python 3.x
- Pandas, NumPy
- Seaborn, Matplotlib
- Jupyter Notebooks (for visualization)

## 🏁 Conclusion

This project provides a solid foundation for **predictive modelling** and **real-time monitoring** in longwall mining operations. By visualizing shield pressure patterns and correlating them with roof events, it opens pathways for safer and more efficient mining practices.

## 👨‍🔬 Authors

- **Rahul Kumar Sharma** (20JE0749)  

Department of Mining Engineering  
Indian Institute of Technology (ISM), Dhanbad  

Supervisor: **Dr. Dondapati Gopi Krishna**

## 📚 References

See the `FINAL_YEAR_PROJECT_MAIN.docx` or the "References" section for a detailed bibliography of related works.

---




