# GreenLeaf E-Commerce – Project Methodology

**Author:** Cameron Naidoo  
**Date:** 01 July 2026  
**Project Type:** GRC Portfolio (Simulated Engagement)  
**Duration:** [Start Date] – [End Date]

---

## 1. Executive Summary

This document outlines the methodology used to build the GreenLeaf E-Commerce GRC Portfolio. The project simulated a real-world GRC engagement for a 50-employee online retail company. The objective was to identify security risks, build a compliance framework, and produce actionable deliverables that demonstrate practical GRC skills.

**Key Deliverables:**
- Risk Register with 5 identified risks
- 3 Security Policies (Access Control, Remote Work, Data Classification)
- 3 Compliance Mappings (ISO 27001, NIST CSF, PCI DSS)
- Internal Audit Report with Non-Conformities
- Vendor Risk Assessment (TPRM)
- Data Protection Impact Assessment (DPIA)
- Incident Response Plan + Tabletop Exercise
- GRC Dashboard (Looker Studio)
- Security Awareness Program
- 5 GRC Cheat Sheets

**Frameworks Used:**
- ISO 27001:2022
- NIST CSF 2.0
- NIST SP 800-53
- NIST SP 800-61
- PCI DSS v4.0
- GDPR (EU) 2016/679
- OWASP Risk Rating Methodology

---

## 2. Project Scoping

### 2.1 The Organisation – GreenLeaf E-Commerce

| Attribute | Detail |
| :--- | :--- |
| **Industry** | Online Retail (E-Commerce) |
| **Size** | 50 Employees |
| **Key Assets** | Customer Database, Website, Payment System |
| **Data Processed** | Names, Addresses, Email, Phone, Credit Card Info |
| **Compliance Obligations** | GDPR, PCI DSS (via PaySecure) |

### 2.2 Project Objectives

| Objective | Why It Matters |
| :--- | :--- |
| Identify security risks | Understand what could go wrong and prioritise response. |
| Build a compliance framework | Align GreenLeaf with ISO 27001 and NIST CSF. |
| Draft security policies | Provide enforceable rules for employees. |
| Conduct internal audits | Verify that controls are working. |
| Assess third-party vendors | Ensure partners (PaySecure) meet security standards. |
| Create incident response plan | Prepare for a cyberattack. |
| Build a security awareness program | Train employees to be a human firewall. |
| Produce executive reporting | Translate technical risk into business language. |

### 2.3 Scope Boundaries

| In Scope | Out of Scope |
| :--- | :--- |
| Customer data (PII, payment info) | Physical security (office access) |
| Internal systems (AWS, email, admin) | Network infrastructure design |
| Third-party vendors (PaySecure) | Software development lifecycle |
| Employee behaviour & training | Incident forensics (post-breach) |

---

## 3. Methodology Framework

### 3.1 The 5-Phase GRC Approach

| Phase | Description | GreenLeaf Application |
| :--- | :--- | :--- |
| **1. Discovery** | Identify assets, threats, and vulnerabilities. | Created asset inventory; identified 5 critical risks. |
| **2. Assessment** | Quantify risk (Likelihood × Impact). | Scored risks using 5x5 matrix (Inherent vs Residual). |
| **3. Control Design** | Define policies, standards, and procedures. | Drafted Access Control, Remote Work, Data Classification Policies. |
| **4. Audit & Assurance** | Verify controls are working. | Conducted internal audit; identified 2 Non-Conformities. |
| **5. Continuous Improvement** | Monitor, report, and improve. | Built GRC Dashboard; created quarterly review schedule. |

### 3.2 Risk Assessment Methodology

**Risk Scoring (5x5 Matrix):**

| Likelihood (1-5) | × | Impact (1-5) | = | Inherent Risk Score (1-25) |
| :--- | :--- | :--- | :--- | :--- |

**Severity Scale:**

| Score | Severity | Action Required |
| :--- | :--- | :--- |
| 20–25 | Critical | Immediate executive action (30 days) |
| 15–19 | High | Management action (60 days) |
| 7–14 | Medium | Monitor and review annually |
| 1–6 | Low | Accept and monitor |

**Risk Treatment Options:**

| Option | Definition | When Used |
| :--- | :--- | :--- |
| **Mitigate** | Implement controls to reduce risk | When the risk is high and controls are feasible |
| **Transfer** | Shift risk to third party (e.g., insurance) | When financial impact is high but control is difficult |
| **Accept** | Acknowledge and monitor | When risk is low or mitigation cost exceeds impact |
| **Avoid** | Eliminate the activity entirely | When risk is critical and cannot be controlled |

### 3.3 Policy Development Methodology

**The 3-Tier Policy Hierarchy:**

| Tier | Document Type | Definition | Example |
| :--- | :--- | :--- | :--- |
| **1** | **Policy** | High-level mandatory statement | "GreenLeaf shall enforce MFA" |
| **2** | **Standard** | Measurable technical requirement | "MFA shall use TOTP for all admin accounts" |
| **3** | **Procedure** | Step-by-step guide | "Step 1: Install Google Authenticator..." |

**Policy Development Process:**

1. Identify regulatory and framework requirements (ISO 27001, NIST).
2. Draft policy aligned with industry standards.
3. Review against GreenLeaf's specific risk profile.
4. Ensure enforceability and auditability.

### 3.4 Audit Methodology

**Audit Phases (NIST SP 800-61):**

| Phase | Description | GreenLeaf Application |
| :--- | :--- | :--- |
| **1. Planning** | Define scope, objectives, criteria. | Audited A.8.13 (Information Backup). |
| **2. Evidence Collection** | Request and review evidence. | Reviewed logs, cloud screenshots, testing reports. |
| **3. Findings** | Compare evidence against criteria. | Identified NC-001 (empty cloud bucket) and NC-002 (no testing). |
| **4. Reporting** | Present findings to management. | Drafted formal Non-Conformity Reports. |
| **5. Remediation** | Track corrective actions and verify closure. | Recommended 48-hour cloud migration. |

### 3.5 Vendor Risk Assessment Methodology

**Vendor Tiering Criteria:**

| Criterion | Scoring (1-5) | Weight |
| :--- | :--- | :--- |
| **Data Sensitivity** | 1: Public data, 5: PII/Credit Card | High |
| **Business Impact** | 1: Interruption >30 days, 5: Interruption <24h | High |
| **Risk Transfer** | 1: No insurance, 5: $5M+ insurance | Medium |

**TPRM Assessment Process:**

1. **Tier** – Assign vendor tier (Critical, High, Medium, Low).
2. **Questionnaire** – Send 10-question security questionnaire.
3. **Score** – Apply weighted scoring matrix (max 42 points).
4. **Treat** – Decide: Mitigate, Transfer, Accept, or Avoid.
5. **Monitor** – Ongoing review (quarterly for High/Critical).

---

## 4. Framework Mapping

### 4.1 ISO 27001:2022 Mapping

| Risk ID | Risk Description | ISO 27001 Control | Theme |
| :--- | :--- | :--- | :--- |
| GR-001 | No MFA on admin accounts | A.8.5 Secure Authentication | Technological |
| GR-002 | Manual offboarding delays | A.5.16 Identity Management | Organisational |
| GR-003 | No tested offsite backups | A.8.13 Information Backup | Technological |
| GR-004 | No security awareness training | A.6.3 Awareness & Training | People |

### 4.2 NIST CSF 2.0 Mapping

| Risk ID | NIST CSF Function | NIST CSF Category |
| :--- | :--- | :--- |
| GR-001 | Protect (PR) | PR.AA-01 (Identity & Access Management) |
| GR-002 | Protect (PR) | PR.AA-01 (Identity & Access Management) |
| GR-003 | Recover (RC) | RC.RP-01 (Recovery Plan) |
| GR-004 | Protect (PR) | PR.AT-01 (Awareness & Training) |

### 4.3 PCI DSS Mapping

| PCI DSS Requirement | GreenLeaf Gap | Risk Link |
| :--- | :--- | :--- |
| Req 3: Protect stored account data | Need to ensure no CVV stored in logs | – |
| Req 8: Strong access control | No MFA on admin accounts | GR-001 |

---

## 5. Tools & Technologies

| Tool | Purpose | Phase Used |
| :--- | :--- | :--- |
| **Google Sheets** | Risk Register, Metrics, Visualisations | Discovery, Assessment, Reporting |
| **Google Docs / Markdown** | Policies, Reports, Cheat Sheets | Control Design, Reporting |
| **Google Looker Studio** | GRC Dashboard | Reporting, Continuous Improvement |
| **CISO Assistant** | ISO 27001 mapping, Compliance Report | Control Design, Audit |
| **Canva** | Security Awareness Poster | Control Design |

---

## 6. Quality Assurance

### 6.1 Review Process

| Review Type | Frequency | Reviewer |
| :--- | :--- | :--- |
| **Self-Review** | After each draft | Cameron Naidoo |
| **Alignment Check** | After each artifact | Against NIST, ISO 27001 frameworks |
| **Formatting Review** | Before finalising | Ensure professional, audit-ready formatting |

### 6.2 Validation Criteria

| Criteria | Description |
| :--- | :--- |
| **Completeness** | Does the artifact meet the stated objective? |
| **Accuracy** | Are the facts, scores, and mappings correct? |
| **Clarity** | Is the document easy to read and understand? |
| **Auditability** | Can an auditor use this document to verify compliance? |
| **Actionability** | Does it provide clear next steps? |

---

## 7. Lessons Learned

| Lesson | Why It Matters |
| :--- | :--- |
| **Risk scoring is subjective.** Two analysts may score the same risk differently. Document assumptions. | Ensures consistency and defensibility in audits. |
| **Policies without enforcement are just suggestions.** | Need procedures and accountability for compliance. |
| **Vendors are an extension of your security posture.** | A weak vendor can compromise your entire program. |
| **Executive communication is critical.** | Technical details must be translated into business risk. |
| **Awareness training is the cheapest control.** | Prevents phishing and human error. |

---

## 8. Future State Recommendations

| Recommendation | Priority | Timeline |
| :--- | :--- | :--- |
| Implement MFA on all admin accounts | Critical | Immediate |
| Hire freelance privacy lawyer for GDPR compliance | Critical | 30 days |
| Implement immutable cloud backups | High | 60 days |
| Deploy security awareness training | High | 60 days |
| Automate offboarding process | Medium | 90 days |
| Conduct quarterly risk reviews | Medium | Ongoing |

---

## 9. Conclusion

The GreenLeaf GRC Portfolio was built using a structured, framework-aligned methodology. Every artifact was designed to solve a specific business problem and is backed by industry-recognised standards (ISO 27001, NIST CSF, NIST SP 800-61, PCI DSS, GDPR). The methodology demonstrates:

- **Discovery:** Identifying what matters most.
- **Assessment:** Quantifying risk.
- **Control Design:** Building enforceable policies.
- **Audit:** Verifying controls work.
- **Continuous Improvement:** Monitoring and reporting.

**All artifacts are ready for employer review and can be applied to any organisation requiring GRC expertise.**

---

## 10. References

1. ISO. (2022). *ISO/IEC 27001:2022 – Information Security Management Systems*.
2. NIST. (2018). *NIST Cybersecurity Framework (CSF) v1.1*.
3. NIST. (2020). *NIST SP 800-53 – Security and Privacy Controls*.
4. NIST. (2012). *NIST SP 800-61 – Computer Security Incident Handling Guide*.
5. PCI Security Standards Council. (2022). *PCI DSS v4.0*.
6. GDPR. (2016). *Regulation (EU) 2016/679*.
7. OWASP. *Risk Rating Methodology*.

---

**Prepared by:** Cameron Naidoo  
**Date:** 01 July 2026  
**Version:** 1.0  
**Classification:** Confidential – For Employer Review
