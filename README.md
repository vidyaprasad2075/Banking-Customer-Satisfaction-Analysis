# Banking Customer Satisfaction & Service Resolution Analysis (Excel)

## 📌 Executive Project Overview
This project focuses on evaluating customer service efficiency and tracking issue lifecycles within a retail banking environment. Utilizing a structured transactional log of 1,200 unique customer complaints across 8 distinct operational categories (including Fraud Investigations, Card Problems, and Account Access errors), this analysis isolates response bottlenecks across multiple communication channels. 

The resulting business intelligence metrics provide executive leadership with clarity on support performance, channel-specific SLA compliance, and underlying drivers of poor customer sentiment.

---

## 🛠️ Tech Stack & Methodology
* **Advanced Microsoft Excel:** Used for deep-dive exploratory data analysis (EDA), data cleaning, conditional field formatting, and cross-tabulation.
* **Pivot Tables & Calculations:** Built out complex matrices to isolate distribution trends, group operational time deltas, and segment volume metrics.
* **Data Visualizations:** Engineered a centralized executive reporting dashboard linking dynamic charts with slicers for seamless operational monitoring.

---

## 📈 Key Banking Performance Benchmarks (KPIs)
Through targeted data aggregation, organization-wide customer support baselines were established:
* **Total Logged Complaints:** 1,200 cases.
* **Resolved Case Count:** 783 cases (65.25% resolution efficiency rate).
* **Average Operational Resolution Time:** 27.70 Hours.
* **Average Customer Satisfaction Score:** 3.22 / 5.00.

---

## 🎯 Strategic Business Insights

### 1. Operational Inefficiencies by Issue Type
The complaint pipeline is remarkably distributed, indicating systemic challenges across different products rather than a single point of failure. **Fraud Investigations** (165 cases) and **Card Problems** (161 cases) represent the highest strain on customer support teams, creating critical areas for backend security and authentication process optimization.

### 2. Communication Channel Inefficiencies & SLA Drift
While the average bank-wide resolution time is **27.70 hours**, significant variation appears when isolating communication channels:
* **Highest Latency:** **Website submissions** experience the longest resolution delays, averaging **29.28 hours**.
* **Lowest Latency:** **Call Centers** resolve issues fastest, averaging **25.21 hours**.

*Strategic Takeaway:* The 4-hour variance between digital self-service (Website) and direct support (Call Center) points to potential automated workflow integration gaps or systemic queue-routing delays for online requests.

### 3. Case Volume Backlogs
Out of 1,200 total cases, **241 remain In Progress** and **176 are Pending**. This indicates that nearly **34.7%** of all customer complaints have structural overhead delays, directly driving down the core customer sentiment score (3.22/5.00).

---

## 🖥️ Dashboard UI Layout

<img width="1825" height="877" alt="image" src="https://github.com/user-attachments/assets/847c524b-6021-4a38-a95a-548b838a7329" />



---

## 📂 Repository Structure
```directory
├── Data/
│   ├── Complaints_Data.csv
│   └── Pivot_Table_Extracts.csv
└── README.md
