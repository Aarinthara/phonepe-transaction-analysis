# 📱 PhonePe Digital Payments — Data Analysis Case Study

![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green?logo=pandas)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-orange)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-red)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

## 📌 Project Overview

This project analyzes **transaction and demographic data** from PhonePe — one of India's leading digital payment platforms — spanning **Q1 2018 to Q2 2021**. The goal is to uncover trends in transaction behavior, device usage patterns, and demographic correlations across **36 states and 723 districts** in India.

---

## 🎯 Objectives

- Analyze transaction growth trends across states and quarters
- Identify top-performing and low-adoption states and districts
- Understand device brand preferences among PhonePe users
- Explore correlations between population density and digital payment adoption
- Deliver state-specific deep-dive insights (Tamil Nadu focus)

---

## 📂 Dataset

The dataset is an Excel file with **6 sheets**, each covering a different dimension of PhonePe's data:

| Sheet | Description |
|---|---|
| `State_Txn and Users` | State-wise transactions, amount, app opens, registered users |
| `State_TxnSplit` | Transaction type breakdown per state and quarter |
| `State_DeviceData` | Device brand and registered users per state |
| `District_Txn and Users` | District-level transaction and user data |
| `District Demographics` | Population, density, and demographic data by district |
| `Admin` | Administrative/reference data |

**Source:** PhonePe Pulse — Public Data Release (Q1 2018 – Q2 2021)

---

## 🛠️ Tools & Libraries

```
Python 3.8+
pandas
numpy
matplotlib
seaborn
```

---

## 📊 Key Analyses Performed

### 1. Exploratory Data Analysis (EDA)
- Summary statistics, data types, and missing value identification
- Dataset covers 36 states and 723 unique districts

### 2. Transaction Trends
- Yearly and quarterly growth in transaction volume and amount
- Top 5 and bottom 5 states by transaction volume
- Most common transaction type per state and quarter

### 3. Device Brand Analysis
- Dominant device brand (by registered users) per state
- Device brand usage ratio across all states
- **Finding:** Xiaomi leads in most states, followed by Samsung and Vivo

### 4. Demographic Analysis
- Highest-population district per state
- Population density vs. transaction volume correlation
- **Finding:** Moderate positive correlation — denser areas transact more

### 5. Average Transaction Value (ATV)
- State-wise ATV ranking
- **Finding:** Ladakh and A&N Islands have the highest ATV; West Bengal and Odisha the lowest

### 6. Tamil Nadu Deep Dive
- Transaction volume and amount trends (2018–2021)
- App usage growth over time
- Transaction type distribution (Pie chart — 2021 Q2)
- Population density across districts

---

## 💡 Key Findings

- **Consistent growth:** Digital transactions grew steadily from 2018 to 2021 across India
- **Top states:** Karnataka, Maharashtra, Telangana, and Tamil Nadu lead in transaction activity
- **Payment type:** Peer-to-peer transfers and merchant payments dominate transaction share
- **Devices:** Android brands (Xiaomi, Samsung, Vivo, Oppo) dominate the user base
- **Urban edge:** Densely populated urban districts show higher digital payment adoption
- **COVID dip:** A slight drop in 2020 Q2 followed by rapid recovery and acceleration

---

## 📁 Repository Structure

```
PhonePe-Digital-Payments-Analysis/
│
├── Phonepay.ipynb                  # Main Jupyter Notebook (full analysis)
├── phonepe-pulse_raw-data.xlsx     # Source dataset (6 sheets)
├── README.md                       # Project documentation
└── requirements.txt                # Python dependencies
```

---

## 🚀 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/PhonePe-Digital-Payments-Analysis.git
   cd PhonePe-Digital-Payments-Analysis
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Open the notebook**
   ```bash
   jupyter notebook Phonepay.ipynb
   ```

4. Make sure the Excel file is in the **same folder** as the notebook before running.

---

## 📋 Requirements

```
pandas
numpy
matplotlib
seaborn
openpyxl
jupyter
```

*(Also saved in `requirements.txt`)*

---

## 🔮 Recommendations

- Expand digital payment outreach to **semi-urban and rural regions**
- Improve **digital literacy and accessibility** in low-adoption states
- Strengthen **merchant payment ecosystems** to meet growing demand
- Optimize app experience for **popular Android brands** (Xiaomi, Samsung, Vivo)

---

## 👤 Author

**Aarinthara Babu**
- 🔗 [LinkedIn](www.linkedin.com/in/aarinthara-babu)

