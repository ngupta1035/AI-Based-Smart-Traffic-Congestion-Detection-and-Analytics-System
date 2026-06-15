# 🚦 AI-Based Smart Traffic Congestion Detection and Analytics System

## Overview

Traffic congestion is one of the major challenges faced by modern cities, resulting in increased travel time, fuel consumption, pollution, and economic losses. This project presents an AI-powered Traffic Congestion Detection and Analytics System that leverages Computer Vision and Deep Learning to automatically monitor road traffic conditions from video feeds.

Using the YOLOv8 object detection model, the system detects and classifies vehicles in real time, analyzes traffic density, calculates congestion scores, categorizes traffic conditions, and generates interactive dashboards and reports for traffic monitoring and decision-making.

---

## Problem Statement

Traditional traffic monitoring systems rely heavily on manual observation or expensive sensor infrastructure. These approaches are often inefficient, costly, and difficult to scale.

The objective of this project is to develop an intelligent and automated traffic analytics solution capable of:

- Detecting vehicles from traffic video streams
- Measuring traffic density
- Estimating congestion levels
- Generating analytical reports
- Providing traffic management recommendations

---

## Key Features

### Vehicle Detection and Classification
Detects multiple vehicle categories using YOLOv8:

- Cars
- Motorcycles
- Buses
- Trucks
- Bicycles

### Traffic Density Analysis

Computes road occupancy using weighted vehicle density calculations.

### Congestion Scoring

Generates dynamic congestion scores ranging from:

- Free Flow
- Light Traffic
- Moderate Traffic
- Heavy Traffic
- Severe Traffic

### Interactive Dashboard

Automatically creates an HTML analytics dashboard containing:

- Congestion score trends
- Vehicle count trends
- Vehicle composition analysis
- Time-period traffic analysis
- Traffic distribution statistics
- Mitigation recommendations

### Automated Reporting

Exports:

- Traffic analytics dashboard
- CSV reports
- Annotated traffic videos

---

## System Architecture

Traffic Video Input
↓
YOLOv8 Vehicle Detection
↓
Vehicle Classification
↓
Density Calculation
↓
Congestion Scoring
↓
Traffic Analytics Engine
↓
Dashboard & Report Generation

---

## Technologies Used

| Category | Technologies |
|-----------|-------------|
| Programming Language | Python |
| Deep Learning | YOLOv8 |
| Computer Vision | OpenCV |
| Data Analysis | Pandas, NumPy |
| Visualization | HTML, Chart.js |
| Development Environment | Google Colab |

---

## Workflow

1. Upload traffic video.
2. Extract frames from video.
3. Detect vehicles using YOLOv8.
4. Classify detected vehicles.
5. Calculate traffic density.
6. Generate congestion score.
7. Categorize traffic severity level.
8. Produce analytics dashboard.
9. Export reports and annotated video.

---

## Results

The system successfully:

✅ Detects vehicles in traffic videos

✅ Calculates traffic congestion levels

✅ Generates real-time traffic analytics

✅ Produces visual dashboards for decision-making

✅ Provides congestion mitigation recommendations

---

## Sample Dashboard Metrics

- Average Congestion Score
- Peak Vehicle Count
- Dominant Traffic Condition
- Vehicle Composition Distribution
- Congestion Timeline Analysis
- Time Period Breakdown
- Traffic Management Recommendations

---

## Future Enhancements

- Real-time CCTV integration
- Multi-camera traffic monitoring
- Traffic prediction using time-series forecasting
- Emergency vehicle prioritization
- Smart traffic signal optimization
- Cloud deployment for city-scale monitoring

---

## Applications

- Smart Cities
- Traffic Management Centers
- Urban Planning
- Transportation Analytics
- Highway Monitoring Systems
- Intelligent Transportation Systems (ITS)

---

## Author

**Narayani Gupta**

B.E. Artificial Intelligence & Data Science

Dr. D. Y. Patil Institute of Technology, Pune

GitHub: https://github.com/ngupta1035

LinkedIn: https://linkedin.com/in/narayani-gupta

---

## Project Highlights

✔ Computer Vision

✔ Deep Learning

✔ YOLOv8 Object Detection

✔ Traffic Analytics

✔ Data Visualization

✔ Dashboard Development

✔ Smart City Applications
