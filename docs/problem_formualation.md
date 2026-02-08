# Step 4: Problem Formulation — Loan Approval System

This document defines the loan approval problem in a structured
and explainable manner before any machine learning is applied.

The purpose of this step is to clarify what decision the AI system
must make, what information it can use, and what constraints it
must respect.

---

## Decision Definition

The AI system is required to make a binary decision for each loan
application:

- Approve the loan
- Reject the loan

This decision will later be supported by predictive models and
explainable reasoning mechanisms.

---

## Input Information (State)

Each loan application is described using the following information:

- Applicant and co-applicant income
- Loan amount and repayment term
- Credit history
- Employment and education status
- Number of dependents
- Property area

These variables collectively represent the financial capability,
risk profile, and contextual background of the applicant.

---

## Actions

The system can perform one of the following actions:

- Approve the loan
- Reject the loan

No intermediate actions are allowed.

---

## Constraints

The decision-making process must consider the following constraints:

- Applicants with missing or poor credit history present higher risk
- Loan amounts that are high relative to income increase default risk
- Sensitive attributes must not introduce unfair bias
- Incomplete or uncertain data must be handled conservatively

---

## Objective

The primary objectives of the system are:

- Maximize approval of creditworthy applicants
- Minimize financial risk due to defaults
- Maintain fairness and transparency
- Enable clear and human-understandable explanations

---

## Expected Outcome

For each application, the system should be able to provide:

- A loan approval or rejection decision
- A confidence estimate for the decision
- An explanation describing the key factors influencing the decision

---

## Notes

At this stage:
- No machine learning models are trained
- No predictions or performance metrics are generated

This formulation acts as the foundation for search-based reasoning,
machine learning, and explainable AI components in later steps.