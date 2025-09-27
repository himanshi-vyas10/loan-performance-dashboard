# loan-performance-dashboard
## overview

This project provides an end-to-end analysis of loan applications and performance metrics using Excel. The dashboards help uncover insights into borrower behavior, loan risks, and repayment performance, providing data-driven recommendations for financial institutions.


## Tech Stack

Excel → Data cleaning, analysis, KPI calculations, dashboard creation

Power Query → Data transformation & automation

Pivot Tables & Charts → KPI aggregation and visualization

Conditional Formatting & Formulas → Risk segmentation and dynamic metrics


## Dataset

Source: Kaggle – Loan Data Dataset

Raw Data Sheet: Contains the original dataset with borrower, loan, and repayment details

Design Sheet: Shows step-by-step KPI calculations and formulas

Overview Dashboard: High-level summary of loan portfolio performance

Summary Dashboard: Deeper breakdown by loan purpose, term, and borrower risk



## Insights

1. The bank received 38.6K total loan applications, showing a 6.91% MoM growth.

2. A total of $435.8M was funded, with a 13.04% MoM increase, outpacing applicant growth.

3. $473.1M was received, with a 15.84% MoM increase, indicating strong repayment performance.

4. Good loans = 86.18% while bad loans = 13.82%. Around 5.3K applications worth $65.5M fall into the bad loan category,
   with only $37.3M recovered.

5. Of closed loans, 32.1K were fully paid, but 5.3K were charged off. Around 14% of closed loans end in default, showing        relatively strong repayment performance but still room for reducing bad loans.

6. The average interest rate is 12.05%, with a 3.47% MoM decline, signaling competitive offers but reduced profitability.

7. The average DTI is 13.33%, with a 2.73% MoM improvement. Borrowers appear healthier, but some still show high leverage.

8. Debt consolidation (18.2K) and credit card refinancing (5.0K) dominate loan purposes, together making up nearly 60% of       total applications.

9. 36-month loans (28.2K) are much more popular than 60-month loans (10.3K) — nearly 73% of borrowers prefer short-term         loans.

10. Home Ownership : Renters represent the largest segment of applicants (~48% or 18.4K), significantly outweighing
    mortgage owners (~45% or 17.2K) and outright owners (~7% or 2.8K).

11. Employment Length : Applicants with short tenure (<1 year and 2 years) comprise over 50% of volume, while the
    stable 10+ years segment shows 15% month-over-month growth.

12. By Month (Applications Trend) : Loan applications are rising at 6.91% MoM with peaks in March, June, and September

    

## Recommendations

1. Strengthen credit scoring models and implement stricter eligibility checks to maintain portfolio quality.

2. Balance approval growth with risk controls by segmenting high-risk borrowers.

3. Sustain repayment efficiency with digital reminders, auto-debit systems, and restructuring options.

4. Reduce bad loan ratio to <10% through predictive analytics and enhanced recovery mechanisms.

5. Introduce risk-based pricing and stronger follow-ups to reduce charge-offs.

6. Apply differentiated pricing → lower rates for low-risk customers, slightly higher for risky profiles.

7. Encourage low-DTI applicants with loyalty discounts while capping loans for high-DTI borrowers.

8. Diversify portfolio into small business, education, and home improvement loans.

9. Incentivize long-term loans (fee waivers, bundled insurance) for stable revenue streams.

10. Develop specialized credit assessment models and loan products for the large renter segment to better serve
    this key market and mitigate potential risk.

11. Offer 0.5-1% rate discounts to the growing 10+ years employment segment (now 15% of monthly inflows) to secure
    low-risk assets. 

12. Align marketing campaigns and product launches with these peak months to maximize approvals.


## Dashboards Included

Overview Dashboard → Portfolio performance, growth trends, loan quality

Summary Dashboard → Loan purposes, term preferences, repayment breakdown

Design Sheet → KPI logic, formulas, and calculations

Raw Data Sheet → Original Kaggle dataset


## How to Use

1. Clone this repository or download the Excel file.


2. Open in Excel.


3. Navigate to:

Overview Dashboard → for top-level metrics

Summary Dashboard → for detailed breakdowns

Design Sheet → to understand KPI calculations



4. Interact with slicers and filters to explore trends by loan purpose, state, term, or borrower profile.
