### Loan Tracker App (Salesforce)

Admin & automation focused demo project.

This GitHub showcases demo projects and learning artifacts, not proprietary client work.

## Project overview

This is a Salesforce Loan Tracker demo built to showcase **admin** and platform configuration skills rather than live production implementation.
It focuses on how a Salesforce Admin models loan data, enforces business rules, and automates workflows using standard platform features such as Flows, validation rules, and reporting.

## Key Salesforce features used

- Custom objects and fields to represent loans, customers, and repayment schedules.
- Validation rules to enforce data quality, business constraints, and guardrails on loan inputs.
- Record types and page layouts tailored for different loan lifecycle stages (application, approved, disbursed, closed).
- Flows (Screen and Record-Triggered) to automate loan creation, status updates, and notifications.
- Approval logic (Flow or approval process) for loan sanctioning scenarios.
- Reports and dashboards to track active loans, overdues, and pipeline visibility for stakeholders.

## Flows and automation

- Record-triggered Flows to set default values, calculate amounts (e.g., EMI, total payable), and maintain consistent status transitions.
- Screen Flows to guide users through structured loan intake, review, and decision steps.
- Automated emails and tasks for follow-ups on overdue EMIs or pending documentation, driven by Flow.
- Optional scheduled automation to maintain summary flags and health indicators on loan records.

## Validation rules and data quality

- Mandatory capture of loan-critical fields (income, interest rate, tenure, loan amount, risk band) beyond simple page-layout requirements.
- Range checks and conditional logic ensuring values stay within business-defined thresholds.
- Contextual validations based on loan type or segment (for example, collateral required for certain loan categories).

## Reporting and dashboards

- Reports for active, closed, and delinquent loans filtered by user, branch, or segment.
- Summary reports grouped by product, salesperson, or risk category to support GTM and operations teams.
- Example dashboards to visualize portfolio health, overdue volume, and recent loan creation trends.

## What this project demonstrates to hiring teams

- Ability to translate a business use case (loan lifecycle) into Salesforce data model, Flows, validation rules, and reports.
- Practical admin-first mindset: configuration and automation are preferred before code, aligning with maintainable Salesforce delivery.
- Hands-on experience designing Flows, approvals, and validations that reduce manual effort and prevent data issues.
- Awareness of reporting needs for sales, operations, and management, with examples that can be extended in real orgs.
- Clear, concise documentation that a team could understand, review, and build on during hiring assessments.
