# AI Risk Register

## Purpose

This document records AI-specific risks identified for EugTech Solutions Ltd as part of the Artificial Intelligence Management System.

It supports ISO/IEC 42001:2023 Clause 6.1.2, which requires AI risks to be identified, assessed, treated, and reviewed.

## Risk Assessment Methodology

| Parameter | EugTech Approach |
|---|---|
| Risk Identification | Identify AI-specific risks across the lifecycle: data, model, deployment, monitoring, operation, and decommissioning |
| Likelihood Scoring | 1 rare to 5 almost certain |
| Impact Scoring | 1 negligible to 5 critical |
| Risk Rating | Likelihood x Impact |
| Low Risk | 1 to 8 |
| Medium Risk | 9 to 15 |
| High Risk | 16 to 25 |
| Treatment Options | Accept, Treat, Transfer, Avoid |
| Review Frequency | Quarterly or after significant AI system change or incident |

## AI Risk Register

| ID | Asset | AI Threat | Likelihood | Impact | Rating | Control | Residual Risk | Owner | Status |
|---|---|---|---:|---:|---|---|---|---|---|
| AIR-01 | EugAI chatbot | Hallucination causing confident false product advice | 3 | 4 | High: 12 | RAG grounding, monthly accuracy testing, knowledge base review, human escalation | Medium: 6 | Head of Product | In Progress |
| AIR-02 | EugAI chatbot | Prompt injection attack by malicious user | 3 | 4 | High: 12 | Prompt hardening, input monitoring, red team testing, escalation triggers | Low: 4 | AI Engineering Lead | In Progress |
| AIR-03 | LLM API | Third-party model change without notice degrades quality | 3 | 3 | Medium: 9 | Supplier contract clauses, provider monitoring, model change review | Medium: 6 | IT Manager | In Progress |
| AIR-04 | Training data | Biased training data causing unfair outputs | 2 | 4 | Medium: 8 | Bias testing, impact assessment, representative test cases | Low: 3 | ISM | Implemented |
| AIR-05 | EugAI chatbot | User overreliance on AI for high-stakes decisions | 3 | 3 | Medium: 9 | AI disclosure, human escalation, user guidance, limitations notice | Medium: 5 | Head of Product | In Progress |
| AIR-06 | Internal AI tools | Staff using AI to process client PII without safeguards | 3 | 4 | High: 12 | AI Policy, staff training, DPO review, data minimisation controls | Medium: 6 | DPO | In Progress |
| AIR-07 | Code review AI | AI suggesting insecure code patterns | 2 | 4 | Medium: 8 | Secure code review, human approval, engineering standards | Low: 3 | AI Engineering Lead | Implemented |
| AIR-08 | EugAI chatbot | AI denies being AI, causing EU AI Act transparency failure | 2 | 4 | Medium: 8 | AI disclosure notice, system prompt controls, red team testing | Low: 2 | ISM | Implemented |
| AIR-09 | All AI systems | Staff AI literacy gap leading to inappropriate AI use | 4 | 3 | High: 12 | Mandatory AI literacy training, acceptable use guidance, completion tracking | Medium: 6 | HR Manager | In Progress |
| AIR-10 | Project estimation AI | Systematic bias in resource estimates affecting pricing | 2 | 3 | Medium: 6 | Human review, estimation variance checks, periodic audit | Low: 3 | Head of Delivery | Implemented |

## Risk Ownership

| Risk Area | Owner |
|---|---|
| AI governance and AIMS oversight | ISM / AI Management Representative |
| EugAI business performance | Head of Product |
| Technical AI controls | AI Engineering Lead |
| Privacy and personal data | Data Protection Officer |
| Staff training and competence | HR Manager |
| Supplier and IT dependency | IT Manager |
| Delivery and pricing impacts | Head of Delivery |

## Review Requirements

The AI Risk Register must be reviewed:

- Quarterly
- After a significant AI system change
- After an AI incident or nonconformity
- Before deployment of a new AI system
- During internal audit
- During management review

## Summary

This AI Risk Register identifies 10 AI-specific risks across chatbot use, internal AI tools, supplier dependency, privacy, fairness, transparency, staff competence, and AI-assisted decision support.

The highest inherent risks relate to hallucination, prompt injection, staff handling of client PII, and staff AI literacy gaps.

## Status

Status: Implemented  
ISO 42001 Mapping: Clause 6.1.2  
Project: ISO/IEC 42001:2023 AIMS Portfolio Project
