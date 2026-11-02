# Nexus Financial Services – Risk-Based Annual Audit Plan and ISO/IEC 27001 Audit Program

![ISO 27001](https://img.shields.io/badge/ISO%2FIEC-27001%3A2022-blue)
![GRC](https://img.shields.io/badge/Focus-GRC%20%7C%20Risk%20%7C%20Compliance-green)
![Project](https://img.shields.io/badge/Project-Security%20Auditing-orange)
![Status](https://img.shields.io/badge/Status-Proposal-yellow)

## Project Overview

This project presents a risk-based annual internal audit plan and an ISO/IEC 27001:2022 audit program for Nexus Financial Services, a fictional financial services organization.

The proposal establishes a structured approach to prioritizing information security audits, assessing control effectiveness, reviewing the Information Security Management System (ISMS), and monitoring corrective actions.

The audit cycle covers **1 November 2026 to 31 October 2027**.

## Problem Statement

Nexus Financial Services identified several information security and governance concerns:

- Employees retaining system access after role changes.
- Inconsistent completion of quarterly access reviews.
- Incomplete security incident records.
- Overdue supplier security assessments.
- Unresolved findings from previous audits.
- Limited internal audit resources requiring risk-based prioritization.

The project addresses these concerns by developing an audit plan that prioritizes areas according to their likelihood and potential impact.

## Project Objectives

- Develop a risk-based annual internal audit plan.
- Identify and prioritize key information security risks.
- Establish an ISO/IEC 27001:2022-aligned audit program.
- Define audit scope, objectives, procedures, and evidence requirements.
- Establish sampling approaches for audit testing.
- Support corrective action tracking and follow-up.
- Provide a framework for monitoring audit performance.

## Key Features

### 1. Risk-Based Audit Planning

The audit plan uses a likelihood and impact scoring methodology.

**Risk Score = Likelihood × Impact**

| Risk Score | Classification |
|---|---|
| 21–25 | Critical |
| 15–20 | High |
| 8–14 | Medium |
| 1–7 | Low |

Five priority audit areas were selected for full audit coverage:

| Priority Audit Area | Risk Score | Rating |
|---|---:|---|
| Access lifecycle and access reviews | 25 | Critical |
| Previous audit findings and corrective actions | 20 | High |
| Security incident records and management | 20 | High |
| Supplier security assessments | 16 | High |
| ISMS governance, risk management and Statement of Applicability | 15 | High |

Other areas receive targeted coverage or are deferred based on available resources and risk priorities.

### 2. Annual Audit Schedule

The proposed audit cycle covers 12 months.

| Period | Planned Activity |
|---|---|
| November 2026 | Planning and scoping |
| December 2026 – January 2027 | Access lifecycle and access reviews |
| February 2027 | Previous audit findings |
| March – April 2027 | Incident management |
| May – June 2027 | Supplier security |
| July 2027 | ISMS governance, risk and Statement of Applicability |
| August 2027 | Retesting high and critical findings |
| September 2027 | Reporting |
| October 2027 | Annual close-out |

**Resource allocation:** 48 planned auditor-days and 8 contingency days, for a total of 56 days.

### 3. ISO/IEC 27001:2022 Audit Program

The audit program addresses the ISMS requirements under Clauses 4–10 and applicable Annex A controls identified through the Statement of Applicability.

The proposed ISMS scope includes:

- People, processes, information and technology supporting financial services.
- Lagos headquarters and remote employees.
- Cloud applications.
- Payment systems.
- Identity and remote-access management.
- Security incident management.
- Third-party and supplier relationships.

### 4. Detailed Audit Procedures

The audit program defines six procedures:

| Audit ID | Audit Area | Key Activities |
|---|---|---|
| AP-01 | Access lifecycle and reviews | Review joiner, mover and leaver processes, approvals, access removal, privileged accounts and quarterly reviews. |
| AP-02 | Previous audit findings | Review corrective actions, ownership, root causes, implementation evidence and recurring findings. |
| AP-03 | Incident management | Examine incident records, reporting, investigation, escalation and notification processes. |
| AP-04 | Supplier security | Review supplier inventories, due diligence, contractual security requirements and overdue assessments. |
| AP-05 | ISMS governance and risk | Examine ISMS scope, risk assessments, risk treatment, governance, objectives and Statement of Applicability. |
| AP-06 | Follow-up and effectiveness retesting | Verify completed corrective actions and assess whether identified weaknesses have been effectively addressed. |

### 5. Audit Methodology

The proposed audit methodology includes:

- Document and policy reviews.
- Interviews with relevant personnel.
- Observation of processes and controls.
- Sampling and evidence examination.
- Process walkthroughs.
- Authorized control testing.
- Follow-up testing of corrective actions.

Audit evidence is assigned unique workpaper identifiers and stored in a restricted repository.

## Standards and Frameworks Referenced

- ISO/IEC 27001:2022 – Information Security Management Systems.
- ISO 19011:2026 – Guidelines for auditing management systems, as cited in the source report.
- Personal Data Protection Act (NDPA) 2023.
- Central Bank of Nigeria cybersecurity requirements, where applicable.
- Payment Card Industry Data Security Standard (PCI DSS).
- ISACA IT Audit Framework (ITAF).
- IIA Global Internal Audit Standards 2024.

## Tools and Deliverables

The primary deliverable is a structured Microsoft Word audit planning and audit program report.

The project also identifies supporting audit documentation requirements, including:

- Risk assessment and prioritization.
- Annual audit schedule.
- Audit procedures.
- Evidence and workpaper documentation.
- Corrective action follow-up.
- Audit performance monitoring.

## Corrective Action Management

The proposal establishes corrective action timelines according to finding severity:

| Finding Classification | Proposed Timeline |
|---|---|
| Critical / Major | Containment within 5 working days; action within 30 days |
| High / Minor | 60 days |
| Medium / Observation | 90 days |
| Low / Opportunity | 180 days or as agreed |

## Monitoring and Performance Measures

The proposed audit program includes quarterly monitoring and annual review.

Suggested performance measures include:

- Percentage of planned engagements completed on schedule.
- Timeliness of audit reporting.
- Corrective action closure rates.
- Effectiveness of implemented corrective actions.

The proposed target is at least 90% of planned engagements completed on schedule.

## Project Status and Limitations

This document represents a proposed audit plan and audit program for review and approval.

It does not represent:
- A completed internal audit.
- Verified operating effectiveness of the organization's controls.
- ISO/IEC 27001 certification.
- Formal approval by executive management or the Audit and Risk Committee.

Nexus Financial Services is a fictional organization used for this project.

## Suggested Repository Structure

```text
nexus-financial-services-audit/
│
├── README.md
├── documents/
│   └── annual-audit-plan-and-audit-program.docx
│
├── supporting-materials/
│   ├── risk-register.xlsx
│   ├── annual-audit-schedule.xlsx
│   └── corrective-action-tracker.xlsx
│
└── references/
    └── standards-and-frameworks.md
