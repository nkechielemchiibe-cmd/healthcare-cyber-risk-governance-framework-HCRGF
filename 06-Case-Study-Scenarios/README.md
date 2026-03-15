# 06 – Case Study Scenarios

This module provides realistic healthcare cybersecurity scenarios analyzed through governance, cloud security, and human-factor perspectives. Each scenario demonstrates how the H‑CRGF framework applies in real operational environments.

## Scenario 1: Ransomware in a Hospital Emergency Department

### Summary
A ransomware attack disrupts clinical systems during peak hours, forcing staff to revert to manual workflows.

### Root Causes
- Legacy systems without proper patching
- High operational pressure leading to delayed updates
- Weak segmentation between clinical and administrative networks

### Human-Factor Insights
- Staff fatigue contributed to delayed reporting
- Workarounds increased exposure
- Training gaps in early detection

### Controls That Would Have Prevented It
- Stronger patch governance
- Segmented VPC architecture
- Mandatory phishing and anomaly detection training

---

## Scenario 2: Insider Access to PHI

### Summary
A billing contractor accesses patient records outside their job scope.

### Root Causes
- Excessive access privileges
- Lack of periodic access reviews
- Weak monitoring of user behavior

### Human-Factor Insights
- Poor role clarity
- Inadequate onboarding controls
- No real-time alerts for unusual access

### Controls That Would Have Prevented It
- RBAC with least privilege
- Quarterly access reviews
- CloudTrail + GuardDuty monitoring

---

## Scenario 3: Shadow IT AI Tool Used for Clinical Notes

### Summary
A clinician uses an unauthorized AI tool to summarize patient notes, exposing PHI to an external service.

### Root Causes
- No AI usage policy
- Lack of awareness about PHI risks
- High workload and desire for efficiency

### Human-Factor Insights
- Workflow pressure drove unsafe shortcuts
- Staff assumed the tool was “safe enough”
- No approved alternative provided

### Controls That Would Have Prevented It
- AI governance policy
- Approved clinical documentation tools
- Human-factor risk monitoring

## Objective

Demonstrate how the H‑CRGF framework applies to real healthcare incidents and highlight the importance of governance, cloud security, and human behavior.
