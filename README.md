# 📦 Shipment Journey Data Analysis

This repository contains a complete solution to a data analysis assignment for a logistics company. The objective is to process and analyze shipment tracking data from JSON files, flatten it into a structured format, and derive meaningful insights for business intelligence and logistics optimization.

---

## 🧠 Problem Statement

You're working for a logistics company that helps deliver online orders from a seller's warehouse to a customer’s address. Each shipment undergoes several stages—pickup, transit, warehouse stops, and final delivery. The dataset captures this journey in detail.

### Tasks

- Load and parse a nested JSON dataset.
- Flatten each shipment’s tracking data.
- Extract and compute relevant fields like:
  - Tracking Number
  - Payment Type (Prepaid/COD)
  - Pickup & Delivery Date-Time (in IST)
  - Days Taken for Delivery
  - Delivery Attempts
  - Location Info (Pincode, City, State)
  - Shipment Weight

- Save cleaned data as a CSV for analytics.
- Generate a summary CSV file with:
  - Mean, Median, and Mode of days taken for delivery
  - Mean, Median, and Mode of delivery attempts

---



## 📊 Visualizations
The notebook also includes several useful visualizations such as:

Payment Type Distribution

Delivery Duration Histogram

Delivery Attempts Distribution

State-wise Delivery Analysis

## 📌 Key Learnings
JSON flattening and ETL workflows in Python

Timezone conversion and datetime processing

Summary statistics generation

Data visualization for operational insights

