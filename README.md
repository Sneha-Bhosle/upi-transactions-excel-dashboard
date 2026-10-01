# upi-transactions-excel-dashboard
Interactive Excel KPI dashboard analyzing 500K+ UPI transactions, regional trends, payment gateway shares, and fraud alerts.


# 📊 UPI Transactions Analytics Dashboard (Microsoft Excel)

An interactive, multi-dimensional executive dashboard built in Microsoft Excel analyzing over 500,000+ UPI transaction records, regional distribution, channel mix, failure trends, and fraud alerts.

---

## 🖥️ Interactive Dashboard Demo

![Dashboard Walkthrough](walkthrough.gif)

---

## 📌 Executive Summary & Key Metrics
* **Total Transactions Analyzed:** 502,857
* **Total Gross Transaction Value (GTV):** ₹44.25 Crore
* **Overall Success Rate:** 91.07%
* **Total Cashback Distributed:** ₹34.63 Lakh
* **Suspected Fraud Flags:** 17,089 transactions

---

## 🔍 Core Visuals & Business Questions Answered
1. **Regional Performance (Choropleth Map):** State-wise breakdown highlighting top-performing states (Maharashtra, Karnataka, Madhya Pradesh, Uttar Pradesh).
2. **Channel & App Distribution:** Volume and value market share across PhonePe, Google Pay, Paytm, BHIM, and WhatsApp Pay.
3. **Operational Temporal Trends:** Hourly transaction volume spikes identifying server load peaks between 5 PM and 9 PM.
4. **Transaction Health:** Breakdown of Successful (91.1%), Failed (7.0%), and Pending (2.0%) transactions for SLA compliance.
5. **Merchant Category Spend:** Distribution of transaction amounts across Bill Payments, Groceries, Shopping, Electronics, and Travel.

---

## 🛠️ Tools & Technical Features
* **Formulas & Modeling:** `INDEX/MATCH`, `XLOOKUP`, nested `IFS`, dynamic ranking, summary aggregations.
* **Interactivity:** Linked multi-tier PivotTables, timeline slicers (Region, Bank, UPI App, Category).
* **Integrity Controls:** Conditional anomaly alerting for transaction failure spikes and suspected fraud indicators.

---

## 📂 How to View
1. Download `UPI_Transactions_Dashboard.xlsx` from this repository.
2. Open with Microsoft Excel (2019 or Microsoft 365 recommended).
3. Use the **Filter Panel** on the left to interact with regional, category, and app-level data slices.
