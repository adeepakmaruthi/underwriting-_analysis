
# Underwriting & Customer Analytics Dashboard

An interactive **Insurance Underwriting & Customer Analytics Dashboard** built using **Python, Pandas, Plotly, and Dash**. The project analyzes policy, customer, and claims data to help insurance decision-makers understand portfolio performance, customer risk profiles, premium trends, claims patterns, and KYC quality.

### Key Features

* Interactive filters for **Location, Channel, Policy Type, and Policy Start Date**
* KPI cards for **Total Premium, Total Policies, Average Premium, Policies with Claims, and KYC Verified Rate**
* Premium trends over time
* Average premium analysis by distribution channel
* Claim-rate analysis across **credit-score bands and policy types**
* KYC status analysis
* Premium concentration by location
* Claim severity analysis by policy type
* Interactive **policy-level drill-down table**
* Professional Power BI-style dashboard layout

### Business Objective

The dashboard is designed to answer three key underwriting questions:

**What is happening?** — portfolio KPIs and trends
**Why is it happening?** — customer, credit, policy, channel, and claims drivers
**What should we do?** — evidence-based underwriting and portfolio management actions

### Data

The analysis uses synthetic course-provided insurance datasets:

* `customers.csv`
* `policies.csv`
* `claims.csv`

The datasets are joined using `customer_id` and `policy_id`, with derived underwriting and claims metrics created using Pandas.

### Technology

**Python | Pandas | Plotly | Dash | Jupyter Notebook**

This project was developed as part of an **Insurance Analytics Dashboard Project** focused on applying analytics tools to insurance data and designing data-driven insurance solutions.
