# Enterprise Incident Response Plan
**Document ID:** IRP-SEC-002
**Version:** 1.0
**Framework Alignment:** NIST SP 800-61 Rev. 2

---

## 1. Severity Definitions
* **Low:** Isolated malware detection on a single non-critical endpoint, successfully quarantined by EDR.
* **Medium:** Multiple failed administrative login attempts on internal database systems or suspected credential compromise.
* **Critical:** Active ransomware execution, domain controller compromise, or unauthorized exfiltration of sensitive customer data.

## 2. Containment Procedures
* **Network Isolation:** Immediately isolate compromised hosts from the local network via central EDR console controls.
* **Identity Revocation:** Revoke active SSO session tokens and reset passwords for impacted user accounts in Active Directory.

## 3. Eradication & Recovery
* **Eradication:** Remove malicious artifacts, patch identified software vulnerabilities, and rebuild infected hosts from trusted gold images.
* **Recovery:** Restore verified databases from clean backups, re-enable access in phased batches, and monitor SIEM logs for 72 hours.

## 4. Post-Incident Activity
A mandatory post-mortem review must be conducted within 5 business days of incident resolution to document root cause analysis and update detection rules.

---
[⬅️ Back to README](<./README.md>)
