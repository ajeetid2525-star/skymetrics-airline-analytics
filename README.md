# skymetrics-airline-analytics
Power BI analytics report analyzing 50K passengers across airline operations, revenue, bookings, and customer satisfaction to uncover growth and efficiency opportunities.
# ✈️ SkyMetrics — Airline Analytics Report

A comprehensive Power BI dashboard analyzing operations, revenue, passengers, and customer satisfaction across the global aviation industry — built for confident, data-backed decisions.

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![Status](https://img.shields.io/badge/status-active-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue)

---

## 📌 Overview

SkyMetrics brings together flight operations, revenue and booking trends, passenger demographics, and customer satisfaction into a single connected report. It's built to help airline stakeholders spot where the business is growing, where operations are breaking down, and where the customer experience needs attention — all backed by real numbers, not guesswork.

**Data period:** Jan 2024 – Dec 2025 · **Total passengers:** 50K · **Total revenue:** $54M

---

## 📊 Dashboard Preview

| Page | Preview |
|------|---------|
| Cover Page | `images/00_cover.png` |
| Executive Overview | `images/01_executive_overview.png` |
| Passenger Insights | `images/02_passenger_insights.png` |
| Revenue & Booking Analysis | `images/03_revenue_booking.png` |
| Flight Operations | `images/04_flight_operations.png` |
| Customer Satisfaction | `images/05_customer_satisfaction.png` |
| Executive Summary & Recommendations | `images/06_summary_recommendations.png` |

> Add your exported screenshots to an `images/` folder and reference them above with `![Executive Overview](images/01_executive_overview.png)` so they render on the repo page.

---

## 🧭 Report Pages

### Cover Page
Introduces the report, its scope, and the five core analysis areas: Executive Overview, Customer Satisfaction, Flight Operations, Revenue & Booking, and Passenger Insights.

### 01 · Executive Overview
Business at a glance — growth, revenue leaders, and operational health.
- Total passengers, total revenue, average fare, average delay, average satisfaction score, on-time %
- Monthly passenger trend and revenue by airline
- Top 5 departure airports
- Class distribution and flight status breakdown
- Filters: Airline, Class, Date Range

### 02 · Passenger Insights
Who flies with us — demographics, loyalty & booking behavior.
- Average age, gender split, loyalty membership rate
- Age group distribution and passenger count by airline
- Class vs. satisfaction comparison
- Booking channel by age group
- Filters: Gender, Airline

### 03 · Revenue & Booking Analysis
Where the company earns — fares, channels & payment trends.
- Total revenue, average/highest/lowest fare, total bookings
- Average fare by class and top revenue-generating routes
- Sales by booking channel, payment method, day of week, and quarter
- Filters: Booking Channel, Airline, Payment Method

### 04 · Flight Operations
How efficiently we fly — delays, on-time performance & routes.
- Average delay, maximum delay, on-time %, delayed/cancelled flight counts
- Average delay by month, airline, and route
- On-time flights by airline
- Passenger volume by delay category
- Filters: Airline, Status

### 05 · Customer Satisfaction
The experience behind the journey — ratings, comfort & loyalty.
- Average satisfaction score, % happy customers, loyalty members, average fare
- Satisfaction by airline, class, gender, and booking channel
- Delay vs. satisfaction relationship
- Filters: Airline, Class, Loyalty Member

### 06 · Executive Summary & Recommendations
The story across all five dashboards, condensed into key findings and next steps.

---

## 💡 Key Insights

| Metric | Value | Insight |
|---|---|---|
| Total passengers | 50K | Across all airlines and routes in the dataset |
| Total revenue | $54M | Generated from 50K bookings |
| Average fare | $1.07K | Highest fare $3.07K, lowest $25.37 |
| On-time performance | 80% | 8,938 flights delayed, 989 cancelled |
| Average delay | 24 minutes | March recorded the highest average delay |
| Average satisfaction | 3.01 / 5 | Economy class scores highest; First Class scores lowest despite highest fares |
| Loyalty members | 25K (50%) | Only 40% of customers report being happy — a retention risk |
| Busiest airport | DXB | 5,083 flights departed |
| Top airline by revenue & volume | SkyJet | Leads both passenger count and revenue |
| Most delay-prone airline | FlyFast | Highest average airline delay (~24 min) |
| Longest average delay routes | SIN → BLR, CCU → HYD | ~26 minute average delay |
| Top booking channels | Website & Mobile App | Together outsell Travel Agents |
| Strongest sales quarter | Q3 | Top quarter for revenue across the year |

---

## 🎯 Recommendations

1. **Target March & FlyFast delays** — audit scheduling and turnaround at DEL and on the SIN→BLR / CCU→HYD routes; build seasonal slack into March timetables
2. **Elevate Premium & First Class service** — investigate why the highest-paying cabins score lowest on satisfaction; review seating, crew service, and amenities
3. **Close the loyalty–satisfaction gap** — survey loyalty members directly; add tangible perks (upgrades, lounge access) tied to satisfaction recovery, not just tenure
4. **Replicate Q3 revenue drivers** — identify what made Q3 the top quarter (routes, fares, promotions) and test similar campaigns in Q1/Q2
5. **Grow digital, self-serve booking** — Website and Mobile App already lead Travel Agents; invest further to lower distribution cost and improve booking speed
6. **Benchmark against SkyJet & AeroNova** — SkyJet leads volume/revenue and AeroNova leads satisfaction; study both to raise performance fleet-wide

---

## 🛠️ Tools & Technologies

- **Power BI Desktop** — report building and DAX measures
- **Power Query** — data cleaning and transformation
- **DAX** — calculated measures for satisfaction scoring, delay analysis, and revenue breakdowns

---

## 📁 Repository Structure

```
skymetrics-airline-analytics/
├── skymetrics_airline_report.pbix     # Main Power BI report file
├── data/
│   └── dataset.csv                    # Source dataset
├── images/
│   ├── 00_cover.png
│   ├── 01_executive_overview.png
│   ├── 02_passenger_insights.png
│   ├── 03_revenue_booking.png
│   ├── 04_flight_operations.png
│   ├── 05_customer_satisfaction.png
│   └── 06_summary_recommendations.png
└── README.md
```

---

## 🚀 Getting Started

1. Clone this repository
```bash
   git clone https://github.com/<your-username>/skymetrics-airline-analytics.git
```
2. Open `skymetrics_airline_report.pbix` in **Power BI Desktop**
3. Use the filters on each page (Airline, Class, Date Range, Gender, Booking Channel, Payment Method, Status, Loyalty Member) to explore the data
4. Navigate between pages using the in-report navigation or page tabs

---

## 🔭 Future Improvements

- Add route-level profitability analysis
- Introduce predictive delay modeling by season and airport
- Publish to Power BI Service with scheduled data refresh
- Add a mobile-optimized report layout

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome. Feel free to check the [issues page](../../issues) or open a pull request.

---

## 📬 Contact

Questions or feedback? Open an issue in this repository or reach out directly.
