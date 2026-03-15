# Flight Performance Dashboard — Power BI

![PowerBI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow?style=flat-square)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=flat-square)

> Interactive Power BI dashboard analyzing flight delays, cancellations, and airline performance — enabling data-driven operational insights across routes and airlines.

---

## Problem Statement

Airlines and airports generate massive volumes of operational data, but raw data alone doesn't drive decisions. This project transforms flight performance data into an interactive Power BI dashboard that surfaces delay trends, cancellation rates, and route-level performance — giving stakeholders a clear picture of operational efficiency.

---

## Dashboard Features

| Visual | Description |
|---|---|
| KPI Cards | Total flights, on-time count, delayed count, cancellation rate |
| Avg Delay by Airline | Bar chart comparing average departure/arrival delay per airline |
| Delay Trend Over Time | Line chart showing delay patterns across dates |
| Flight Count by Route | Top routes by volume |
| Cancellation % by Airline | Which airlines cancel most frequently |
| Overall Performance Summary | Airline and route efficiency overview |

---

## Key Insights

- Some airlines show consistently higher average delays across all routes
- Specific routes have disproportionately high cancellation rates
- Delay trends show clear weekly and seasonal patterns
- Strong correlation between departure delay and arrival delay across carriers

---

## Tech Stack

| Category | Tools |
|---|---|
| BI Tool | Microsoft Power BI Desktop |
| Data Modeling | Power BI data model |
| Calculated Metrics | DAX formulas |
| Data Source | CSV (flight dataset) |
| Optional Preprocessing | Python / PySpark |

---

## Dataset

| Column | Description |
|---|---|
| `FlightDate` | Date of flight |
| `Airline` | Airline name or code |
| `Origin` | Departure airport |
| `Destination` | Arrival airport |
| `DepDelay` | Departure delay (minutes) |
| `ArrDelay` | Arrival delay (minutes) |
| `Distance` | Route distance |
| `Cancelled` | Cancellation flag |

---

## How to Use

```
1. Download: Flights Performance Dashboard_task3.pbix from this repo
2. Open with: Microsoft Power BI Desktop (free download from Microsoft)
3. If dataset path changes:
   Home → Transform Data → Data Source Settings → Change Source
4. Click Refresh to update all visuals
```

---

## Project Structure

```
flight-performance-dashboard-powerbi/
│
├── Flights Performance Dashboard_task3.pbix    # Power BI dashboard file
└── README.md
```

---

## Screenshots

> Add a screenshot of your dashboard here — even a single image makes a huge difference for anyone viewing this repo.

![Dashboard Preview](assets/dashboard_preview.png)

---

## Key Learnings

- Building interactive dashboards with slicers, filters, and drill-throughs in Power BI
- Writing DAX measures for calculated KPIs (e.g., on-time rate, avg delay)
- Data modeling — relationships between fact and dimension tables
- Translating raw CSV data into business-ready visual insights

---

## Future Improvements

- [ ] Connect to a live data source for real-time flight updates
- [ ] Add drill-through pages for individual airline deep-dives
- [ ] Publish to Power BI Service for web-based sharing

---

## Author

**Thejal C Kotian**
[LinkedIn](https://linkedin.com/in/thejalckotian2003) · [GitHub](https://github.com/cthejal) · thejalck@gmail.com
