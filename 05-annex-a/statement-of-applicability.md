# Annex A Statement of Applicability

## Purpose

This Statement of Applicability documents selected ISO/IEC 42001:2023 Annex A controls for EugTech Solutions Ltd.

It records which controls are applicable, how they are implemented, the evidence available, and the current implementation status.

## Scope

This Statement of Applicability applies to the Artificial Intelligence Management System for EugTech Solutions Ltd.

It covers selected Annex A controls relevant to:

- EugAI customer service chatbot
- Internal AI tools
- AI-assisted code review
- AI supplier governance
- AI data governance
- AI transparency
- AI logging
- Human oversight
- AI security and testing

## Annex A Control Summary

ISO/IEC 42001 Annex A contains AI management controls across control objectives including:

- AI policies
- Internal organisation
- Resources for AI systems
- Assessing impacts of AI systems
- AI system lifecycle
- Data for AI systems
- Information for interested parties
- Use of AI systems
- Third-party and customer relationships

## Statement of Applicability

| Clause | Control | Applicability | Implementation | Evidence | Status |
|---|---|---|---|---|---|
| A.2.2 | AI policy communicated | Applicable | AI Policy v1.0 distributed to all staff at onboarding and annually. Signed acknowledgement required. | AI Policy, acknowledgement records | Implemented |
| A.3.2 | AI-related responsibilities | Applicable | RACI matrix defines all AI responsibilities. Reviewed annually and after organisational changes. | AI Roles RACI, org chart, job descriptions | Implemented |
| A.4.6 | Screening for AI roles | Applicable | Enhanced background checks for staff with AI system admin rights. AI ethics awareness assessment included for AI roles. | HR screening records, interview guides | Partially Implemented |
| A.4.6 | AI awareness and training | Applicable | Annual AI Literacy Training mandatory for all staff. Role-specific training for AI users and owners. Completion tracked. | LMS records, training materials, completion rates | Implemented |
| A.4.2 | AI asset classification | Applicable | AI assets classified, including AI systems, models, training data, prompts, logs, and AI-generated outputs. | Asset inventory, classification policy | Implemented |
| A.4.5 | AI asset protection | Applicable | AI models and training data protected with access controls, encryption, backup, and secure credential storage. | Access control records, Key Vault configuration | Implemented |
| A.10.3 | Supplier AI governance | Applicable | Supplier security questionnaire includes AI-specific questions. LLM API provider assessed against AI governance obligations. | Supplier questionnaire, assessment records | Partially Implemented |
| A.10.2 | Supplier AI contracts | Applicable | AI contractual clauses included in LLM API agreement, including incident notification, compliance evidence, audit rights, and model change notice. | Signed API agreement with AI clauses | Implemented |
| A.6.2.8 | AI system logging | Applicable | EugAI interactions logged, including model version, query content, response, confidence score, and escalation decisions. | Logging configuration, sample log review | Partially Implemented |
| A.6.2.4 | AI system testing | Applicable | Regression testing before knowledge base updates. Accuracy testing monthly. Bias testing quarterly. Red team annually. | Test plans, test results, red team report | Implemented |
| A.9.2 | Human oversight of AI | Applicable | Human escalation mandatory for high-stakes topics, low-confidence responses, user requests, and sensitive queries. AI cannot take actions on accounts. | Escalation trigger documentation, oversight procedures | Implemented |
| A.7.4 | Data quality for AI | Applicable | Knowledge base content reviewed and approved before inclusion. Source documents version-controlled. Outdated content retired on schedule. | Content review records, version control logs | Partially Implemented |
| A.7.2 | Data governance for AI | Applicable | Training data documented by source, date, and preprocessing steps. No client PII in training or RAG data. Data minimisation applied. | Data governance documentation, privacy impact assessment | Implemented |
| A.8.2 | AI transparency to users | Applicable | EugAI displays AI disclosure notice at conversation start. It cannot deny AI nature. Contact for human agent always provided. | Disclosure notice text, red team results | Implemented |
| A.6.2.7 | AI explainability | Applicable | EugAI cites knowledge base source for factual claims. Confidence score shown for uncertain responses. Limitations documented in model card. | Model card, sample outputs showing citations | Partially Implemented |

## Non-Applicable Controls

This portfolio project documents selected Annex A controls most relevant to EugTech's AI use cases.

Controls not listed are treated as not selected for detailed implementation in this simulated project, but would be assessed during a full production ISO/IEC 42001 implementation.

## Status Summary

| Status | Count |
|---|---:|
| Implemented | 10 |
| Partially Implemented | 5 |
| Not Applicable | 0 selected controls |

## Key Observations

- AI policy, roles, asset classification, asset protection, supplier contracts, AI testing, human oversight, data governance, and transparency controls are implemented.
- Supplier AI governance, logging consistency, data quality, screening for AI roles, and explainability require further improvement.
- Partial implementation items are tracked through internal audit, management review, and continual improvement.

## Review Requirements

The Statement of Applicability must be reviewed:

- Annually
- After significant AI system changes
- After AI incidents or nonconformities
- After supplier changes
- During internal audit
- During management review
- When new ISO 42001 or regulatory obligations apply

## Approval

| Role | Name | Approval |
|---|---|---|
| AI Management Representative / ISM | Simulated | Approved |
| CEO | Simulated | Approved |
| Head of Product | Simulated | Reviewed |
| AI Engineering Lead | Simulated | Reviewed |

## Status

Status: Implemented  
ISO 42001 Mapping: Annex A  
Project: ISO/IEC 42001:2023 AIMS Portfolio Project
