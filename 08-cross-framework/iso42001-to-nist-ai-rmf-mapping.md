# ISO 42001 to NIST AI RMF Mapping

## Purpose

This document maps ISO/IEC 42001:2023 to the NIST AI Risk Management Framework.

The purpose is to show how ISO 42001 provides the AI management system structure, while NIST AI RMF provides detailed AI risk management methodology.

## Framework Relationship

ISO/IEC 42001 is a certifiable AI Management System standard.

NIST AI RMF is a voluntary AI risk management framework structured around four core functions:

- GOVERN
- MAP
- MEASURE
- MANAGE

ISO 42001 helps establish the management system, responsibilities, policies, audits, reviews, and continual improvement.

NIST AI RMF helps identify, assess, measure, and manage AI risks in detail.

## High-Level Mapping

| ISO 42001 Area | NIST AI RMF Function | Relationship |
|---|---|---|
| Clause 4 - Context | MAP | Defines organisational context, interested parties, AI system scope, and affected stakeholders |
| Clause 5 - Leadership | GOVERN | Establishes AI policy, accountability, roles, and governance commitment |
| Clause 6 - Planning | MAP and MEASURE | Identifies AI risks, assesses impacts, and defines measurable AI objectives |
| Clause 6.1.2 - AI Risk Assessment | MAP | Identifies and categorises AI-specific risks |
| Clause 6.1.4 - AI Impact Assessment | MAP and MEASURE | Assesses impacts on people, groups, users, and society |
| Clause 6.2 - AI Objectives | MEASURE | Defines KPIs for monitoring AI governance performance |
| Clause 7 - Support | GOVERN | Establishes AI competence, communication, and awareness |
| Clause 8 - Operation | MANAGE | Implements AI controls and operational governance |
| Annex A Controls | GOVERN and MANAGE | Provides selected AI controls for lifecycle, data, transparency, oversight, and suppliers |
| Clause 9 - Performance Evaluation | MEASURE | Reviews AI performance, audit results, and management review evidence |
| Clause 10 - Improvement | MANAGE | Handles incidents, nonconformities, corrective actions, and continual improvement |

## Detailed Mapping

| ISO 42001 Deliverable | NIST AI RMF Function | Connection |
|---|---|---|
| AIMS Scope Statement | MAP | Defines the AI system boundary and operational context |
| Context Analysis | MAP | Identifies internal and external factors affecting AI risk |
| Interested Parties Register | MAP | Identifies affected parties and their AI-related needs |
| AI Policy | GOVERN | Establishes responsible AI principles and governance expectations |
| AI Roles RACI | GOVERN | Defines AI ownership, accountability, and responsibilities |
| Management Commitment Statement | GOVERN | Demonstrates leadership commitment to AI governance |
| AI Risk Register | MAP and MANAGE | Identifies, scores, owns, and treats AI risks |
| AI Impact Assessment | MAP and MEASURE | Assesses AI effects on users, clients, vulnerable groups, and society |
| AI Objectives and KPIs | MEASURE | Defines measurable AI performance indicators |
| AI Competence Framework | GOVERN | Ensures staff have appropriate AI literacy and role-specific competence |
| AI Communication Plan | GOVERN | Supports awareness, transparency, and stakeholder communication |
| Statement of Applicability | MANAGE | Documents selected controls and implementation status |
| Internal Audit Report | MEASURE | Evaluates whether controls are implemented and effective |
| Management Review Minutes | MEASURE and MANAGE | Reviews AIMS performance and improvement decisions |
| Nonconformity and Incident Register | MANAGE | Records AI failures, root causes, and corrective actions |
| Continual Improvement Plan | MANAGE | Uses lessons learned to improve AI governance |

## AI Risk Examples

| AI Risk | ISO 42001 Treatment | NIST AI RMF Connection |
|---|---|---|
| Hallucination | Risk register, accuracy KPI, impact assessment, incident process | MAP identifies risk, MEASURE tracks accuracy, MANAGE treats risk |
| Prompt injection | Annex A controls, red team evidence, technical safeguards | MAP identifies adversarial risk, MEASURE tests controls, MANAGE implements treatment |
| Bias and unfair outputs | AI impact assessment and bias testing | MAP identifies affected groups, MEASURE evaluates fairness |
| Privacy leakage | AI Policy, DPO involvement, data governance controls | GOVERN defines accountability, MANAGE applies privacy controls |
| Transparency failure | AI disclosure controls and incident register | GOVERN defines transparency expectations, MANAGE handles failures |
| Supplier dependency | Supplier AI governance and contractual clauses | MAP identifies third-party risk, MANAGE treats supplier risk |

## Key Observations

- ISO 42001 is stronger for management system structure, documentation, audit, and certification readiness.
- NIST AI RMF is stronger for detailed AI risk methodology and trustworthiness analysis.
- ISO 42001 Clause 6 maps strongly to NIST MAP and MEASURE.
- ISO 42001 Annex A maps strongly to NIST GOVERN and MANAGE.
- Together, both frameworks provide a strong AI governance portfolio story.

## Summary

ISO 42001 and NIST AI RMF are complementary.

For EugTech Solutions Ltd, ISO 42001 provides the formal AI Management System, while NIST AI RMF provides detailed AI risk management thinking across GOVERN, MAP, MEASURE, and MANAGE.

## Status

Status: Implemented  
Project: ISO/IEC 42001:2023 AIMS Portfolio Project
