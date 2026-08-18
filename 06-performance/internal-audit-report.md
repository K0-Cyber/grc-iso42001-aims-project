# Internal Audit Report

## Purpose

This document records the internal audit of EugTech Solutions Ltd's Artificial Intelligence Management System.

It supports ISO/IEC 42001:2023 Clause 9.2, which requires the organisation to conduct internal audits at planned intervals.

## Audit Details

| Field | Details |
|---|---|
| Organisation | EugTech Solutions Ltd |
| Standard | ISO/IEC 42001:2023 |
| Audit Reference | AIMS Audit 2026-01 |
| Audit Date | January 2026 |
| Auditor | Eugene Akamanquah |
| Audit Type | Internal AIMS audit |
| Scope | Mandatory ISO 42001 clauses 4-10 and selected Annex A controls |
| Method | Document review, staff interviews, AI system testing, and configuration inspection |

## Audit Scope

The audit reviewed the following areas:

- AIMS scope and organisational context
- Interested parties and requirements
- AI Policy
- AI roles and responsibilities
- AI risk register
- AI impact assessment
- AI objectives and KPIs
- AI competence framework
- Communication plan
- Annex A Statement of Applicability
- AI incident and nonconformity records
- Continual improvement process

## Audit Conclusion

The AIMS demonstrates strong foundational implementation with good technical controls and clear governance documentation.

Key gaps were identified in supplier management, AI competence verification, and logging completeness.

## Audit Findings

| Ref | Clause | Finding Type | Description | Corrective Action |
|---|---|---|---|---|
| F-01 | A.4.6 Screening | Minor Nonconformity | Enhanced screening for AI roles is defined in policy but has not yet been applied to existing staff in AI roles. It has only been applied to new hires since policy launch. | Apply AI ethics awareness assessment to all existing staff in AI roles within 60 days. Update HR records. |
| F-02 | A.6.2.8 Logging | Minor Nonconformity | EugAI interaction logs do not capture model confidence scores consistently. Approximately 15% of interactions are missing this field due to API response format variation. | Fix confidence score extraction in API response parser. Backfill where possible. Achieve 100% capture within 30 days. |
| F-03 | A.10.3 Supplier | Observation | Supplier AI governance questionnaire has been sent to the LLM API provider, but specific EU AI Act GPAI compliance evidence has not yet been received. | Escalate to API provider account manager. Set 30-day deadline. If not received, raise with legal team for contract enforcement. |
| F-04 | 6.2 Objectives | Observation | AI KPIs are defined, but no formal dashboard exists. Reporting to board is narrative rather than data-driven. | Build KPI dashboard using a spreadsheet as a minimum. Present data-driven KPI report at next management review. |

## Findings Summary

| Finding Type | Count |
|---|---:|
| Minor Nonconformity | 2 |
| Observation | 2 |
| Major Nonconformity | 0 |
| Total Findings | 4 |

## Strengths Identified

| Area | Strength |
|---|---|
| AIMS scope | Scope is clearly defined and includes in-scope and excluded AI systems |
| AI Policy | Policy includes responsible AI principles and leadership approval |
| AI Risk Register | AI risks are documented with likelihood, impact, residual risk, owners, and status |
| AI Impact Assessment | EugAI impact assessment includes vulnerable group considerations |
| Annex A controls | Selected controls are documented in a Statement of Applicability |
| Governance | Roles and responsibilities are clearly assigned |

## Corrective Action Tracking

| Ref | Owner | Due Date | Status |
|---|---|---|---|
| F-01 | HR Manager | 60 days | Open |
| F-02 | AI Engineering Lead | 30 days | Open |
| F-03 | IT Manager / ISM | 30 days | Open |
| F-04 | ISM | Next management review | Open |

## Audit Opinion

The AIMS is suitable for continued operation, subject to timely completion of corrective actions.

No major nonconformities were identified.

The organisation should prioritise logging completeness, competence evidence, supplier assurance, and KPI dashboard reporting.

## Status

Status: Implemented  
ISO 42001 Mapping: Clause 9.2  
Project: ISO/IEC 42001:2023 AIMS Portfolio Project
