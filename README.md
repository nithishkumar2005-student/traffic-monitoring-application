# 🚦 Large-Scale Traffic Monitoring Application

A city-scale traffic monitoring and visualization system built using GPS bottleneck data for **Hyderabad city (inside ORR)**.

This application visualizes traffic congestion by simulating vehicle density across major junctions, signals, and landmarks using an interactive map.

---

## 📍 Project Overview

Urban traffic congestion is a major challenge in metropolitan cities.  
This project focuses on **monitoring and visualizing traffic congestion** across Hyderabad using structured GPS data.

The system highlights:
- High-traffic zones
- Congestion severity
- Vehicle density per area

---

## 🗺️ Region Covered

- **City:** Hyderabad  
- **Coverage:** Inside ORR  
- **Total Locations:** ~120 major traffic-prone areas  
- **Each location includes:**
  - Area Name  
  - Signal / Junction Name  
  - Key Landmark  
  - Latitude  
  - Longitude  

---

## 🚗 Traffic Simulation Logic

- Vehicles are **simulated (not real-time)**
- Vehicle count per area ranges from **100 to 500**
- Dense clustering represents traffic congestion
- Vehicles are generated close to junctions to resemble road traffic

---

## 📊 Features

- Interactive city-scale traffic map (5–10 km)
- Red zones indicate congestion areas
- Blue dots represent vehicles
- Area-wise vehicle count
- Stable and flicker-free dashboard
- CSV-driven (easy to update data)

---

## 🛠️ Tech Stack

- **Programming Language:** Python  
- **Framework:** Streamlit  
- **Libraries:** Pandas, NumPy  
- **Mapping:** Folium, OpenStreetMap  
- **Data Source:** CSV (GPS bottleneck data)

---

## 📂 Project Structure
traffic_app/
├── app.py
├── gps_data.csv
├── requirements.txt
├── README.md

To run this project 
1. python -m venv venv
venv\Scripts\activate

2.pip install streamlit pandas folium streamlit-folium scikit-learn

3.streamlit run app.py



