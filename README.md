#  Live Network Traffic Dashboard

## Overview
The **Live Network Traffic Dashboard** is an advanced real-time network monitoring and analysis tool built using **Python** and **Streamlit**. It provides deep insights into network activity, enabling users to track connections, detect anomalies, and analyze behavioral patterns with interactive visualizations.

---

##  Objectives
- Monitor live network connections in real-time  
- Analyze traffic patterns and system behavior  
- Detect anomalies and potential security threats  
- Provide detailed visual and statistical insights  
- Generate downloadable reports  

---

## Key Features

### Real-Time Monitoring
- Start/Stop live network tracking  
- Adjustable monitoring duration and intervals  
- Snapshot capture for instant analysis  

### Advanced Visualizations
- Protocol distribution  
- Traffic direction analysis  
- Process-level insights  
- Bandwidth usage trends  
- Correlation heatmaps  

### Machine Learning Integration
- **Isolation Forest** → Anomaly detection  
- **DBSCAN Clustering** → Behavioral grouping  

### Security Insights
- Detection of:
  - Port scanning activity  
  - Unusual port usage  
  - High outbound traffic (possible data exfiltration)  
  - Suspicious processes  
  - Burst and periodic traffic patterns  

### Geographical Analysis
- IP-based geolocation  
- Country and city-level connection tracking  
- Global network reach visualization  

### Behavioral Analysis
- Burst traffic detection  
- Periodic connection patterns  
- Connection clustering  

### Export Options
- Download data as **CSV**  
- Export full analysis report as **JSON**  

---

## Tech Stack

| Category | Tools Used |
|--------|-----------|
| Frontend | Streamlit |
| Backend | Python |
| Data Processing | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn, Altair |
| Machine Learning | Scikit-learn |
| Networking | psutil, socket |
| Geolocation | IP-API |

---

## Usage

1. Open the dashboard in your browser  
2. Set:
   - Monitoring duration  
   - Collection interval  
   - UI update interval  
3. Click **Start Monitoring**  
4. Explore:
   - Dashboard  
   - Raw Data  
   - Reports  
   - Security Insights  
   - Trends & Patterns  

---

## Dashboard Modules

- **Dashboard** → Visual summaries  
- **Raw Data** → Connection-level data  
- **Report** → Aggregated insights  
- **Security** → Threat detection  
- **Bandwidth** → Data transfer analysis  
- **Anomalies** → Suspicious activity  
- **Trends** → Process performance over time  
- **TCP Analysis** → Protocol-level deep dive  
- **Geography** → Location-based insights  
- **Behavior** → Pattern detection  
- **Statistics** → Advanced analytics  

---
## Limitations

- Geolocation depends on external API accuracy  
- High-frequency monitoring may impact performance  

---

