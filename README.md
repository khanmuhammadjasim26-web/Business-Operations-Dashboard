# 🏢 Business Operations & CTM Open Enquiries Dashboard (Power BI)

[![Power BI](https://img.shields.io/badge/Power_BI-Desktop-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)
[![DAX](https://img.shields.io/badge/DAX-Data_Analysis_Expressions-2563EB?style=for-the-badge)](https://learn.microsoft.com/en-us/dax/)
[![Excel](https://img.shields.io/badge/Excel-Source_Dataset-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)](https://office.com)
[![Dataset](https://img.shields.io/badge/Dataset-2%2C492_Enquiries-8B5CF6?style=for-the-badge)](https://github.com/khanmuhammadjasim26-web/Business-Operations-Dashboard)
[![Live Site](https://img.shields.io/badge/Live_Site-GitHub_Pages-000000?style=for-the-badge&logo=github)](https://khanmuhammadjasim26-web.github.io/Business-Operations-Dashboard/)

> **Project by Muhammad Jasim**  
> 🌐 **Live Web Showcase:** [https://khanmuhammadjasim26-web.github.io/Business-Operations-Dashboard/](https://khanmuhammadjasim26-web.github.io/Business-Operations-Dashboard/)

---

## 📌 Project Overview & Purpose

In Corporate Travel Management (CTM) and hospitality booking operations, booking failures, rate discrepancies, and system errors lead to open customer support enquiries that require rapid operational intervention.

This project delivers an **end-to-end Business Operations Dashboard** built in **Microsoft Power BI**. It analyzes **2,492 booking enquiries** logged across FreshDesk ticketing systems to track resolution lifecycles, diagnose root causes of booking failures across major hotel chains, evaluate agent workload & resolution efficiency, and drive operational performance improvements.

---

## 🎯 Key Business Objectives

1. **Enquiry Volume & Confirmation Rates:** Monitor overall enquiry inflow (`2,492` total tickets) and quantify overall booking conversion (`Total Confirmed` vs. `Not Confirmed`).
2. **Root-Cause Failure Diagnostics:** Categorize and track major drivers of booking failures, including **Technical Errors**, **Rate Changes**, **Offline Rates**, **Booking.com Rate discrepancies**, and **Room Type Availability**.
3. **Vendor & Hotel Chain Impact:** Pinpoint recurring booking failure hotspots across leading hotel chains (Travelodge, Holiday Inn, Premier Inn, Best Western, Park Plaza, Hampton by Hilton).
4. **Agent Resolution & Workload Performance:** Measure enquiry resolution throughput and contribution shares between operational support agents (**Mohd Jasim Khan** and **Aniket**).
5. **Operational Trend Monitoring:** Track recurring failure patterns over time and observe failure rate shifts across shift periods (SOD to EOD).

---

## 📊 Dashboard Architecture & Report Pages

The Power BI workbook (**`CTM Dashboard Open Enquiries.pbix`**) features 3 operational report pages:

```
CTM Dashboard Open Enquiries.pbix
├── 🏠 Page 1: Home (Executive Overview & Confirmation KPIs)
├── ⚡ Page 2: Action (Failure Breakdown & Chain Analysis)
└── 📋 Page 3: Detail (Recurring Trends & Timeframe Patterns)
```

### 🏠 Page 1: Home (Executive Overview)
* **High-Level KPIs:** Total Enquiries (`2,492`), Total Confirmed vs. Not Confirmed counts and percentages.
* **Agent Performance Cards:** Total enquiries resolved by **MJK** (Mohd Jasim Khan) and **Aniket**, along with percentage shares of total resolved volume.
* **Action Summary:** Visual distribution of action status across booking requests.

### ⚡ Page 2: Action (Failure Distribution & Hotspots)
* **Failure Reason Analysis:** Detailed volume breakdowns for Technical Errors, Rate Changes, and Offline Rates.
* **Hotel Chain Breakdown:** Booking error distribution across individual partner chains.
* **Interactive Slicers:** Dynamic filtering by Date, Agent, and Hotel Chain.

### 📋 Page 3: Detail (Trend & Timeframe Analysis)
* **Time-Series Analytics:** Recurring failure patterns over time and resolution progression.
* **Granular Records:** FreshDesk ticket tracking, CTM Booking References, and daily operational status.

---

## 📐 Data Architecture

### 📁 Source Dataset
* **File:** `Open Enquiries To Create Dashboard.xlsx`
* **Sheet:** `Open Enquiries` *(2,492 rows $\times$ 13 columns)*
* **Key Fields:** `Date`, `FreshDesk`, `CTM Booking Reference`, `Number of Bookings`, `Hotel Name`, `Hotel Chain`, `Reason of failure`, `Status`, `SOD`, `EOD`, `Agent Name`.

---

## 🧮 DAX Measures (`All Measures` Table)

A dedicated calculation table houses the business logic:

| # | Measure Name | Purpose |
| :-: | :--- | :--- |
| 1 | `Total Enquiries` | Overall count of customer booking enquiries |
| 2 | `Total Confirmed` | Count of successfully resolved & confirmed bookings |
| 3 | `% Total Confirmed` | Proportion of total enquiries confirmed |
| 4 | `Total Not Confirmed` | Count of unconfirmed or voided enquiries |
| 5 | `% total Not Confirmed` | Proportion of enquiries unconfirmed |
| 6 | `Total Enquiries resolved by MJK` | Enquiry volume resolved by Mohd Jasim Khan |
| 7 | `% resolved by MJK` | Percentage share of resolutions by MJK |
| 8 | `Total Enquiries resolved by Aniket` | Enquiry volume resolved by Aniket |
| 9 | `% resolved by Aniket` | Percentage share of resolutions by Aniket |

---

## 💡 Key Business Insights Discovered

* **Primary Failure Driver:** **Technical Errors (~49.8%)** account for the largest share of booking drop-offs, followed by **Rate Changes** and **Offline Rates**.
* **High-Volume Partners:** **Travelodge** and **Holiday Inn Express** represent the highest frequency of automated booking exceptions requiring manual agent intervention.
* **Agent Throughput:** Balanced operational distribution between frontline support agents ensuring comprehensive coverage of open FreshDesk tickets.

---

## 🛠️ How to Open and Refresh the Project

1. **Download the Project:**
   * Clone this repository or download **`CTM Dashboard Open Enquiries.pbix`** and **`Open Enquiries To Create Dashboard.xlsx`**.
2. **Open in Power BI Desktop:**
   * Launch **Power BI Desktop**.
   * Open `CTM Dashboard Open Enquiries.pbix`.
3. **Refresh Local Data Source Paths:**
   * Click **Home** &rarr; **Transform Data** &rarr; **Data source settings**.
   * Click **Change Source** and select the Excel file on your machine.
   * Click **Close & Apply** to refresh all visuals.

---

## 👨‍💻 Author & Contributions

* **Created by:** [Muhammad Jasim](https://github.com/khanmuhammadjasim26-web)
* **Repository:** [https://github.com/khanmuhammadjasim26-web/Business-Operations-Dashboard](https://github.com/khanmuhammadjasim26-web/Business-Operations-Dashboard)
* **Live Showcase:** [https://khanmuhammadjasim26-web.github.io/Business-Operations-Dashboard/](https://khanmuhammadjasim26-web.github.io/Business-Operations-Dashboard/)

---
*Feel free to star ⭐ this repository if you find this Business Operations Dashboard useful!*
