# RCM-Dashboard
# 🏥 Revenue Cycle Management (RCM) Dashboard – Tableau Project

This project presents an interactive Tableau dashboard designed to monitor and analyze key financial and operational metrics in the **Revenue Cycle Management** process for healthcare organizations.

The dashboard helps stakeholders quickly identify trends, track performance, and make data-driven decisions to improve collections, reduce denials, and optimize cash flow.

---

## 📊 Dashboard Visuals & Insights

### 1️⃣ **Transaction Trend (Gross Charges)**
- **Description**: Line chart showing gross charges over time.
- **Tooltip**: Displays **month-over-month change (%)**.
- **Insight**: Helps identify billing trends and seasonal fluctuations in revenue generation. Sudden dips or spikes can signal operational changes or issues in billing volume.

---

### 2️⃣ **Accounts Receivable (AR) Summary**
- **Components**:
  - **AR Balance**: Total outstanding receivables.
  - **AR Snapshot Breakdown**:
    - **Final Bill**: Charges ready for submission.
    - **DNFB Beyond Suspense**: Discharged but not final billed beyond expected threshold.
    - **DNFB In Suspense**: Charges currently in allowable hold time.
  - **Percent of Total**: Visual contribution of each category.
- **Insight**: Quickly assess AR aging and pinpoint bottlenecks in the billing process. A high DNFB may indicate documentation delays or workflow inefficiencies.

---

### 3️⃣ **Denial Summary**
- **Description**: Bar chart showing **total denied charges**, **denial rate**, and **month-over-month % change**.
- **Insight**: Helps uncover trends in claim denials and monitor denial management effectiveness. Rising denial rates can highlight coding or authorization issues.

---

### 4️⃣ **Charges by Provider (Tree Map)**
- **Description**: Tree map showing provider-wise distribution of gross charges.
- **Insight**: Visualizes top revenue-generating providers and helps benchmark provider productivity. Disproportionate charge volumes can trigger deeper review into patient load and billing efficiency.

---

### 5️⃣ **Charges by Medical Service**
- **Description**: Bar chart ranking charges by medical service (e.g., Radiology, Cardiology, Surgery).
- **Insight**: Shows which departments contribute most to revenue, aiding in strategic planning, resource allocation, and marketing focus.

---

### 6️⃣ **Balance by Denial Reason**
- **Description**: Bar chart showing outstanding balance grouped by denial reason.
- **Insight**: Reveals the **financial impact of denials** and top root causes (e.g., eligibility, missing info, prior auth), guiding targeted denial prevention strategies.

---

## 📘 Definitions

- **Gross Charges**: Total charges submitted before adjustments.
- **Denial Rate**: Percentage of claims denied out of total submitted.
- **DNFB (Discharged Not Final Billed)**: Patients discharged, but claim not yet billed.
- **AR Balance**: Total amount still due from payers or patients.

---

## 🛠️ Tools Used

- **Tableau** – Data visualization and dashboarding.
- **Sample RCM Data** – Simulated for demonstration purposes.
- **JIRA (Planned)** – For backlog and task management (not shown in this dashboard).

---

## 🔗 Live Preview

If published to Tableau Public, include:

[👉 View Live Dashboard](https://public.tableau.com/...)

---

## 📥 Contact

**Created by**: Dinesh Banjara  
If you'd like to collaborate or have questions, feel free to connect via [LinkedIn](https://www.linkedin.com/in/dinesh-banjara-1608616b/) or email me.

