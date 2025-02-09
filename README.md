# Fleet-Management-System-Python-Based
A Fleet Management System (FMS) is a comprehensive software and hardware solution used by organizations to manage and optimize their fleet of vehicles. This system is commonly used in industries where a large number of vehicles are essential for operations, such as logistics, transportation, delivery services, construction, and more. 

# Fleet Management System (Python-Based) 🚚<br>
A Python-based Fleet Logistics Management System designed to optimize vehicle tracking, route planning, and resource allocation for efficient logistics operations.<br>

### 🚀 Project Overview<br>
Objective: Develop an intelligent system for managing fleet operations, reducing costs, and improving efficiency.<br>
Dataset: Simulated or real-world fleet data containing vehicle details, route history, fuel consumption, driver logs, and delivery schedules.<br>

**Key Features:<br>**
✅ Vehicle Tracking & Route Optimization using machine learning.<br>
✅ Fuel Consumption Analysis to improve cost efficiency.<br>
✅ Predictive Maintenance using time-series forecasting.<br>
✅ Driver Performance Monitoring based on trip data.<br>

### 🏗 Object-Oriented Design (Parent & Child Classes)
The system is structured using Object-Oriented Programming (OOP) principles.<br>

### UML diagram of all classes<br>
![image](https://github.com/user-attachments/assets/ed94b1d7-2f9a-45d9-ba8e-9c41160940b6)
![image](https://github.com/user-attachments/assets/39a13e63-2d34-434b-85dc-9338588f8b34)
![image](https://github.com/user-attachments/assets/af8d2566-4cff-4ed8-848d-e702785a54d9)<br>

**1️⃣ Parent Class: VehicleFleet**<br>
The base class for managing the overall fleet of vehicles.<br>

**2️⃣ Child Class: Truck (Inherits from VehicleFleet)**<br>
Handles cargo trucks, including capacity and fuel efficiency.<br>

**3️⃣ Child Class: ServiceTruck (Inherits from Truck)**<br>
Handles maintenance and repair trucks.<br>

**4️⃣ Child Class: ScheduledRoute (Manages Route Assignments for Trucks)**<br>
Handles scheduled routes, distances, and time estimations.<br>

### 🔧 Installation & Requirements<br>

**1️⃣ Setup Environment**<br>
pip install -r requirements.txt<br>

**2️⃣ Required Libraries**<br>
pandas – Data handling<br>
numpy – Numerical computations<br>
matplotlib & seaborn – Data visualization<br>
scikit-learn – Machine learning models<br>
geopy – Distance and geolocation calculations<br>
networkx – Graph-based route optimization<br>

### 📊 Data Preprocessing & Analysis<br>
Data Cleaning: Handling missing values, normalizing numerical fields.<br>
Feature Engineering: Extracting key attributes for logistic insights.<br>
Visualization:<br>
import seaborn as sns<br>
import matplotlib.pyplot as plt<br>
plt.figure(figsize=(12,6))<br>
sns.histplot(df["fuel_consumption"], kde=True, bins=30)<br>
plt.title("Fuel Consumption Distribution")<br>
plt.show()<br>

### 🚗 Route Optimization & Cost Reduction<br>
Graph-based Shortest Path Calculation using Dijkstra’s Algorithm.<br>
Dynamic Route Optimization for real-time traffic adjustments.<br>
Fuel Efficiency Modeling based on road conditions and vehicle load.<br>

### 🤖 Machine Learning for Predictive Maintenance<br>
Time-Series Forecasting for vehicle breakdown prediction.<br>
Classification Models for detecting high-risk vehicles based on past failures.<br>
Anomaly Detection in fuel consumption for fraud prevention.<br>

### 📈 Performance Evaluation<br>
Accuracy Metrics: RMSE, MAE, F1-score for model performance.<br>
Dashboard Visualization using Plotly / Dash / Streamlit.<br>

### 📌 Future Enhancements<br>
🔹 Integrate GPS API for real-time tracking.<br>
🔹 Develop a Web App using Flask or Django for easy fleet monitoring.<br>
🔹 Incorporate IoT sensors for real-time vehicle health tracking.<br>

### 🤝 Contributing<br>
Feel free to fork this repo, enhance the system, and submit pull requests! 🚀<br>

### 📜 License<br>
This project is MIT Licensed – free to use and modify.<br>



