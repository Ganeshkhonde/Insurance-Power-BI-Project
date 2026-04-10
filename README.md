# Prism Insurance Dashboard

---

## Problem Statement

This dashboard helps **Prism Insurance Pvt. Ltd.** analyze their overall business performance by tracking key metrics such as premium collection, claim amounts, and policy distribution. It enables stakeholders to understand customer behavior, monitor claim trends, and identify areas for improving operational efficiency.

The dashboard provides insights into:

* Total premium revenue generated
* Total coverage offered to customers
* Total claim amount processed
* Claim status distribution (Rejected, Settled, Pending)
* Policy activity (Active vs Inactive)
* Performance across different policy types

By using this dashboard, the company can optimize claim processing, improve customer retention, and make data-driven decisions.

---

## Steps Followed

* **Step 1:** Loaded dataset into Power BI Desktop.
* **Step 2:** Opened Power Query Editor and enabled:

  * Column Quality
  * Column Distribution
  * Column Profile
* **Step 3:** Ensured profiling was based on the entire dataset.
* **Step 4:** Cleaned the data by handling null values and verifying data types.
* **Step 5:** Created relationships between tables using keys like CustomerID, PolicyNumber, and ClaimNumber.
* **Step 6:** Designed the dashboard theme and layout for better visualization.
* **Step 7:** Added slicers for:

  * CustomerID
  * PolicyNumber
  * ClaimNumber
* **Step 8:** Created KPI cards for:

  * Total Premium Amount
  * Total Coverage Amount
  * Total Claim Amount
* **Step 9:** Added gender distribution cards for male and female customers.
* **Step 10:** Created a bar chart to visualize **Premium Amount by Policy Type**.
* **Step 11:** Added a donut chart to represent **Active vs Inactive Policies**.
* **Step 12:** Built an area chart showing **Number of Claims by Claim Status**.
* **Step 13:** Created a line chart for **Claim Amount by Age Group**.
* **Step 14:** Added a matrix table showing claim status breakdown (Pending, Rejected, Settled) across policy types.
* **Step 15:** Finalized dashboard formatting and published to Power BI Service.

---

## Dashboard Features

* Interactive slicers for dynamic filtering
* KPI cards for quick business overview
* Policy-type based premium analysis
* Claim status tracking
* Age-group based claim insights
* Active vs inactive policy monitoring
* Detailed tabular breakdown for deeper analysis

---

## Snapshot of Dashboard (Power BI Service)
<img width="3198" height="1750" alt="Image" src="https://github.com/user-attachments/assets/fe040134-1949-43f2-a2b8-7eb73eb2dbef" />

---

## Insights

### [1] Overall Business Performance

* Total Premium Amount: **5.97M**
* Total Coverage Amount: **600.33M**
* Total Claim Amount: **16.90M**

This indicates that the company has a high coverage base compared to claims, showing controlled risk exposure.

---

### [2] Policy Type Analysis

* Travel policies generate the highest premium (~2.5M)
* Health and Auto policies follow
* Home and Life policies contribute comparatively less

-> Travel insurance is the most profitable segment.

---

### [3] Policy Activity

* Active Policies: ~58%
* Inactive Policies: ~42%

A significant portion of policies are inactive, indicating potential churn or renewal gaps.

---

### [4] Claims Status

* Rejected claims are the highest (~4.4K)
* Settled claims are moderate (~3.4K)
* Pending claims are the lowest (~2.3K)

High rejection rate may indicate strict claim validation or customer dissatisfaction.

---

### [5] Age Group Analysis

* Adults generate the highest claim amount (~8.8M)
* Elders contribute moderately (~6.4M)
* Young adults have the least (~1.7M)

Adults are the primary risk segment for claims.

---

### [6] Gender Distribution

* Male Customers: 5000
* Female Customers: 5000

-> Customer base is evenly distributed across genders.

---

### [7] Detailed Claim Breakdown

* Travel policies have the highest pending and rejected claims
* Health policies also show significant claim activity

-> These categories require better claim management strategies.

---

## Conclusion

This dashboard provides a comprehensive view of the insurance business by combining financial metrics, customer segmentation, and claim analysis. It helps in identifying high-performing segments, monitoring risks, and improving decision-making through data-driven insights.

---

## Tools Used

* Power BI Desktop
* Power Query Editor

---
