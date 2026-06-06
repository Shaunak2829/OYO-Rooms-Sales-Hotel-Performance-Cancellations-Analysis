# OYO-Rooms-Sales-Hotel-Performance-Cancellations-Analysis

# 🏨 OYO Rooms — Sales, Hotel Performance & Cancellations Analysis | Power BI Dashboard

## Short Description
A 3-page Power BI dashboard analyzing **41K bookings** and **₹242M in revenue** across OYO properties in 10 Indian cities — covering sales trends, hotel-level performance, room type revenue, and a dedicated cancellations analysis to identify where bookings are being lost.

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| **Power BI Desktop** | Dashboard development & visualization |
| **Power Query Editor** | Data cleaning & transformation |
| **DAX** | KPI measures & calculated columns |
| **`.pbix`** | Development file format |
| **`.png`** | Dashboard preview exports |

---

📂 Data Source

Platform: Synthetic dataset built for portfolio purposes
Scope: OYO hotel bookings across 10 Indian cities covering revenue, room types, payment methods, market segments, seasons, and cancellations
Data Modeling: Designed a Snowflake Schema with 1 central fact table and multiple dimension tables, establishing proper relationships across booking, hotel, room, city, and customer entities in Power BI

---

## ✨ Key Findings & Highlights

### 📊 Page 1 — Sales Overview
- Revenue: **₹242.13M** | Bookings: **41K** | Occupancy: **86.42%** | ADR: **₹2.36K** | RevPAR: **₹2.04K**
- **Monsoon is the highest revenue season at ₹66M**, followed by Winter (₹53M) — Summer and Spring lag at ₹36–37M
- **October peaks at ₹26M** while December drops to ₹15M — a **42% month-over-month revenue fall** in Q4
- **UPI dominates payments at ₹78M (32% of revenue)** — far ahead of Credit Card (₹57M) and Debit Card (₹45M)
- **Bangalore, Chennai, and Indore** consistently grow revenue every quarter, making them the most stable markets

### 🏨 Page 2 — Hotel Performance
- **OYO Grand Inn Vijay Nagar - 6 is the top hotel at ₹48.26L**, while the bottom 10 hotels earn ~₹30–33L each — a **~45% revenue gap** between top and bottom performers
- **OYO Townhouse leads all property types at ₹63M**, followed by Collection O (₹58M) — standard OYO brand earns only ₹46M
- **Maharashtra leads all states in revenue** across all room types, with Deluxe and Standard rooms contributing the most
- Bottom 10 hotels are concentrated in **Pune, Mumbai, Nagpur, and Indore** — these cities need property-level audits

### Page 3 — Cancellations Analysis
- **Online (2,597) and OTA (2,605) segments have the highest cancellations** — together accounting for over **5,200 cancelled bookings**
- **Standard rooms have the most cancellations at 2,383** — nearly **2.4x more than Luxury rooms (980)**
- **Indore leads city-wise cancellations at 965**, followed closely by Kanniyakumari (944) and Pune (911)
- Top 5 hotels by cancellations each average **~150 cancelled bookings** — a targeted retention fix here could recover significant revenue

---

## 💡 Recommendations
- **Address the December revenue drop** — a ₹11M fall from October to December signals a need for year-end promotional pricing or packages
- **Investigate OTA and Online cancellations** — 5,200+ cancellations from these two channels alone; reviewing cancellation policy and booking confirmation flow could significantly reduce losses
- **Upgrade or reposition Standard rooms** — highest cancellation category at 2,383; pricing, photos, or amenity gaps may be driving customers to cancel after booking
- **Focus retention efforts on Indore, Kanniyakumari, and Pune** — the top 3 cancellation cities; city-specific offers or flexible booking policies could help
- **Replicate top hotel strategies** — OYO Grand Inn Vijay Nagar earns 45% more than bottom performers; identifying what they do differently can lift underperforming properties

---

## 📸 Dashboard Preview

**Sales Overview**
![Sales Overview](https://github.com/Shaunak2829/OYO-Rooms-Sales-Hotel-Performance-Cancellations-Analysis/blob/main/Oyo%20sales%20overview.png)

**Hotel Performance**
![Hotel Performance](https://github.com/Shaunak2829/OYO-Rooms-Sales-Hotel-Performance-Cancellations-Analysis/blob/main/Hotel%20Performance.png)

**Cancellations Analysis**
![Cancellations](https://github.com/Shaunak2829/OYO-Rooms-Sales-Hotel-Performance-Cancellations-Analysis/blob/main/oyo%20Cancellations.png)

