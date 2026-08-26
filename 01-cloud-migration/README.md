# Lab 01 — ISO 27001 Cloud Migration Risk Assessment

## Scenario

TechStart Inc., a B2B SaaS company, is migrating a customer database containing 5M+ records from on-premises infrastructure to AWS.

The company is pursuing ISO/IEC 27001:2022 certification to meet enterprise client requirements.

As a GRC Analyst, the goal is to:

- Identify critical assets
- Assess migration risks
- Implement security controls aligned with ISO 27001 Annex A
- Create risk treatment plans

## Analogy

### Moving House

I used a moving-house analogy to understand the scenario:

- **On-premises servers** = the old house
- **AWS** = the new house
- **Assets** = the valuable things being moved
- **Risks** = what could go wrong during the move
- **Controls** = the protections used to reduce those risks

Mental model:

**ASSET → RISK → CONTROL**

## Critical Assets

1. Customer Database
2. SaaS Application
3. AWS Credentials

## Key Risks

1. Compromised AWS credentials causing unauthorized access
2. Unencrypted data in transit causing exposure of customer data
3. Inadequate backup and recovery causing data loss
4. Cloud misconfiguration causing unauthorized database access
5. Infrastructure failure causing SaaS downtime

## Security Controls

1. Enforce MFA on privileged AWS accounts
2. Encrypt customer data in transit and at rest
3. Perform and verify backups before migration
4. Enforce secure configuration baselines for AWS resources
5. Maintain redundant cloud resources for critical SaaS services

## ISO 27001 Control Examples

- A.5.17 — Authentication Information
- A.8.24 — Use of Cryptography
- A.8.13 — Information Backup
- A.8.9 — Configuration Management
- A.8.14 — Redundancy of Information Processing Facilities

## Risk Treatment

The primary strategy used in this lab was:

**Mitigate**

The goal was to reduce each identified risk to an acceptable level by implementing specific controls before the production migration.

## What I Learned

This lab helped me understand that GRC risk assessment can be simplified into three questions:

1. What am I protecting?
2. What could happen to it?
3. What can I put in place to reduce the risk?

The moving-house analogy helped me understand the concept before focusing on the technical vocabulary.

---

### Cybersecurity in Rice and Beans

**Complicated terms. Simple explanations.**
