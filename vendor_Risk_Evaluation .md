# Vendor Security Evaluation Report

**Vendor Name:** SaaS Cloud Solutions, Inc.
**Service Provided:** Customer Relationship Management (CRM) Platform
**Data Classification:** Confidential (Contains Customer PII and Financial Records)
**Assessor:** GRC Analyst
**Date:** August 2026

---

## 1. Executive Summary
A third-party security evaluation was conducted on SaaS Cloud Solutions, Inc. to review their security controls prior to contract renewal. Assessment artifacts included their latest SOC 2 Type II report and CAIQ security submission.

## 2. Compliance Findings
* **SOC 2 Type II Report:** Reviewed for audit period Jan 2025 – Jan 2026. Issued by an independent CPA firm with zero noted control exceptions in Common Criteria.
* **Data Protection:** Verified encryption at rest using AES-256 and in transit using TLS 1.3.
* **Disaster Recovery:** Vendor conducts annual DR testing with a documented Recovery Time Objective (RTO) under 4 hours.

## 3. Identified Gaps & Recommendation
* **Gap:** Vendor does not currently support SSO integration on their entry tier.
* **Recommendation:** **Conditionally Approved.** Approval requires vendor commitment to mandate MFA for all administrator logins and enable SSO integration within 90 days.
