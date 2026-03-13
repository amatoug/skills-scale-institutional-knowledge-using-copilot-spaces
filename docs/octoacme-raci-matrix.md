# OctoAcme — RACI Matrix

## Purpose
The RACI matrix clarifies who is **Responsible**, **Accountable**, **Consulted**, and **Informed** for each key project management activity. Use this to resolve ambiguity, reduce duplication of effort, and ensure every activity has a clear owner.

## RACI Key

| Letter | Meaning |
|--------|---------|
| **R** | **Responsible** — does the work |
| **A** | **Accountable** — owns the outcome; final decision authority |
| **C** | **Consulted** — provides input before or during the activity |
| **I** | **Informed** — kept up to date; notified of outcomes |

---

## Initiation Phase

| Activity | Project Manager | Product Manager | Developer | QA / Test Engineer | Tech Lead / Architect | Stakeholder | Security Champion | UX / Designer |
|----------|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| Define problem statement & goals | C | A/R | I | I | C | C | I | C |
| Create Project One-pager | R | A | I | I | C | C | I | C |
| Identify stakeholders & communication plan | A/R | C | I | I | I | C | I | I |
| Conduct initial risk assessment | R | C | C | C | C | I | C | I |
| Approve go/no-go decision | I | A | I | I | C | R | I | I |

---

## Planning Phase

| Activity | Project Manager | Product Manager | Developer | QA / Test Engineer | Tech Lead / Architect | Stakeholder | Security Champion | UX / Designer |
|----------|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| Facilitate kickoff meeting | A/R | C | C | C | C | I | C | C |
| Prioritize and create backlog | C | A/R | C | C | C | I | I | C |
| Write acceptance criteria | C | A/R | C | R | C | I | C | C |
| Estimate effort | C | C | A/R | C | R | I | I | C |
| Define Definition of Done | C | C | R | R | A/R | I | C | C |
| Create release plan & milestones | A/R | C | C | C | C | I | I | I |
| Draft initial test plan | I | C | C | A/R | C | I | C | I |
| Conduct security review / threat modeling | I | C | C | C | C | I | A/R | I |
| Create UX designs & prototypes | I | C | C | C | C | C | I | A/R |

---

## Execution Phase

| Activity | Project Manager | Product Manager | Developer | QA / Test Engineer | Tech Lead / Architect | Stakeholder | Security Champion | UX / Designer |
|----------|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| Implement features | I | I | A/R | I | C | I | I | C |
| Conduct code reviews | I | I | R | I | A/R | I | C | I |
| Write and maintain tests | I | I | R | A/R | C | I | C | I |
| Triage and resolve defects | I | C | R | A/R | C | I | C | I |
| Monitor CI / security scan results | C | I | C | C | C | I | A/R | I |
| Update project board / risk register | A/R | I | C | C | C | I | C | I |
| Facilitate daily standups | A/R | I | C | C | C | I | I | I |
| Facilitate sprint review / demo | A/R | C | C | C | C | I | I | C |
| Validate UX implementation | I | C | C | C | I | I | I | A/R |

---

## Release Phase

| Activity | Project Manager | Product Manager | Developer | QA / Test Engineer | Tech Lead / Architect | Stakeholder | Security Champion | UX / Designer |
|----------|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| Verify all acceptance criteria met | C | A | R | R | C | I | C | C |
| Confirm CI and security scans passing | C | I | C | C | C | I | A/R | I |
| Draft release notes | A/R | C | C | C | I | I | I | I |
| Schedule deployment window | A/R | C | C | I | C | I | I | I |
| Execute deployment | I | I | A/R | C | C | I | C | I |
| Run post-deploy smoke tests | I | I | R | A/R | C | I | C | I |
| Announce release to stakeholders | A/R | C | I | I | I | I | I | I |

---

## Retrospective & Continuous Improvement

| Activity | Project Manager | Product Manager | Developer | QA / Test Engineer | Tech Lead / Architect | Stakeholder | Security Champion | UX / Designer |
|----------|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| Facilitate retrospective | A/R | C | C | C | C | I | C | C |
| Identify action items | C | C | C | C | C | I | C | C |
| Assign and track action items | A/R | C | C | C | C | I | C | C |
| Measure and report on improvements | A/R | C | C | C | C | I | I | I |

---

## Risk & Escalation

| Activity | Project Manager | Product Manager | Developer | QA / Test Engineer | Tech Lead / Architect | Stakeholder | Security Champion | UX / Designer |
|----------|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| Identify and log risks | R | C | C | C | C | I | C | C |
| Assess risk impact and likelihood | A/R | C | C | C | C | I | C | I |
| Define and execute risk mitigations | A/R | C | C | C | C | I | C | I |
| Escalate business-impacting risks | A/R | C | I | I | C | R | I | I |
| Own security risk escalation | C | I | I | C | C | I | A/R | I |

---

## Notes
- A single role should hold the **A** (Accountable) for each activity. If two roles share accountability, escalate to the Project Manager to assign a primary owner.
- This matrix should be reviewed at the start of each project and updated when roles change.
- For full role descriptions see [Roles & Personas](octoacme-roles-and-personas.md).
