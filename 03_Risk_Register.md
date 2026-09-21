# Enterprise Risk Register

| Risk ID | Threat & Vulnerability Scenario | Inherent (L x I) | Inherent Score | Proposed Security Control | Residual (L x I) | Residual Score | Risk Owner |
| :---: | :--- | :---: | :---: | :--- | :---: | :---: | :--- |
| **RSK-01** | Ransomware deployment via phishing email due to missing endpoint security controls. | 4 x 4 | **16 (High)** | Deploy central EDR agents, restrict local admin rights, and enforce email sandboxing. | 2 x 3 | **6 (Low)** | SecOps Lead |
| **RSK-02** | Customer PII leak caused by publicly misconfigured cloud storage bucket. | 3 x 5 | **15 (High)** | Implement automated IaC scanning in CI/CD pipelines and block public bucket creation globally. | 1 x 4 | **4 (Low)** | Cloud Arch |
| **RSK-03** | Unauthorized access to corporate systems following employee departure. | 3 x 4 | **12 (Med)** | Automate HR-to-IdP offboarding workflow to revoke access tokens within 2 hours of termination. | 1 x 3 | **3 (Low)** | IAM Lead |
| **RSK-04** | Outage of primary customer platform due to critical third-party vendor downtime. | 3 x 3 | **9 (Med)** | Require vendor SOC 2 Availability coverage and enforce 99.9% uptime SLA contracts. | 2 x 3 | **6 (Low)** | GRC Lead |

---
[⬅️ Back to README](<./README.md>)
