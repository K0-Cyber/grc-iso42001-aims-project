# AI Impact Assessment for EugAI

## Purpose

This document records the completed AI Impact Assessment for EugAI, EugTech Solutions Ltd's simulated customer service chatbot.

It supports ISO/IEC 42001:2023 Clause 6.1.4, which requires organisations to assess the impact of AI systems on people, groups, and society.

## Assessment Details

| Field | Details |
|---|---|
| AI System | EugAI Customer Service Chatbot |
| Version | 1.0 |
| Organisation | EugTech Solutions Ltd |
| Assessment Date | January 2026 |
| Assessor | AI Management Representative / ISM |
| System Owner | Head of Product |
| ISO 42001 Mapping | Clause 6.1.4 |
| Assessment Status | Completed |

## AI System Description

EugAI is a customer service chatbot used to provide first-line support to EugTech clients.

The system supports:

- Product queries
- Troubleshooting common issues
- Ticket routing
- Knowledge base retrieval
- Human escalation for complex or sensitive queries

## Intended Purpose

The intended purpose of EugAI is to improve first-line customer support by providing fast, consistent, and available responses to common customer service questions.

EugAI is not intended to provide:

- Medical advice
- Legal advice
- Financial advice
- Employment decisions
- Credit decisions
- High-stakes decisions affecting rights or access to services

## Affected Populations

| Population | Description |
|---|---|
| Client employees | Approximately 2,000 users across 20 client organisations |
| Financial services users | Users may operate in regulated business environments |
| Healthcare sector users | Queries may come from organisations serving clinically vulnerable people |
| Retail sector users | Users may rely on fast operational support |
| EugTech support staff | Human agents may review escalations and AI output quality |
| EugTech clients | Client organisations may be affected by service quality and trust |

## Potential Positive Impacts

| Positive Impact | Description |
|---|---|
| Faster query resolution | Users receive immediate answers to common support questions |
| 24/7 support | Customer support is available outside normal working hours |
| Reduced wait times | Human agents can focus on complex cases |
| Consistent responses | Approved knowledge base content can be reused consistently |
| Improved triage | Complex or sensitive issues can be routed to humans |
| Operational efficiency | EugTech can support more client queries with existing resources |

## Potential Negative Impacts

| Impact Area | Potential Negative Impact | Mitigation |
|---|---|---|
| Accuracy | Incorrect information could cause wasted time or operational disruption | RAG grounding, monthly accuracy testing, knowledge base review |
| Fairness | Users with non-standard writing styles may receive lower quality responses | Quarterly bias testing and demographic variant testing |
| Privacy | Users may accidentally submit personal data in queries | PII detection, data minimisation, short retention period |
| Autonomy | Users may over-rely on AI instead of seeking human support | AI disclosure, confidence messaging, human escalation |
| Transparency | Users may not realise they are interacting with AI | AI disclosure notice at conversation start |
| Security | Malicious users may attempt prompt injection or jailbreaks | Prompt hardening, red team testing, monitoring |
| Trust | Poor AI responses may damage client confidence | Monitoring, incident response, management review |

## Vulnerable Group Considerations

Healthcare sector clients may include users who support clinically vulnerable individuals.

To reduce potential harm:

- EugAI must not provide medical advice
- Health-related queries must be escalated to human support
- AI limitations must be clearly disclosed
- Human support must remain available
- Outputs must be monitored for safety and accuracy

## Rights and Equality Considerations

EugAI must provide fair and consistent service regardless of:

- Writing style
- Technical literacy
- Implied gender
- Implied nationality
- Language formality
- Client sector

Quarterly bias testing is used to monitor whether response quality differs across demographic variants.

## Privacy Considerations

EugAI may process user query content that includes personal data.

Privacy mitigations include:

- Data minimisation
- No client PII in training data
- Short retention period for logs
- PII detection and masking
- DPO involvement in privacy-related incidents
- Escalation for sensitive data use

## Assessment Conclusion

EugAI presents a low societal impact risk in its current limited customer service deployment.

The system is approved for deployment with monitoring conditions because it does not make high-stakes decisions, does not change customer accounts, and includes human escalation controls.

## Monitoring Conditions

| Monitoring Requirement | Frequency | Owner |
|---|---|---|
| Bias assessment | Quarterly | ISM / Customer Experience Manager |
| Accuracy testing | Monthly | Head of Product |
| Human review of sampled interactions | Monthly | Customer Experience Manager |
| AI incident review | As required | ISM |
| Knowledge base review | Monthly | Head of Product |
| Full AI impact reassessment | Annually | ISM |

## Approval

| Role | Name | Decision |
|---|---|---|
| AI Management Representative / ISM | Simulated | Approved with monitoring conditions |
| Head of Product | Simulated | Approved |
| Data Protection Officer | Simulated | Approved with privacy controls |

## Status

Status: Implemented  
ISO 42001 Mapping: Clause 6.1.4  
Project: ISO/IEC 42001:2023 AIMS Portfolio Project
