# Bytepay — AI Governance Deliverables

**A synthetic case study in AI governance, risk assessment and policy design for a Nigerian payments business.**

> **Disclosure:** Bytepay is a fictional organisation created for portfolio purposes. All systems, figures, risks and departmental structures described here are illustrative. This repository demonstrates governance methodology and documentation practice, not work performed for a real client, and does not constitute legal or regulatory advice.

---

## Purpose

This repository holds the governance artefacts produced for the Bytepay case study, kept under version control so that changes to each document are visible and traceable. Governance work is only credible if it can be shown to be maintained, so this repository is the living record rather than a static set of files.

## Regulatory and framework basis

The assessment draws on two complementary sources:

- **NIST AI Risk Management Framework (AI RMF 1.0)** — the methodological spine: govern, map, measure and manage, applied to each AI system in scope.
- **Nigeria Data Protection Act 2023** — the binding obligations that apply to the processing of personal data within the assessed systems, including lawful basis, data subject rights and cross-border transfer.
- **Financial services regulatory and governance considerations** — sector expectations for model risk, outsourcing, consumer protection and board accountability in a licensed payments environment.

Using a voluntary international framework alongside binding domestic law is deliberate: the AI RMF supplies structure where Nigerian AI-specific regulation is still developing, while the NDPA supplies enforceable obligations that any governance programme must satisfy today.

## Deliverables

| # | Deliverable | Format | Link |
|---|---|---|---|
| 1 | Risk assessment register with treatment strategies (v2) | PDF | [Register (PDF)](deliverables/01-risk-assessment-register/Bytepay_AI_Risk_Assessment_Register.pdf) |
| 1a | Risk assessment register workbook (v2, editable) | XLSX | [Register (XLSX)](deliverables/01-risk-assessment-register/Bytepay_AI_Risk_Assessment_Register.xlsx) |
| 2 | AI governance policy | — | Pending upload |
| 3 | Departmental roles and responsibilities | PDF | [Roles and responsibilities](deliverables/03-roles-and-responsibilities/Bytepay_Departmental_Roles_and_Responsibilities.pdf) |
| 4 | Project summary (executive summary) | PDF | [Project summary](deliverables/04-executive-summary/Bytepay_Project_Summary.pdf) |
| 5 | Main project report | PDF | [Main project report](deliverables/05-main-project-report/Bytepay_Main_Project_Report.pdf) |

The register is provided in two forms: a PDF for reading and an editable XLSX so the working document, including its scoring model and controls, can be inspected.

## Repository structure

```
/
├── README.md                  This file
├── CHANGELOG.md               Record of changes to each deliverable
├── deliverables/
│   ├── 01-risk-assessment-register/     Register PDF + editable XLSX
│   ├── 02-ai-governance-policy/         Pending
│   ├── 03-roles-and-responsibilities/
│   ├── 04-executive-summary/
│   └── 05-main-project-report/
└── LICENSE.md
```

## Change control

Every revision to a deliverable is recorded in `CHANGELOG.md` with a date and a short description of what changed and why. Superseded versions remain in the commit history rather than being overwritten silently.

## Licence

Documentation is shared for portfolio and educational purposes. See `LICENSE.md` for terms.
