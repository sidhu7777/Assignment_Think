# **ThinkClock Battery Analysis Project**  

## **Project Overview**  
This project analyzes **Li-ion battery performance** using data from **NASA Battery Dataset**. The dataset contains multiple operational profiles, including **charge, discharge, and impedance measurements**, collected at various temperatures.  

### **Key Objectives**  
- **Monitor battery degradation** over repeated charge-discharge cycles.  
- **Analyze impedance data** using Electrochemical Impedance Spectroscopy (EIS).  
- **Predict Remaining Useful Life (RUL)** and state-of-health (SoH) of batteries.  

---

## **Data Source**  
The dataset used in this project is sourced from **NASA Battery Dataset** available on Kaggle:  
🔗 [NASA Battery Dataset](https://www.kaggle.com/datasets/patrickfleith/nasa-battery-dataset/data)  

### **Dataset Description:**  
- Batteries were cycled through charge-discharge operations under different conditions.  
- Impedance spectroscopy (EIS) was used to capture internal battery health.  
- Experiments continued until the batteries reached **End-of-Life (EOL)** conditions.  

---

## **Features & Implementation**  
✅ **Battery Aging Analysis** – Identify battery degradation patterns over cycles.  
✅ **Charge & Discharge Behavior** – Analyze capacity retention over time.  
✅ **EIS 3D Visualization** – Understand internal battery parameter changes using impedance data.  
✅ **Predictive Modeling** *(Future Work)* – Develop models to estimate Remaining Useful Life (RUL).  

---

## **Project Structure**  

```bash
📂 thinkclock-battery-analysis  
 ├── 📂 think_code                         # Contains Python scripts & logic  
 │    ├── new_assignment_think_clock.ipynb  # Jupyter Notebook with analysis  
 ├── 📄 README.md                          # Project Documentation  
