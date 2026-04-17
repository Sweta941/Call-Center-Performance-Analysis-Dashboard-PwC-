<div align="center">

# 📞 Call Center Analysis Dashboard

<img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" />
<img src="https://img.shields.io/badge/DAX-0078D4?style=for-the-badge&logo=microsoft&logoColor=white" />
<img src="https://img.shields.io/badge/Data%20Modeling-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white" />
<img src="https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge" />

<br/>

> An end-to-end Power BI report that transforms raw call center logs into actionable intelligence — tracking agent performance, resolution trends, and customer satisfaction across time.

</div>

---
![Page 1 - Operations Overview](https://github.com/Sweta941/Call-Center-Performance-Analysis-Dashboard-PwC-/blob/cc92492d375e089f8ce388b0e6c76f2aa06cc1e9/Dashboard%20Page%20-%201.png)


![Page 2 - Agent Performance](https://github.com/Sweta941/Call-Center-Performance-Analysis-Dashboard-PwC-/blob/95c30333575b5c37df184793c211f4864e30f125/Dashboard%20Page%20-%202.png)

---

## 🗺️ Table of Contents

- [Project Background](#-project-background)
- [Dashboard Pages](#-dashboard-pages)
- [Data Model](#-data-model)
- [Key Metrics & KPIs](#-key-metrics--kpis)
- [Insights & Findings](#-insights--findings)
- [Tools & Skills](#-tools--skills)

---

## 📌 Project Background

Call centers generate enormous volumes of data daily, yet many teams still rely on manual reporting to track performance. This project builds a fully interactive Power BI dashboard to give managers a real-time view of operational health — from how quickly calls are being answered, to which agents consistently resolve cases and which topics drive the highest call volumes.

The report is structured around two perspectives:
- **Operations Overview** — the big picture for management
- **Agent Performance** — the granular detail needed for coaching and optimization

---

## 📊 Dashboard Pages

### Page 1 · Operations Overview

The executive-facing page. Seven KPI cards deliver an instant health check, with full drill-down capability through interactive slicers.

```
Slicers: Agent  |  Topic  |  Date Range
```

| Visual Type | Title | What It Shows |
|---|---|---|
| 🃏 KPI Cards (×7) | Total Calls, Calls Answered, Calls Unanswered, Avg Speed of Answer, Resolved Cases, Unresolved Cases, Agent Count | Top-line operational snapshot |
| 🍩 Donut Chart | Calls Answered (Y/N) Analysis | Answered vs. missed call split |
| 🍩 Donut Chart | Resolved & Unresolved Cases | Resolution rate at a glance |
| 🌡️ Gauge | Average Satisfaction Rating | Customer sentiment score |
| 🗺️ Treemap | Number of Calls by Topic | Volume distribution across issue categories |
| 📊 Column Chart | Calls & Resolved Cases by Month | Month-over-month trend analysis |
| 📋 Pivot Table | Agent Statistics | Per-agent breakdown: calls answered, resolved, satisfaction, avg speed |

---

### Page 2 · Agent Performance Deep Dive

The operations-facing page. Built for team leads who need to compare agents side-by-side and spot performance gaps.

```
Slicers: Month  |  Day of Week
```

| Visual Type | Title | What It Shows |
|---|---|---|
| 📊 Column Chart | Calls by Topic (Answered / Resolved / Unresolved) | Topic-level resolution breakdown |
| 🍩 Donut Chart | Ratio of Calls Answered to Resolved Cases | How effectively answered calls get closed |
| 📈 Area Chart | Avg Speed of Answer by Agent | Response time comparison across the team |
| 📊 Clustered Column Chart | Calls Answered vs. Unanswered by Agent | Who is picking up — and who isn't |

---

## 🗂️ Data Model

The report uses a clean star schema with two tables:

```
Call_Center (Fact)                    Calendar (Dimension)
──────────────────────                ──────────────────────
Call ID                      ◄────── Date
Agent                                 Month Name
Topic                                 WeekDay
Answered (Y/N)
Speed of Answer (seconds)
Satisfaction Rating
Resolved (Y/N)

── Measures ──────────────
Calls Received
Calls Answered
Calls Unanswered
Resolved Cases
Unresolved Cases
Avg Speed of Answer
```

---

## 📐 Key Metrics & KPIs

| Metric | Description |
|---|---|
| **Total Calls** | Overall volume of inbound calls received |
| **Answer Rate** | % of calls successfully picked up by an agent |
| **Resolution Rate** | % of answered calls that were fully resolved |
| **Avg Speed of Answer** | Mean time in seconds before a call is connected |
| **Satisfaction Rating** | Average customer-provided score per interaction |
| **Unresolved Cases** | Calls answered but not resolved — a key quality signal |

---

## 💡 Insights & Findings

- 📅 **Monthly trends** reveal whether call volume spikes are being absorbed by the team or causing drop-off in answer and resolution rates
- 🧑‍💼 **Agent-level data** in the pivot table makes it easy to identify top performers and flag agents who may benefit from additional coaching
- 📂 **Topic analysis** highlights recurring issue categories that could be addressed through self-service resources or FAQ improvements
- ⏱️ **Speed of answer by agent** surfaces workload imbalances — some agents may be handling a disproportionate share of incoming volume
- 📉 **Unresolved cases** are tracked separately from unanswered calls, ensuring management can distinguish between access failures and quality failures

---

## 🛠️ Tools & Skills

| Category | Details |
|---|---|
| **BI Tool** | Microsoft Power BI Desktop |
| **Query Language** | DAX (Data Analysis Expressions) |
| **Data Modeling** | Star schema, calculated columns & measures |
| **Report Design** | Solar theme, multi-page layout, interactive slicers |
| **Analytical Skills** | KPI design, operational analytics, agent performance benchmarking |

---

## 👤 Author

**[Sweta Mehta]**  

Data Analyst

---

<div align="center">


*Built as part of a data analytics portfolio · Feel free to reach out with questions or feedback*

</div>
