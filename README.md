# ☁️ NawaCloud ISMS Implementation Portfolio

![Portfolio](https://img.shields.io/badge/Project-Educational%20Simulation-2F75B5)
![Language](https://img.shields.io/badge/Language-English-17365D)
![License](https://img.shields.io/badge/License-MIT-548235)

An end-to-end **Information Security Management System (ISMS) portfolio simulation** for a fictional SaaS provider. The project demonstrates how organizational scope, assets, risks, control decisions, remediation, audit evidence, and management review can be connected in one coherent case study.

> **Simulation notice:** NawaCloud, its people, records, metrics, control states, and evidence references are fictional. This portfolio is for learning and demonstration; it is not a real implementation, audit, certification, or compliance assessment.

## 👤 Author

**Ahmed Ban Harhara**  
✉️ [Ahmed.banharhara@gmail.com](mailto:Ahmed.banharhara@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/ahmed-ban-harhara-285a76264)

## 📌 Contents

- [Scenario and scope](#-scenario-and-scope)
- [Methodology](#-methodology)
- [Portfolio results](#-portfolio-results)
- [Deliverables](#-deliverables)
- [How the work fits together](#-how-the-work-fits-together)
- [Estimated effort](#-estimated-effort)
- [Learning outcomes](#-learning-outcomes)
- [Repository structure](#-repository-structure)
- [License and limitations](#-license-and-limitations)

## 🏢 Scenario and scope

**NawaCloud** is a fictional 24-person SaaS company that provides appointment and booking management for small clinics. In this scenario, the platform handles account and booking details. It does not hold complete clinical records or process payment card data.

The modeled ISMS covers product design, development, testing, deployment, hosting, support, operational data, workforce identities and managed devices, backups, source repositories, cloud services, and suppliers that affect the service. Work is remote. Provider facilities, clinic devices and networks, external clinical systems, and payment services outside NawaCloud's operation are outside the direct boundary; relevant interfaces and suppliers remain in scope for oversight.

## 🧭 Methodology

1. Define the organization, stakeholders, service boundary, and dependencies.
2. Inventory information and technology assets and assign owners and classifications.
3. Identify threat events, enabling conditions, and potential business impacts.
4. Score likelihood and impact from 1 to 5. Inherent risk is `likelihood × impact`: 1–4 Low, 5–9 Medium, 10–16 High, and 17–25 Critical.
5. Select a treatment, owner, due date, supporting controls, and testable closure criteria for each risk.
6. Review each of the 93 control references, document its applicability decision and simulated state, and connect it to relevant risks.
7. Plan remediation and audit activities, then define evidence and management review inputs.

The residual scores and control states are **illustrative targets or assumptions**. They are not results of testing a real company.

## 📊 Portfolio results

| Area | Simulated result |
|---|---:|
| Asset groups | 12 |
| Assessed risks | 12: 1 Critical, 9 High, 2 Medium inherent |
| Control references | 93: 91 included and 2 excluded with rationale |
| Included control states | 74 implemented, 13 partially implemented, 4 planned — all simulated |
| Gap-remediation actions | 17 |
| Audit procedures | 11 |
| Practical exercises | 6 |

## 📦 Deliverables

### 📄 Documents

1. [Executive overview and scope](deliverables/documents/01-ISMS-Executive-Overview-and-Scope.docx)
2. [Risk assessment and treatment methodology](deliverables/documents/02-Risk-Assessment-and-Treatment-Methodology.docx)
3. [ISMS policies and operating procedures](deliverables/documents/03-ISMS-Policies-and-Operating-Procedures.docx)
4. [Incident response and continuity plan](deliverables/documents/04-Incident-Response-and-Continuity-Plan.docx)
5. [Internal audit program and evidence guide](deliverables/documents/05-Internal-Audit-Program-and-Evidence-Guide.docx)
6. [Gap assessment and remediation report](deliverables/documents/06-Gap-Assessment-and-Remediation-Report.docx)
7. [Awareness and training plan](deliverables/documents/07-Awareness-and-Training-Plan.docx)
8. [Management review meeting pack](deliverables/documents/08-Management-Review-Meeting-Pack.docx)
9. [Illustrative ROI and cost-benefit note](deliverables/documents/09-Illustrative-ROI-and-Cost-Benefit-Note.docx)
10. [Implementation and risk checklists](deliverables/documents/10-Implementation-and-Risk-Checklists.docx)

### 📈 Excel workbooks

1. [Statement of Applicability](deliverables/workbooks/01-Statement-of-Applicability.xlsx)
2. [Risk register](deliverables/workbooks/02-Risk-Register.xlsx)
3. [Asset inventory](deliverables/workbooks/03-Asset-Inventory.xlsx)
4. [Gap remediation plan](deliverables/workbooks/04-Gap-Remediation-Plan.xlsx)
5. [Audit and evidence log](deliverables/workbooks/05-Audit-Evidence-Log.xlsx)
6. [Business continuity and disaster recovery](deliverables/workbooks/06-Business-Continuity-and-Disaster-Recovery.xlsx)
7. [Awareness and training plan](deliverables/workbooks/07-Awareness-and-Training-Plan.xlsx)
8. [Management review](deliverables/workbooks/08-Management-Review.xlsx)
9. [Illustrative ROI analysis](deliverables/workbooks/09-Illustrative-ROI-Analysis.xlsx)
10. [ISMS implementation checklist](deliverables/workbooks/10-ISMS-Implementation-Checklist.xlsx)
11. [Risk assessment checklist](deliverables/workbooks/11-Risk-Assessment-Checklist.xlsx)
12. [Performance measurement and findings](deliverables/workbooks/12-Performance-Measurement-and-Findings.xlsx)

### 🎤 Executive presentation

[NawaCloud ISMS executive briefing — 12 slides](deliverables/presentation/NawaCloud-ISMS-Executive-Briefing.pptx)

### 🧪 Practical exercises

The [exercise guide](exercises/README.md) contains six fictional scenarios covering risk assessment, tenant isolation, backup restoration, supplier access, awareness, and audit sampling. Each exercise includes learner tasks and facilitator guidance.

## 🔗 How the work fits together

The source registers in [`registers/`](registers/README.md) hold the editable data. The scope and risk methodology in [`docs/`](docs/) explain the design choices. The risk register links identified risks to treatments and controls; the SoA records control decisions; the gap plan turns partial or planned states into actions; and the audit and evidence materials describe how those actions could be checked. The executive presentation summarizes the case for management.

## ⏱️ Estimated effort

**Estimated portfolio authoring effort:** 120 hours (approximately 30 working days at 4 hours per day, or about 1.5 months). This is separate from the ROI workbook's fictional 960-hour first-year implementation-effort assumption for NawaCloud.

## 🎓 Learning outcomes

This portfolio demonstrates the ability to:

- Define an ISMS scope and identify relevant stakeholders, assets, and dependencies.
- Assess risks and connect treatments to control references and closure tests.
- Explain why controls are included or excluded for a defined scenario.
- Organize remediation, audit procedures, evidence records, and management review.
- Present a consistent security-management case through documents, workbooks, and a briefing.

It demonstrates a **structured educational simulation**, not verified implementation experience at a real organization.

## 🗂️ Repository structure

```text
NawaCloud-ISMS-Implementation-Portfolio/
├── README.md
├── LICENSE
├── docs/                 # Scope, risk, policy, and audit notes
├── deliverables/
│   ├── documents/        # Ten portfolio documents
│   ├── workbooks/        # Twelve Excel workbooks
│   └── presentation/     # Executive briefing
├── exercises/            # Fictional scenarios and facilitator guidance
├── evidence/             # Evidence conventions; no real evidence
├── references/           # Map of reference-project coverage
└── registers/            # Editable CSV source registers and guide
```

## 📜 License and limitations

The project is released under the [MIT License](LICENSE). Its structure was informed by the three supplied reference projects; the NawaCloud scenario and portfolio materials are adapted for this fictional SaaS case.

This repository does not provide legal advice, an audit opinion, certification, or a conformity assessment. No claim is made that the controls have been implemented or tested in an operating organization. A real organization would need to confirm its scope, obligations, risk decisions, control operation, and evidence with accountable people.
