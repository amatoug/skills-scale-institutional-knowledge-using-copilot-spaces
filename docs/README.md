# OctoAcme Project Management Docs

A central entry point connecting all OctoAcme project management processes, standards, and workflows. This README accelerates onboarding, clarifies where process knowledge lives, and ensures repeatable access for all team members.

---

## Overview of OctoAcme Project Management Processes

OctoAcme's project management approach is anchored in a structured lifecycle encompassing five phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Retrospective & Continuous Improvement**. The organization emphasizes a customer-first mindset, iterative delivery in small increments, clear ownership across cross-functional teams, and data-informed decision-making. Psychological safety is prioritized to encourage open feedback and continuous learning, supporting a culture of experiment-driven improvement.

Key workflows leverage **GitHub Projects** for tracking work across standardized columns (Backlog, Ready, In Progress, In Review, QA, Done), along with standardized pull request practices: small, linked PRs (≤400 lines), clear acceptance criteria, automated CI testing, and at least one approval before merging. Quality assurance spans unit, integration, and end-to-end tests, security scanning in CI, and manual QA for feature acceptance. Risks are escalated through a defined path: Level 1 team-level triage during standups, Level 2 PM escalation to the Product Lead, and Level 3 sponsor-level escalation for business-impacting issues.

Communication flows through a structured cadence: daily standups (15 minutes focused on progress and blockers), weekly syncs between PM and Product Lead, twice-weekly delivery team standups, and monthly stakeholder updates. After each sprint, release, or milestone, retrospectives capture learnings and convert them into actionable improvements tracked in the project backlog.

### Key Roles

| Role | Responsibilities |
|------|-----------------|
| **Project Manager** | Coordinates delivery, manages risks, facilitates meetings, and ensures status transparency |
| **Product Manager** | Owns vision, prioritizes the backlog, and validates outcomes |
| **Developers** | Build, test, and deliver features to defined acceptance criteria |
| **QA / Test Engineer** | Validates acceptance criteria, manages test plans, triages defects, and maintains CI quality gates |
| **Tech Lead / Architect** | Provides technical direction, enforces engineering standards, and mentors the development team |
| **Stakeholder** | Provides business context, participates in milestone reviews, and champions the project |
| **Security Champion** | Promotes secure coding practices, conducts threat modeling, and monitors security scanning results |
| **UX / Designer** | Conducts user research, creates design specifications, and ensures accessible, consistent experiences |

---

## Index of Process Documents

| Document | Description |
|----------|-------------|
| [Project Management Overview](octoacme-project-management-overview.md) | High-level introduction to OctoAcme's PM approach, principles, and lifecycle |
| [Project Initiation Guide](octoacme-project-initiation.md) | Steps to validate work, align stakeholders, and create a lightweight plan |
| [Project Planning](octoacme-project-planning.md) | Turning an approved initiative into a backlog, estimates, and Definition of Done |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Day-to-day team rhythm, GitHub Projects workflow, and PR standards |
| [Risk Management & Communication](octoacme-risks-and-communication.md) | Risk register, escalation paths, and stakeholder communication templates |
| [Release & Deployment Guide](octoacme-release-and-deployment.md) | Pre-release checklist, deployment steps, rollback playbook, and release notes |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Sprint/release retrospective format and tracking improvements |
| [Roles & Personas](octoacme-roles-and-personas.md) | Detailed responsibilities, goals, and communication patterns per role |
| [RACI Matrix](octoacme-raci-matrix.md) | Accountability chart mapping all roles to key project activities |
| [Onboarding Guide](octoacme-onboarding-guide.md) | Step-by-step guide for new team members joining an OctoAcme project |

> For full details on any process, see the linked documents above.
