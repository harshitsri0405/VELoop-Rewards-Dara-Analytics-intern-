# VELOOP Rewards --- Product Analytics & Data Readiness

A documentation-led analytics project developed as part of **Data
Analyst Internship --- Task 01**. It brings together product data
auditing, analytics specifications, KPI definitions, event tracking,
data quality, governance, pipeline design, and implementation planning
in one navigable HTML experience.

> **Data integrity notice:** The supplied dataset is fictional and
> covers the Users entity only. Any findings from that dataset describe
> the supplied file, not actual VELOOP performance. Product events,
> fields, KPIs, and controls are proposals or items to be verified; this
> project does not claim that they are implemented in production.

## Overview

The project defines a traceable analytical foundation for a rewards
product. It documents what data should be collected, how it can be
modelled and validated, which metrics can be calculated, and what
engineering and product teams would need to confirm before relying on
production reporting.

### Key deliverables

-   Product data audit and data coverage matrix
-   User, earning, reward, wallet, withdrawal, referral, and engagement
    analytics specifications
-   Event tracking plan and data dictionary
-   Logical data model and ER diagram
-   KPI catalogue with reproducible definitions
-   Simulated data profiling and data quality audit
-   Dashboard blueprint and visual specifications
-   Developer analytics handoff
-   Data pipeline proposal
-   Privacy and governance proposal
-   Assumption and verification register
-   Analytics readiness assessment
-   Implementation backlog
-   Executive summary and final consolidated report

## Project highlights

-   **54 proposed KPIs** with documented definitions and formulas
-   **42 proposed events** for analytics tracking
-   **128 documented fields** across **10 proposed entities**
-   **39 proposed data quality rules**
-   **7 dashboard concepts** covering **56 planned visuals**
-   **43 prioritised implementation backlog items**

These are counts of documented project artefacts, not measurements of
VELOOP's live product.

## Technology

-   HTML
-   CSS
-   JavaScript
-   Static PDF documents
-   Vercel for static hosting (optional)

The site is static; it does not require a Node.js backend or a database
to display the documentation.

## Repository contents

The deployed folder should keep the HTML entry point and its PDF
documents together so the document links continue to work.

``` text
velop-rewards-analytics/
├── index.html
├── Executive_Summary.pdf
├── 02_Product_Data_Audit.pdf
├── 03_Data_Coverage_Matrix.pdf
├── 04_User_Analytics_Specification.pdf
├── 05_Earning_Reward_Analytics_Specification.pdf
├── 06_Wallet_Withdrawal_Analytics_Specification.pdf
├── 07_Referral_Engagement_Analytics.pdf
├── 08_Event_Tracking_Plan.pdf
├── 09_Data_Dictionary.pdf
├── 10_Logical_Data_Model.pdf
├── 11_KPI_Catalogue.pdf
├── 12_Simulated_Data_Profiling.pdf
├── 13_Data_Quality_Audit.pdf
├── 14_Dashboard_Blueprint.pdf
├── 15_Developer_Analytics_Handoff.pdf
├── 16_Data_Pipeline_Proposal.pdf
├── 17_Privacy_Governance_Proposal.pdf
├── 19_Assumption_Verification_Register.pdf
├── 20_Analytics_Readiness_Assessment.pdf
├── 21_Implementation_Backlog.pdf
└── Final_Consolidated_Report.pdf
```

**Note:** Keep the actual filenames and relative paths in the repository
consistent with the links inside `index.html`. Deliverables 12 and 14
are included as PDFs only; their spreadsheet files are intentionally
excluded from this package. The KPI Catalogue spreadsheet is not
required for the static site unless you choose to add it separately.

## Run locally

1.  Download or clone this repository.
2.  Ensure `index.html` and the linked PDF files are in the expected
    locations.
3.  Open `index.html` in a browser.

For a local development server, you can use the VS Code **Live Server**
extension and select **Open with Live Server**.

## Deploy to Vercel

1.  Push the project files to a GitHub repository.
2.  Sign in to [Vercel](https://vercel.com/) and import the repository.
3.  Configure the project as a static site:
    -   **Framework Preset:** Other
    -   **Root Directory:** `./`
    -   **Build Command:** leave blank
    -   **Output Directory:** `./`
    -   **Install Command:** leave blank
4.  Deploy the project.
5.  Open the generated deployment URL and test the HTML page and each
    PDF link.

The file served at the root should be named `index.html` for the default
Vercel URL to open the site directly.

## Data limitations and interpretation

-   The supplied simulated dataset covers the **Users entity only**.
-   The profiling and quality audit therefore describe the supplied
    Users data; they should not be interpreted as production findings.
-   Many KPIs and cross-entity checks cannot be fully tested without the
    other required datasets.
-   Product definitions and implementation details remain proposed or
    require confirmation from VELOOP stakeholders.
-   No production performance figures, targets, or benchmarks are
    claimed by this project.

## Suggested next steps

1.  Review proposed definitions with Product and Engineering.
2.  Confirm identifiers, event availability, reward units, timestamps,
    and lifecycle rules.
3.  Obtain the missing datasets and rerun profiling, KPI tests, and data
    quality checks.
4.  Implement event collection, validation, transformation, and governed
    analytics layers.
5.  Build production dashboards only after the underlying data and
    definitions are verified.

## Author

**Harshit Srivastava**\
B.Tech --- Computer Science and Engineering

## License

No license is specified. Unless a license is added to this repository,
reuse and redistribution are not explicitly granted.
