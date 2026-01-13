# 🏨 Hotel Revenue & Booking Analytics

**End-to-End Business Intelligence Project**

---

## 1. Introduction

Hotels often lose revenue due to poor pricing decisions, high cancellation rates, and lack of visibility into booking patterns. This project analyzes hotel booking data to understand **demand**, **pricing behavior**, and **cancellation risk**, and presents insights through a **business-friendly Power BI dashboard**.

**Objective:**

* Improve bookings
* Reduce cancellations
* Support data-driven pricing decisions

---

## 2. Dataset Overview

* **Source:** Hotel Booking Demand Dataset (Kaggle)
* **Size:** 100k+ booking records
* **Key Columns Used:**

  * Hotel type, booking lead time, arrival month
  * Stay duration (weekend & weekday nights)
  * Price (ADR)
  * Customer behavior (repeat guest, special requests)
  * Cancellation indicator

Only booking-time information was used to ensure realistic business analysis.

---

## 3. Data Preparation

* Removed irrelevant and leakage columns
* Handled missing values (e.g., children → 0)
* Ensured clean data for analysis and dashboarding

This step ensured the insights reflect **real operational scenarios**.

---

## 4. Exploratory Data Analysis (EDA)

The following visual analyses were performed (only high-impact business visuals are included):

### 4.1 Monthly Booking Trend

**Chart:** Column Chart
**Insight:** Clear seasonality observed. Peak months show significantly higher bookings.

*(Insert Chart: Monthly Booking Trend)*

---

### 4.2 Bookings by Hotel Type

**Chart:** Bar Chart
**Insight:** City hotels receive more bookings compared to resort hotels, indicating higher urban demand.

*(Insert Chart: Bookings by Hotel Type)*

---

### 4.3 Cancellation by Lead Time

**Chart:** Bar Chart
**Insight:** Early bookings (lead time > 30 days) show much higher cancellation rates.

*(Insert Chart: Cancellation by Lead Time)*

---

### 4.4 Room Price (ADR) vs Cancellation

**Chart:** Box Plot / Column Chart
**Insight:** Higher-priced bookings are more likely to be canceled, indicating price sensitivity.

*(Insert Chart: ADR vs Cancellation)*

---

### 4.5 Repeat Guest vs Cancellation

**Chart:** Bar Chart
**Insight:** Repeat guests cancel significantly less and represent more reliable revenue.

*(Insert Chart: Repeat Guest vs Cancellation)*

---

## 5. Power BI Dashboard

A **one-page executive dashboard** was designed to help hotel owners make quick decisions.

### Dashboard Components:

* **KPI Cards:**

  * Total Bookings
  * Average Room Price (ADR)
  * Cancellation Rate
  * Repeat Guest Percentage

* **Core Visuals:**

  * Monthly Booking Trend
  * Bookings by Hotel Type
  * Cancellation by Lead Time
  * ADR vs Cancellation
  * Repeat Guest vs Cancellation

* **Interactive Filters (Slicers):**

  * Hotel Type
  * Arrival Month
  * Market Segment

*(Insert Dashboard Screenshot)*

---

## 6. Key Business Insights

* High room prices increase cancellation risk
* Early bookings are more uncertain and require stricter policies
* Long-stay customers pay less per night but provide stable revenue
* Repeat guests are highly valuable and reliable

---

## 7. Recommendations for Hotel Management

* Apply **dynamic pricing** during peak months
* Introduce **deposit policies** for early and high-priced bookings
* Offer **loyalty benefits** to repeat customers
* Provide discounts for long stays to ensure occupancy
* Encourage direct bookings to reduce cancellation risk

---

## 8. Conclusion

This project demonstrates how **data analytics and dashboards** can directly support hotel revenue management. By focusing on actionable insights rather than complex models, the solution enables hotel owners to **increase revenue, reduce cancellations, and improve decision-making**.

---

**Tools Used:** Python (Pandas, Seaborn), SQL (MySQL), Power BI
**Outcome:** Recruiter-ready, industry-focused analytics project

