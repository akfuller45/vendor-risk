# vendor-risk

# Vendor Risk Assessment & Procurement Governance Dashboard

## Executive Summary

This project simulates an enterprise Vendor Risk Assessment and Procurement Governance framework using procurement KPI data.

The purpose of this project is to evaluate supplier performance, identify high-risk vendors, monitor procurement control effectiveness, assess compliance exposure, and create executive-level third-party risk reporting.

The project is designed from the perspective of a Vendor Risk Analyst, GRC Analyst, Procurement Risk Analyst, Third-Party Risk Analyst, or Operational Risk Analyst working in an enterprise environment.

Rather than only analyzing procurement performance, this project transforms purchase order data into a vendor governance system that includes risk scoring, supplier-level summaries, control testing, remediation tracking, risk ownership, and executive dashboarding.

---

## Business Problem

Organizations rely on third-party suppliers to deliver goods, services, materials, and operational support. Poor vendor performance can create significant business risk, including:

- late deliveries
- defective goods
- compliance failures
- cancelled orders
- weak pricing outcomes
- supplier concentration exposure
- operational disruption
- audit readiness gaps

Without a structured vendor risk framework, leadership may lack visibility into which suppliers require monitoring, remediation, escalation, or strategic review.

This project builds a simulated vendor risk management system to identify these risks and support procurement governance decision-making.

---

## Project Objectives

The objectives of this project are to:

- Evaluate supplier performance across procurement KPIs
- Identify high-risk suppliers
- Detect late delivery exposure
- Monitor supplier defect rates
- Analyze supplier compliance failures
- Evaluate cancelled order exposure
- Measure negotiated cost savings
- Create vendor risk scores
- Build supplier-level risk summaries
- Test procurement governance controls
- Create a vendor risk register
- Assign vendor risk ownership
- Create remediation actions and review deadlines
- Build a vendor risk matrix
- Develop an executive vendor risk dashboard

---

## Dataset Overview

The dataset contains procurement and supplier performance records.

Key fields include:

| Field | Description |
|---|---|
| `po_id` | Purchase order identifier |
| `supplier` | Vendor or supplier name |
| `order_date` | Date the purchase order was placed |
| `delivery_date` | Date the order was delivered |
| `item_category` | Category of purchased item |
| `order_status` | Status of the purchase order |
| `quantity` | Number of units ordered |
| `unit_price` | Original unit price |
| `negotiated_price` | Final negotiated unit price |
| `defective_units` | Number of defective units |
| `compliance` | Supplier compliance status |

---

## Methodology

The project follows an enterprise vendor risk workflow:

1. Load and inspect procurement data
2. Standardize column names and data types
3. Convert order and delivery dates
4. Calculate delivery cycle time
5. Calculate gross and negotiated order value
6. Calculate cost savings and savings rate
7. Calculate defect rates
8. Create vendor risk flags
9. Score purchase orders by vendor risk exposure
10. Aggregate supplier-level risk metrics
11. Classify suppliers by risk level
12. Test procurement governance controls
13. Create a vendor risk register
14. Assign risk owners and remediation actions
15. Create review due dates and overdue review flags
16. Build a vendor impact-likelihood risk matrix
17. Export high-risk vendor registers
18. Build an executive vendor risk dashboard

---

## Procurement Metrics Created

The project created several procurement and vendor performance metrics:

| Metric | Purpose |
|---|---|
| `delivery_days` | Measures delivery time between order and receipt |
| `gross_order_value` | Calculates original purchase order value |
| `negotiated_order_value` | Calculates final negotiated purchase order value |
| `cost_savings` | Measures savings from negotiation |
| `cost_savings_rate` | Measures percentage savings from negotiation |
| `defect_rate` | Measures defective units as a percentage of quantity |
| `late_delivery_flag` | Flags delayed supplier delivery |
| `high_defect_flag` | Flags elevated quality risk |
| `compliance_failure_flag` | Flags supplier compliance failures |
| `cancelled_order_flag` | Flags cancelled procurement activity |
| `low_savings_flag` | Flags weak negotiated savings performance |

---

## Vendor Risk Indicators

Each purchase order was evaluated using multiple third-party risk indicators.

| Risk Indicator | Description |
|---|---|
| Late Delivery | Supplier delivery time exceeded the expected threshold |
| High Defect Rate | Supplier defect rate exceeded the high-risk threshold |
| Compliance Failure | Supplier failed compliance requirements |
| Cancelled Order | Purchase order was cancelled |
| Low Savings | Negotiated savings rate was below expected performance |

These indicators were used to calculate a vendor risk score and classify each purchase order into a risk level.

---

## Vendor Risk Scoring

A vendor risk score was created by assigning weighted risk points to each purchase order.

Risk points were assigned for:

- late delivery
- high defect rate
- compliance failure
- cancelled order
- low negotiated savings

The final vendor risk score was classified into four categories:

| Risk Level | Description |
|---|---|
| Low | Minimal supplier risk exposure |
| Medium | Moderate supplier risk requiring monitoring |
| High | Elevated supplier risk requiring review |
| Critical | Severe vendor risk requiring escalation |

---

## Supplier-Level Risk Summary

Purchase order data was aggregated to the supplier level to create a vendor risk profile for each supplier.

Supplier-level metrics include:

| Supplier Metric | Description |
|---|---|
| Total Orders | Number of purchase orders associated with supplier |
| Total Spend | Total negotiated spend with supplier |
| Average Delivery Days | Average delivery time |
| Late Delivery Rate | Percentage of orders delivered late |
| Average Defect Rate | Average supplier defect rate |
| Compliance Failure Rate | Percentage of records with compliance failure |
| Cancelled Order Rate | Percentage of cancelled orders |
| Average Cost Savings Rate | Average negotiated savings percentage |
| Average Vendor Risk Score | Supplier average risk score |
| Supplier Risk Level | Supplier-level risk classification |

---

## Automated Procurement Control Testing

The project includes automated control testing to evaluate procurement governance readiness.

Controls tested include:

| Control ID | Control Name | Risk Area |
|---|---|---|
| CTRL-001 | Supplier Present | Vendor Data Completeness |
| CTRL-002 | Order and Delivery Dates Present | Timeline Completeness |
| CTRL-003 | Positive Quantity | Procurement Validity |
| CTRL-004 | Price Fields Present | Pricing Completeness |
| CTRL-005 | Compliance Status Present | Compliance Monitoring |
| CTRL-006 | Valid Delivery Timeline | Delivery Accuracy |

Each control was evaluated using:

- total records tested
- records passed
- records failed
- pass rate
- control effectiveness rating

Control effectiveness was classified as:

| Pass Rate | Effectiveness |
|---|---|
| 95% or higher | Effective |
| 85% to 94.99% | Needs Monitoring |
| Below 85% | Ineffective |

---

## Vendor Risk Register

A vendor risk register was created to simulate enterprise third-party risk management and remediation tracking.

Each supplier was assigned:

- supplier risk level
- risk owner
- vendor status
- remediation priority
- recommended remediation action
- latest delivery date
- review due date
- overdue review flag

The vendor risk register supports:

- supplier oversight
- third-party risk monitoring
- remediation planning
- vendor accountability
- procurement governance
- audit readiness

---

## Risk Owner Assignment

Suppliers were assigned to governance owners based on their primary risk drivers.

| Risk Owner | Assignment Logic |
|---|---|
| Compliance Management | Elevated compliance failure rate |
| Supplier Quality Team | Elevated defect rate |
| Procurement Operations | Elevated late delivery rate |
| Vendor Management | Elevated cancellation rate |
| Strategic Sourcing | High spend concentration |
| Procurement Governance | Standard monitoring |

This simulates how enterprise risk teams route vendor issues to responsible business functions.

---

## Vendor Status Classification

Each supplier was assigned a vendor status based on risk level.

| Vendor Status | Description |
|---|---|
| Escalated | Critical supplier risk requiring immediate review |
| Remediation Required | High-risk supplier requiring corrective action |
| Under Review | Medium-risk supplier requiring monitoring |
| Monitoring | Low-risk supplier under standard review |

---

## Remediation Priority

Suppliers were assigned remediation priority levels based on risk exposure.

| Priority | Timeline |
|---|---|
| Critical | 7-day review |
| High | 14-day review |
| Medium | 30-day review |
| Low | 60-day review |

This provides a structured review timeline for supplier risk governance.

---

## Vendor Risk Matrix

A vendor risk matrix was created using an impact and likelihood framework.

### Impact Score

Impact was based on supplier spend concentration. Suppliers with higher total spend were assigned higher impact scores because failures from these suppliers may create greater financial or operational disruption.

### Likelihood Score

Likelihood was based on recurring supplier risk indicators, including:

- late delivery rate
- average defect rate
- compliance failure rate
- cancelled order rate

### Matrix Score

The vendor matrix score was calculated as:

```text
Impact Score × Likelihood Score = Vendor Matrix Score
```

Suppliers were then classified into:

- Low
- Medium
- High
- Critical

This matrix supports vendor prioritization, third-party risk oversight, procurement governance, remediation planning, and executive reporting.

---

## Executive Dashboard

The executive dashboard provides a consolidated view of vendor risk and procurement governance performance.

Dashboard components include:

- total purchase orders
- total suppliers
- total spend
- average delivery days
- late orders
- compliance failures
- high-risk vendors
- overdue vendor reviews
- supplier risk level distribution
- vendor matrix risk distribution
- vendor risk matrix heatmap
- vendor status distribution
- vendor risk ownership
- remediation priority distribution
- top vendors by risk score
- top compliance failure rates
- failed vendor controls

![Vendor Risk Governance Dashboard](outputs/charts/vendor_risk_governance_dashboard.png)

---

## Key Findings

### Finding 1 — Supplier Risk Concentration

The supplier risk scoring framework identified vendors with elevated risk profiles based on late delivery, defect rates, compliance failures, cancelled orders, and low cost savings performance.

These suppliers may require enhanced monitoring, performance reviews, or corrective action plans.

### Finding 2 — Compliance Failure Exposure

Some suppliers showed elevated compliance failure rates. Compliance failures represent a governance concern because they may indicate weak supplier controls, incomplete documentation, or failure to meet procurement requirements.

### Finding 3 — Delivery Performance Risk

Late delivery flags identified suppliers with weaker delivery performance. Delayed deliveries may create operational disruption, inventory shortages, production delays, or service interruptions.

### Finding 4 — Supplier Quality Risk

High defect rates indicate potential supplier quality concerns. Suppliers with elevated defect rates may require quality audits, corrective action plans, or revised supplier agreements.

### Finding 5 — Vendor Matrix Risk Exposure

The vendor risk matrix identified suppliers with elevated impact and likelihood scores. High-impact suppliers represent larger spend exposure, while high-likelihood suppliers demonstrated recurring performance or compliance issues.

Suppliers classified as High or Critical should receive enhanced review and management oversight.

### Finding 6 — Overdue Vendor Reviews

The remediation tracker identified suppliers with overdue review dates. Overdue reviews may indicate gaps in vendor governance monitoring and should be prioritized for management follow-up.

---

## Recommendations

### Vendor Governance Recommendations

- Maintain a centralized vendor risk register.
- Perform recurring supplier risk reviews.
- Assign risk owners for high-risk suppliers.
- Track remediation status and overdue reviews.
- Monitor vendor risk score trends over time.

### Procurement Risk Recommendations

- Review suppliers with high late delivery rates.
- Establish corrective delivery SLAs for poor-performing suppliers.
- Analyze cancelled order patterns by supplier.
- Monitor spend concentration across high-impact vendors.

### Supplier Quality Recommendations

- Conduct supplier quality reviews for vendors with elevated defect rates.
- Require defect reduction plans for repeat quality issues.
- Review item categories with higher defect exposure.
- Track defect rates as part of ongoing vendor scorecards.

### Compliance Recommendations

- Require remediation evidence for suppliers with compliance failures.
- Perform supplier compliance reviews for high-risk vendors.
- Include compliance status in recurring vendor performance meetings.
- Escalate suppliers with repeated compliance failures.

### Strategic Sourcing Recommendations

- Review pricing and negotiation performance for low-savings suppliers.
- Evaluate opportunities to renegotiate supplier contracts.
- Monitor total spend concentration by supplier.
- Consider alternate suppliers for high-risk or low-value vendors.

### Audit Readiness Recommendations

- Export vendor risk registers for audit review.
- Preserve control testing summaries.
- Maintain evidence of vendor remediation actions.
- Track review due dates and overdue vendor assessments.
- Document supplier risk classification logic.

---

## Project Outputs

The project produces the following outputs:

| Output | Description |
|---|---|
| `vendor_risk_register.csv` | Supplier-level risk register with ownership and remediation tracking |
| `high_risk_vendor_register.csv` | Register of high and critical suppliers |
| `critical_vendor_matrix_register.csv` | Suppliers classified as critical in the impact-likelihood matrix |
| `vendor_matrix_summary.csv` | Summary of vendor matrix risk levels |
| `vendor_risk_matrix.png` | Vendor impact-likelihood risk matrix visual |
| `vendor_risk_governance_dashboard.png` | Executive vendor risk dashboard |
| `process_control_testing_summary.csv` or `vendor_control_testing_summary.csv` | Automated procurement control testing summary |

---

## Technology Stack

- Python
- pandas
- numpy
- matplotlib
- Jupyter Notebook
- CSV data processing
- GitHub

---

## Project Structure

```text
vendor-risk-procurement-governance-dashboard/

│
├── data/
│   ├── raw/
│   ├── cleaned/
│
├── notebooks/
│   └── vendor_risk_procurement_governance.ipynb
│
├── outputs/
│   ├── charts/
│   │   ├── vendor_risk_governance_dashboard.png
│   │   └── vendor_risk_matrix.png
│   ├── tables/
│   │   ├── vendor_risk_register.csv
│   │   ├── high_risk_vendor_register.csv
│   │   ├── critical_vendor_matrix_register.csv
│   │   ├── vendor_matrix_summary.csv
│   │   └── vendor_control_testing_summary.csv
│   └── reports/
│
├── README.md
├── requirements.txt
├── .gitignore
└── LICENSE
```

---

## Suggested `.gitignore`

```text
__pycache__/
.ipynb_checkpoints/
*.pyc

data/raw/
data/cleaned/

.DS_Store
.env
```

---

## Portfolio Value

This project demonstrates skills relevant to:

- vendor risk management
- third-party risk management
- procurement governance
- supplier performance analytics
- operational risk analysis
- GRC reporting
- compliance monitoring
- control testing
- remediation tracking
- audit readiness
- executive dashboarding
- business intelligence

---

## Future Enhancements

Potential future improvements include:

- interactive Power BI dashboard
- vendor scorecard PDF generation
- supplier concentration risk analysis
- contract expiration tracking
- vendor remediation tracker
- ESG supplier risk scoring
- cyber third-party risk scoring
- supplier performance trend analysis
- predictive late delivery modeling
- automated vendor review alerts

---

## Author

Amiranda Fuller

Governance Analytics | Vendor Risk | Procurement Governance | Operational Risk | Business Intelligence
