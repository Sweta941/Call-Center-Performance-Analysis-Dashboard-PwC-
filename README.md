# 📞 Call Center Analysis Dashboard

![Power BI](https://img.shields.io/badge/Data_Visualization-Power_BI-yellow)
![DAX](https://img.shields.io/badge/Analytics-DAX-blue)
![ETL](https://img.shields.io/badge/ETL-Power_Query-orange)

## 📋 Table of Contents
* [Executive Summary](#-executive-summary)
* [Dashboard Architecture](#%EF%B8%8F-dashboard-architecture)
* [Technical Deep Dive](#-technical-deep-dive)
* [Insights & KPIs](#-insights--kpis)
* [How to Deploy](#-how-to-deploy)

---

## 📊 Executive Summary
This Power BI project transforms raw call center logs into a strategic decision-making tool. By analyzing agent performance and call distributions, the dashboard enables management to optimize workforce allocation and improve customer satisfaction scores.

> [cite_start]**Note:** The underlying data model is built on a Star Schema for optimal performance and utilizes the **Solar** custom theme for enhanced visual clarity[cite: 3, 27].

---

## 🛠️ Dashboard Architecture

### 🗂️ Report Pages (Tabs)
1. **Performance Overview**: A high-level view of departmental KPIs and volume trends.
2. **Agent Analytics**: Granular tracking of individual agent efficiency and resolution rates.
3. **Customer Experience**: Analysis of satisfaction scores (CSAT) and abandonment rates.
4. **Volume Forecasting**: Visualizations of peak hours and days to assist in scheduling.

### ⚙️ Backend Components
* [cite_start]**Theme Configuration**: Utilizes the `Solar.json` and `CY23SU11.json` base themes for a professional UI.
* [cite_start]**Resource Assets**: Integrated custom branding via registered PNG resources.
* [cite_start]**Layout Engine**: Custom `DiagramLayout` and `Report/Layout` configurations to ensure mobile and desktop responsiveness[cite: 1, 27].

---

## 💻 Technical Deep Dive

### Data Modeling
[cite_start]The dashboard employs a robust **DataModel** with defined **SecurityBindings** to ensure role-based access control[cite: 4, 27]. 

### Key DAX Measures (Conceptual)
* **Average Handle Time (AHT)**: $\frac{\text{Total Talk Time} + \text{Total Hold Time} + \text{Total Wrap Time}}{\text{Total Calls Handled}}$
* **Service Level**: $\frac{\text{Calls Answered within } X \text{ Seconds}}{\text{Total Calls Received}}$
* **Abandonment Rate**: $\frac{\text{Abandoned Calls}}{\text{Total Calls Received}}$

### Data Transformation (Power Query)
* [cite_start]Cleaned and reshaped metadata and settings[cite: 1].
* [cite_start]Established connections between call logs, agent directories, and date tables.

---

## 📈 Insights & KPIs
* **Volume Analysis**: Identified peak call arrivals between **10:00 AM and 2:00 PM**, suggesting a shift in staffing requirements.
* **Agent Efficiency**: Highlighting top-tier agents with high **First Call Resolution (FCR)** rates.
* **Service Gaps**: Visualized correlation between high hold times and lower customer satisfaction scores.

---

## 🚀 How to Deploy

1. **Clone the Repository**:
   ```bash
   git clone [https://github.com/YourUsername/Call-Center-Analysis.git](https://github.com/YourUsername/Call-Center-Analysis.git)
