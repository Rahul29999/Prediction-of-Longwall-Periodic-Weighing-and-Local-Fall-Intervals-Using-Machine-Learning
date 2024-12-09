# **Prediction of Longwall Periodic Weighing and Local Fall Intervals Using Machine Learning**

## 📌 **Project Overview**

This project introduces a machine learning-based system to predict critical events in **longwall mining** operations, such as periodic weighing and local roof fall intervals. By leveraging historical and real-time geo-mining data, the predictive model aims to enhance safety, minimize disruptions, and optimize mining processes.

---

## 🚀 **Features**

- **Data-Driven Prediction**: Utilizes geo-mining data, including periodic weighing intervals, shield leg pressures, and geological characteristics, to forecast events.  
- **Real-Time Monitoring**: Integrates with mining control systems for real-time data analysis and alert generation.  
- **Machine Learning Models**: Implements advanced algorithms like Random Forest, Gradient Boosting Machines, and Artificial Neural Networks for predictive accuracy.  
- **Enhanced Operational Safety**: Proactively identifies risks, enabling preemptive safety measures.  

---

## 🔧 **Methodology**

### **1. Data Collection**
Data is sourced from sensors, geological surveys, and historical logs, focusing on key parameters:
- **Periodic Weighting Interval (Lp)**: Distance between consecutive roof weighings.
- **Time Interval (Tp)**: Time between weighings.
- **Shield Leg Pressure**: Measurements of roof support stress.

### **2. Data Preprocessing**
- **Missing Value Imputation**: Handled using mean and regression techniques.
- **Feature Engineering**: Created interaction terms between variables like overburden thickness and mining depth.
- **Normalization**: Ensured consistency across numerical features.

### **3. Model Development**
Implemented and compared multiple machine learning models:
- **Random Forest**
- **Gradient Boosting Machines (GBM)**
- **Artificial Neural Networks (ANNs)**

### **4. Model Evaluation**
Used metrics like:
- **Root Mean Squared Error (RMSE)**
- **Mean Absolute Error (MAE)**
- **Precision, Recall, and F1-score** for classification tasks.

### **5. Real-Time Deployment**
- Integrated with control systems for continuous monitoring of geo-mining conditions.
- Deployed an alert system to warn against impending roof falls or excessive loads.

---

## 📊 **Results**

### **Performance Metrics**
The predictive models were evaluated as follows:

| **Metric**         | **Value**   |  
|---------------------|-------------|  
| **RMSE**           | 12.5        |  
| **MAE**            | 9.3         |  
| **R² (Accuracy)**  | 92.7%       |  
| **F1-Score (Fall)**| 0.89        |  

### **Key Insights**
1. The **Random Forest model** achieved the highest accuracy in predicting periodic weighing intervals.
2. ANNs demonstrated strong performance for local roof fall classification due to their ability to handle complex, non-linear relationships.
3. Real-time monitoring improved operational safety and reduced the response time to adverse conditions.

---

## ✅ **Conclusion**

### **Key Achievements**
- Successfully developed and deployed a machine learning model to predict periodic weighing and roof fall intervals.  
- Enhanced safety and productivity in longwall mining operations through real-time alerts and actionable insights.  

### **Practical Impact**
- Reduced downtime and operational costs by predicting events in advance.  
- Improved resource allocation and worker safety with proactive measures.  

---

## 🔮 **Future Scope**

1. **Data Expansion**: Incorporate more diverse datasets from different mines for improved generalizability.  
2. **Hybrid Modeling**: Combine ANN and ensemble models to leverage the strengths of both approaches.  
3. **Dynamic Learning**: Enable models to adapt continuously with real-time feedback loops.  

---

## 🙏 **Acknowledgments**

This project was conducted under the guidance of **Dr. Dondapati Gopi Krishna**, Department of Mining Engineering, IIT (ISM) Dhanbad.  
Special thanks to the mining operations team for providing essential data and resources.  

**Contributor**:  
- **Rahul Kumar Sharma**  
  B.Tech (Mining Engineering), IIT (ISM) Dhanbad  

---

## 📚 **References**

1. Zhao, X., Zhang, L., & Li, Z. (2022). Predicting roof falls in longwall mining using deep learning methods.  
2. Zhang, Y., Wang, X., & Liu, P. (2021). Feature engineering for prediction in geo-mining operations.  
3. Gao, T., Zhang, J., & Li, L. (2022). Robust prediction of mining risks using ensemble learning algorithms.  

