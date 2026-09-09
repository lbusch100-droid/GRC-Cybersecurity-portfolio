  Framework Standard: NIST SP 800-61 Rev.2 

  Security Levels Defined:
low: Isolated malware detection on a single non critical endpoint.
Medium: Multible failed log in attempts on a care database or unauthorized account access.
Critical: Active ransomware execution, domain controller compromise or data exfiltration.

  How to contain an active breach:
Isolation: Isolate host from network via EDR software and disable network adapter.
Containment: Revoke active session tokens and reset user password in active directory.

  How to eradicate threats: Remove malicious files, rebuild infected OS from golden image, and patch vulnerability.
  How to recover: Restore database from clean backup, reenable system access in phased batches. 

Post incident review: A formal "lessons learned" meeting will occur within the next 3 business days of incident resolution.
