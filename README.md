![Image](https://github.com/user-attachments/assets/b8dc5a83-ec08-4d09-b405-bc635418514c)

# TTC Delay Time Data Analytics Report (2014–2024)🚌

This project analyzes **Toronto Transit Commission (TTC)** bus delays from 2014 to 2024 using data analytics and machine learning to uncover delay patterns, identify contributing factors, and build predictive models. The goal is to improve service reliability and support data-driven decision-making for public transit operations.

## 🌟 Project Overview

This urban analytics project explores **104,988+ TTC bus delay records** (2014–2024) to:

- Identify root causes and high-delay locations
- Train predictive models to estimate delay durations
- Visualize operational insights with an interactive **Power BI dashboard**
- Suggest data-driven strategies for delay mitigation

## 🔍 Key Features

- **Data Cleaning & Preparation**: Handled missing values, type conversions, feature scaling, and label encoding 
 
- **Exploratory Data Analysis (EDA)**: 
  - Top causes: mechanical (40%) & operator-related (25%)  
  - Rush-hour & weekend spikes
  - Kennedy & Kipling as delay hotspots
- **Machine Learning Models**:
  - Decision Tree Regressor  
  - K-Nearest Neighbors (KNN)  
  - Random Forest Regressor  
  - AdaBoost Regressor  
  - XGBoost Regressor ✅ (Best Performance with 94.95% accuracy)
- **Feature Engineering**: Time extraction, categorical encoding, interaction terms
- **Deployment Ready**: Flask/FastAPI compatible; cloud deployment plan outlined
- **Interactive Power BI Dashboard**: Real-time visuals of patterns, trends, and hotspots


## 📈 Model Performance

| Model            | Accuracy |
|------------------|----------|
| Decision Tree    | 85.23%   |
| Random Forest    | 94.02%   |
| K Neighbours     | 87.71%   |
| AdaBoost         | 72.95%   |
| **XGBoost** ✅     | **94.95%** |

- **Best Model**: XGBoost
- **Accuracy**: 94.95%
- **Top Predictive Features**: Incident Type, Time of Day, Location, and Route
- The XGBoost Regressor outperformed other models with the lowest MAE (1.92) and highest R² Score (0.81).

## 📊 Power BI Dashboard (Visual Analytics)

This project includes a professional [**Power BI dashboard**](https://github.com/vihar023/TTC-Delay-Time-Data-Analytics-Report-2014-2024-.git) for interactive exploration of TTC delay patterns.

📌 Interactive dashboard includes:
  - Home Page
  - Navigation Panel (Selection Page)
  - Data Exploration and Instruction:
  - **Core Report Sections**
    - Bus Delay Time Analytics
    - Streetcar Delay Time Analytics
    - Subway Delay Time Analytics
  - **Analysis & Comparison Sections**
    - Summary
    - Comparison
    - Bar Race Visualizations

## 🏙️ Use Cases

This project can enhance public transport operations and city planning by:

- 🧠 Predicting delays and preemptively alerting dispatch teams
- 🛠️ Informing maintenance scheduling and training
- 📍 Optimizing resource allocation at high-risk stations
- 📲 Supporting future delay-tracking applications

## 🛠️ Tech Stack

- **Language**: Python (Jupyter Notebook)
- **Libraries**: pandas, NumPy, scikit-learn, seaborn, matplotlib, XGBoost
- **Visualization**: Power BI
- **Deployment**: Flask, FastAPI (for future integration), MLflow, AWS/Azure
- **Version Control**: GitHub
- **Data Source**: [Open Toronto Data Portal - TTC Delay Data](https://open.toronto.ca/dataset/ttc-bus-delay-data)

## 📎 Reports

A detailed project report is included in [Toronto Transit Commission Delay Time Data Analytics Report (2014–2024)](https://open.toronto.ca/dataset/ttc-bus-delay-data), covering methodology, model performance, results, and recommendations.
