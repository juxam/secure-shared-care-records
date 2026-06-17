# Article 1 Source Map

Working title:

Complete but Controlled: Security and Privacy Implications of Cross-Provider Access to Patient Medical Records in Integrated Healthcare

> Working note: This manuscript is supported by the Article 1 source map, evidence matrix, reading log, care-setting access matrix, data-flow model and risk register.

## Purpose

This document connects each section of Article 1 to the supporting Phase One artefacts.

The purpose is to make sure the manuscript is developed from organised evidence rather than unsupported opinion.

---

## Article 1 Structure and Supporting Files

| Article Section | Main Purpose | Supporting Files | Notes |
|---|---|---|---|
| Abstract | Summarise the article after drafting | article-1-draft.md | Write last |
| 1. Introduction | Introduce the problem and central argument | docs/problem-statement.md, docs/project-charter.md, docs/research-scope.md, policy-context/evidence-matrix.csv | Use this section to explain the tension between clinical availability and privacy/security proportionality |
| 2. Background: Shared Patient Records and Direct Care | Explain shared records, direct care and cross-provider access | policy-context/evidence-matrix.csv, references/reading-log.md | Use NHS Shared Care Records, GP Connect, Summary Care Record and Single Patient Record sources |
| 3. Policy, Governance and Legal Context | Explain UK/NHS governance, UK GDPR, Caldicott, DPIA, DSPT and clinical safety | policy-context/evidence-matrix.csv | Use official sources first |
| 4. Security and Privacy Problem Framing | Explain why wider access creates new risks | references/reading-log.md, threat-models/risk-register-template.csv | Link EHR security/privacy literature to the specific shared-record problem |
| 5. Method | Explain how the article was developed | policy-context/evidence-matrix.csv, care-scenarios/care-setting-access-matrix.md, data-flow-models/dfd-level-0.md, threat-models/risk-register-template.csv | Method = policy/literature analysis + care-context mapping + data-flow modelling + risk register |
| 6. Care-Setting Access Matrix | Compare access needs across care settings | care-scenarios/care-setting-access-matrix.md, care-scenarios/*.md | This can become a table in the article |
| 7. Data-Flow Model | Describe actors, systems, data stores, flows and trust boundaries | data-flow-models/dfd-level-0.md | Later develop Level 1 diagrams |
| 8. Security and Privacy Risk Taxonomy | Group risks into clear categories | threat-models/risk-register-template.csv, threat-models/stride-analysis.md, threat-models/linddun-analysis.md | Use R001–R015 to build the taxonomy |
| 9. Discussion | Interpret the findings | all Phase One artefacts | Discuss complete access versus controlled access |
| 10. Implications | Explain practical implications | threat-models/risk-register-template.csv, framework/framework-overview.md | Link to Article 3 framework |
| 11. Limitations | State what the paper does not yet do | docs/research-scope.md | Mention no interviews or system testing yet |
| 12. Conclusion | Summarise contribution | article-1-draft.md | Emphasise risk taxonomy and future framework |

---

## Core Argument

Integrated patient records should not be evaluated only as interoperability infrastructure. They should also be evaluated as socio-technical security and privacy systems.

The key challenge is not simply to make patient records available. The challenge is to make access necessary, proportionate, secure, auditable, transparent and clinically meaningful.

---

## Article 1 Main Contributions

1. A care-setting access matrix for shared patient-record access.
2. A Level 0 data-flow model for cross-provider patient-record access.
3. An initial security and privacy risk register.
4. A security and privacy risk taxonomy.
5. A policy-grounded discussion of clinical availability versus privacy/security proportionality.

---

## Files to Keep Updated While Writing

- policy-context/evidence-matrix.csv
- references/reading-log.md
- care-scenarios/care-setting-access-matrix.md
- data-flow-models/dfd-level-0.md
- threat-models/risk-register-template.csv
- papers/paper-1-conceptual-policy/article-1-draft.md

---

## Next Writing Priority

The first section to properly develop is:

1. Introduction

The introduction should explain:

- why cross-provider record access matters;
- why GP, ambulance, urgent care, emergency care, secondary care and specialist providers need timely information;
- why complete or near-complete access creates security and privacy risks;
- why this is a socio-technical problem;
- what the article contributes.
