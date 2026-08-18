# Nonconformity and Incident Register

## Purpose

This document records nonconformities and AI incidents identified during operation of EugTech Solutions Ltd's Artificial Intelligence Management System.

It supports ISO/IEC 42001:2023 Clause 10.1, which requires the organisation to manage nonconformities and corrective actions.

## Register Overview

| Field | Details |
|---|---|
| Organisation | EugTech Solutions Ltd |
| Register Owner | AI Management Representative / ISM |
| Standard | ISO/IEC 42001:2023 |
| Clause Mapping | Clause 10.1 |
| Review Frequency | Monthly and during management review |

## Nonconformity and Incident Register

| Ref | Date | Type | Description | Severity | Root Cause | Corrective Action | Status | Owner |
|---|---|---|---|---|---|---|---|---|
| NC-01 | Jan 2026 | Nonconformity | AI literacy training completion below 100% target | Medium | No escalation process for non-completions. Line managers were not notified. | Escalation process created. Line managers notified for all staff over 14 days overdue. | In Progress | HR Manager |
| NC-02 | Jan 2026 | Nonconformity | Logging confidence score capture at 85% | Medium | API response format variation not handled in parser code. | Parser updated to handle all response formats. Monitoring in place. | Closed | AI Engineering Lead |
| INC-01 | Feb 2026 | AI Incident | EugAI produced incorrect pricing information for 2 client queries | Medium | Knowledge base contained outdated pricing page. | Outdated pricing content removed. Monthly content review added to calendar. Affected clients notified. | Closed | Head of Product |

## Severity Definitions

| Severity | Definition |
|---|---|
| High | Significant customer, legal, regulatory, privacy, security, or fairness impact |
| Medium | Moderate operational, governance, or service quality impact |
| Low | Minor issue with limited impact and straightforward corrective action |

## Corrective Action Requirements

For each nonconformity or AI incident, EugTech must:

- Record the issue
- Assign an owner
- Identify the root cause
- Define corrective action
- Set a target date
- Track status
- Verify effectiveness
- Update the AI Risk Register if required
- Update the AIMS documentation where required

## Root Cause Analysis

| Ref | Root Cause Category | Explanation |
|---|---|---|
| NC-01 | Process gap | Training completion monitoring existed, but escalation for overdue training was not defined |
| NC-02 | Technical implementation gap | API response parser did not handle all response formats |
| INC-01 | Content governance gap | Knowledge base review did not identify outdated pricing content before AI used it |

## Status Summary

| Status | Count |
|---|---:|
| Open | 0 |
| In Progress | 1 |
| Closed | 2 |
| Total | 3 |

## Management Review Input

This register provides input to:

- AIMS management review
- Internal audit
- AI risk register updates
- Continual improvement planning
- Supplier and system owner reviews
- KPI reporting

## Status

Status: Implemented  
ISO 42001 Mapping: Clause 10.1  
Project: ISO/IEC 42001:2023 AIMS Portfolio Project
