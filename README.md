# GRC Identity & Access Management (RBAC) Matrix

## Objective
To design and document a secure access control model enforcing the **Principle of Least Privilege (PoLP)** across core enterprise systems. This matrix acts as the foundational artifact for Logical Access compliance.

## Project Overview
This project maps 5 distinct business roles (DevOps, Sales, HR, Finance, IT) across 5 critical enterprise systems (AWS, GitHub, Salesforce, Workday, O365). Access tiers were strictly assigned based on job function requirements to minimize insider threat risk and prevent unauthorized lateral movement.

## View the Artifact
[![View RBAC Matrix] (https://github.com/beatricekungu/Beatrice-s-Work/blob/main/RBAC.jpg)

*(Note: Click the button above to view the high-resolution compliance matrix)*

## Framework Alignment
This artifact is designed to satisfy the following compliance and regulatory requirements:
* **SOC 2 (Security & Confidentiality):** CC6.1 - Logical Access Security.
* **ISO 27001:** Annex A.9.1 - Access Control Policy.

## Methodology
The matrix utilizes a standardized permission structure to simplify audit reviews:
- **Admin:** Full read/write/modify/delete permissions.
- **Write:** Authorized to edit and update existing records.
- **Read:** Authorized for view-only access; no data modification.
- **None:** Access restricted; enforces zero-trust architecture.

## Tools Used
* **Microsoft Excel:** Used for data mapping, taxonomy design, and conditional logic.
* **Conditional Formatting:** Applied to provide instant visual risk-identification for auditors.
