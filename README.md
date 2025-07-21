```mermaid
flowchart TD
    A[Start: Driver Application Eligibility] --> B{Is Age ≥ 18?}
    B -- "No" --> Z[Not Eligible: Must be at least 18 years old]
    B -- "Yes" --> C{Medically Fit?}
    C -- "No" --> Y[Not Eligible: Must be medically fit]
    C -- "Yes" --> D{Citizen, PR, or Valid Pass Holder?}
    D -- "No" --> X[Not Eligible: Must be SG Citizen, PR, or Pass Holder]
    D -- "Yes" --> E[Eligible to Apply for Driver's Licence]

