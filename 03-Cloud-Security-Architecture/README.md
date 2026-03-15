# 03 – Cloud Security Architecture (AWS)

This module provides a healthcare-focused cloud security reference architecture using AWS services. It integrates identity, network segmentation, data protection, monitoring, and incident response into a cohesive model.

## Architecture Components

### 1. Identity & Access Management (IAM)
- Role-based access control (RBAC)
- IAM roles for clinical, administrative, and technical users
- MFA enforced for all privileged accounts
- AWS SSO for centralized identity
- Service Control Policies (SCPs) for guardrails

### 2. Network Segmentation
- VPC with separate subnets for:
  - Clinical applications
  - Administrative systems
  - Analytics and data processing
- Security Groups enforcing least privilege
- NACLs for additional boundary protection

### 3. Data Protection
- Encryption at rest using AWS KMS (S3, RDS, EBS)
- Encryption in transit using TLS 1.2+
- S3 bucket policies preventing public access
- PHI-tagged resources with automated compliance checks

### 4. Logging & Monitoring
- CloudTrail enabled for all regions
- GuardDuty for threat detection
- Security Hub for centralized findings
- CloudWatch alarms for high-severity events
- Centralized log bucket with restricted access

### 5. Incident Response
- Automated alerts for:
  - Public S3 buckets containing PHI
  - IAM anomalies
  - GuardDuty high-severity findings
- Playbooks for containment and recovery
- Forensics-ready logging configuration

## Objective

Provide a secure, scalable, and healthcare-ready cloud architecture that aligns with regulatory requirements and supports modern clinical operations.
