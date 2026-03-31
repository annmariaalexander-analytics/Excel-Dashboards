# Excel-Dashboards
Excel-based dashboards analyzing sales performance, KPIs, and business trends using Pivot Tables, Power Query, and advanced formulas. Focused on data-driven decision-making and MIS reporting.
# 🛡 Insurance Claims Analytics Dashboard
### Excel Data Analytics Project 

---

## 📁 Dataset
**File:** `Insurance_Data.xlsx`  
**Records:** 2,000 claims | **Columns:** 23 (19 original + 4 calculated)  
**Source:** BLUE KWET Management Consultancies CO LLC (UAE)

---

## 🎯 Objective
To analyze insurance claims data and identify **why the company is incurring losses** by examining claim patterns, fraud exposure, settlement efficiency and customer retention behaviour across 6 UAE branches.

---

## 🧹 Data Cleaning
| Step | Action |
|---|---|
| Missing Values | 678 blank Settlement fields filled with "N/A - Not Settled" |
| Date Formats | Converted Policy_Start_Date, Claim_Date, Settlement_Date from text to Date |
| New Columns | Added Loss_Ratio, Claim_Age_Days, Claim_Year, Claim_Month |
| Duplicates | None found — all 2,000 records unique |
| Negative Values | None found in numeric columns |

---

## 📊 Dashboard KPIs
| KPI | Value |
|---|---|
| Total Claims | 2,000 |
| Approval Rate | 66.1% |
| Fraud Rate | 6.95% |
| Loss Amount | AED 56.2M |
| Avg Settlement | 23.4 days |

---

## 🔍 Business Questions & Insights

**BQ1 — Claim Amount by Policy Type**
- Motor Insurance highest total claims → AED 18.5M
- Business Insurance close second → AED 17.3M

**BQ2 — Claim Approval Rate by Branch**
- Ajman best approval rate → 71%
- Abu Dhabi lowest → 61%
- Overall approval rate → 66%

**BQ3 — Most Frequent & Costly Claim Reason**
- Most frequent → Travel Cancellation (268 claims)
- Most costly avg → Property Damage (AED 33,938 per claim)

**BQ4 — Settlement Time by Policy & Channel**
- Fastest channel → Mobile App (22.5 days)
- Slowest channel → Branch (23.7 days)
- Slowest combo → Home Insurance via Branch (28.0 days)

**BQ5 — Investigation vs Settlement Time**
- Investigated claims settle faster → 22.6 days vs 23.6 days
- Surprising finding — investigation does not slow down settlement!

**BQ6 — Fraud Rate by Policy Type**
- Overall fraud rate → 6.95% (139 out of 2,000)
- Motor Insurance has highest fraud exposure

**BQ7 — Fraudulent Claims Approval Status**
- 🚨 71% of fraudulent claims were APPROVED (99 out of 139)
- Only 25 fraud cases rejected
- Major financial control gap identified

**BQ8 — Loss Value by Policy Type**
- Total company loss → AED 56.2M
- Business Insurance highest loss → AED 15.9M
- Every policy type has loss ratio above 1.0x
- Company collects AED 9.5M in premiums but pays AED 65.6M in claims

**BQ9 — Customer Renewal Rate by Segment**
- All 3 segments renew at similar rate (~33%)
- No significant difference between Corporate, Retail and SME

**BQ10 — Claim Status Impact on Renewal**
- Rejected claims renew at 33.7% vs Approved at 32%
- Claim rejection does NOT significantly affect renewal
- Customers stay loyal regardless of claim outcome

---

## 🚨 Key Finding — Why Is the Company in Loss?

> The company collected only **AED 9.5M** in premiums but paid out **AED 65.6M** in claims — a loss of **AED 56.2M**

Three root causes identified:
1. **Premiums are too low** — avg premium AED 4,729 vs avg claim AED 32,824
2. **Fraud approvals** — 71% of fraudulent claims approved, draining money
3. **High value claims** — Property Damage and Travel Cancellation averaging AED 33,000+ per claim

---

## 🛠 Tools Used
- **Microsoft Excel** — Data cleaning, pivot tables, dashboard, charts, slicers, KPI cards
- **Power BI** — (Coming soon)
- **Tableau** — (Coming soon)

---

## 📂 Files in this Repository
```
├── insurance_Data.xlsx        # Original dataset
├── Insurance_Cleaned.xlsx       # Cleaned dataset with calculated columns
├── Insurance_Dashboard.xlsx     # Final Excel dashboard
└── README.md                    # This file
```

---

## 👩‍💻 Author
**Ann Maria KA**  
