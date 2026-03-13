# OctoAcme — Onboarding Guide

## Purpose
Help new team members get up to speed quickly on OctoAcme's project management processes, tools, and expectations. This guide provides a structured path from day one to active contribution.

---

## Before You Start

Confirm with your manager or Project Manager that you have access to:

- [ ] GitHub organization and relevant repositories
- [ ] GitHub Projects board for the current project
- [ ] Team communication channels (Slack/Teams/other)
- [ ] CI/CD system and deployment tools
- [ ] Design tools (e.g., Figma) — if applicable to your role
- [ ] Security tooling and scanning dashboards — if applicable to your role

---

## Week 1: Understand the Project

### 1. Read the core docs (in order)

| Step | Document | What you'll learn |
|------|----------|------------------|
| 1 | [Project Management Overview](octoacme-project-management-overview.md) | Principles, lifecycle, and key artifacts |
| 2 | [Roles & Personas](octoacme-roles-and-personas.md) | Your role and how it interacts with others |
| 3 | [RACI Matrix](octoacme-raci-matrix.md) | Your responsibilities across each project phase |
| 4 | [Project Initiation Guide](octoacme-project-initiation.md) | How projects are started and approved |
| 5 | [Project Planning](octoacme-project-planning.md) | How work is planned, estimated, and tracked |
| 6 | [Execution & Tracking](octoacme-execution-and-tracking.md) | Day-to-day workflow, PR standards, and Definition of Done |
| 7 | [Risk Management & Communication](octoacme-risks-and-communication.md) | Risk register, escalation paths, and communication templates |
| 8 | [Release & Deployment Guide](octoacme-release-and-deployment.md) | Release types, deployment checklist, and rollback procedures |
| 9 | [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | How the team learns and improves |

### 2. Review the current project

- Read the Project One-pager (found in the project repo or docs)
- Review the active project board on GitHub Projects
- Review open pull requests to understand the current state of the codebase
- Attend the next standup (observe if it is your first day; participate from day two onward)

### 3. Schedule 1:1s with key team members

| Who | What to discuss |
|-----|----------------|
| Project Manager | Current sprint goals, blockers, communication norms |
| Product Manager | Product vision, backlog priorities, acceptance criteria standards |
| Tech Lead / Architect | Codebase overview, branching strategy, coding standards |
| QA / Test Engineer | Test strategy, how to run the test suite, current defect priorities |
| Security Champion | Security scanning tools, secure coding practices for the project |
| UX / Designer | Design system, how to access design files, design review process |

---

## Week 2: Contribute

### Branching & Pull Request Standards

1. Branch naming convention: `<type>/<short-description>` (e.g., `feat/add-login-flow`, `fix/null-pointer-crash`)
2. Keep PRs small (≤400 lines when possible)
3. Every PR must include:
   - Link to the related GitHub issue
   - Summary of what changed and why
   - Acceptance criteria from the issue
   - Test evidence (screenshots, test run output, or CI link)
4. Request at least one reviewer (Tech Lead or teammate)
5. Do not merge your own PR without approval

### Definition of Done Checklist

Before marking a task as Done, verify:

- [ ] All acceptance criteria met (confirmed with QA / Test Engineer)
- [ ] Unit and integration tests written and passing in CI
- [ ] No critical/high defects open against this feature
- [ ] Security scans passing (no new critical vulnerabilities)
- [ ] PR reviewed and approved
- [ ] Documentation updated (if user-facing or architectural change)
- [ ] Release notes entry drafted (coordinate with Project Manager)

### Communication Norms

| Channel | Used for |
|---------|---------|
| Daily standup | Progress, blockers, handoffs |
| GitHub Issues | Bug reports, feature requests, task tracking |
| GitHub Pull Requests | Code review, design review, QA sign-off |
| Weekly sync | Status updates, risk review, stakeholder alignment |
| Slack/Teams | Quick questions, informal coordination (not decisions) |

> All decisions should be recorded in GitHub Issues, PRs, or project docs — not left in chat.

---

## Role-Specific Quick-Start

### If you are a Developer
1. Run the test suite locally and confirm all tests pass
2. Review the coding standards and PR template in the project README
3. Claim your first task from the "Ready" column in GitHub Projects
4. Pair with the Tech Lead for your first PR review

### If you are a QA / Test Engineer
1. Review the current test plan and identify any coverage gaps
2. Set up the automated test suite locally
3. Review open defects in the issue tracker and triage any unclassified bugs
4. Coordinate with the Product Manager to verify acceptance criteria for items in "In Review"

### If you are a Tech Lead / Architect
1. Review existing Architecture Decision Records (ADRs) in the docs
2. Identify and document any undocumented architectural decisions
3. Schedule a brief design review with the team to introduce yourself and align on standards
4. Review the risk register for any outstanding technical risks

### If you are a UX / Designer
1. Access the design system and component library files
2. Review designs for in-flight work and identify any open design questions
3. Schedule a design review walkthrough with the Product Manager
4. Attend the next sprint demo to understand how designs are being implemented

### If you are a Security Champion
1. Review CI security scanning configuration and current open alerts
2. Familiarize yourself with the security runbook and escalation path
3. Review the security section of the risk register
4. Schedule a brief sync with the Tech Lead to align on security architecture priorities

### If you are a Product Manager
1. Review the product roadmap and backlog
2. Confirm success metrics and acceptance criteria for the current sprint items
3. Schedule alignment meetings with Stakeholders for the upcoming milestone review
4. Review user research notes or feedback backlog

### If you are a Project Manager
1. Review the current project plan, risk register, and open action items
2. Set up recurring ceremonies (standup, weekly sync, retrospective) if not already scheduled
3. Introduce yourself to Stakeholders and confirm communication preferences
4. Review the project board and confirm all in-flight items are correctly tracked

---

## Key Contacts & Escalation

Refer to the [Risk Management & Communication](octoacme-risks-and-communication.md) doc for the full escalation matrix. Quick summary:

| Situation | Who to contact |
|-----------|---------------|
| Technical blocker | Tech Lead / Architect |
| Unclear acceptance criteria | Product Manager |
| Defect or quality concern | QA / Test Engineer |
| Security vulnerability found | Security Champion (immediately) |
| Design or usability question | UX / Designer |
| Schedule / delivery risk | Project Manager |
| Business priority conflict | Product Manager + Stakeholder |

---

## Onboarding Completion Checklist

- [ ] All core process docs read
- [ ] GitHub Projects board reviewed and access confirmed
- [ ] 1:1s completed with all key roles
- [ ] First PR submitted and merged
- [ ] Attended at least one standup, one weekly sync, and one demo/review
- [ ] Attended a retrospective (or reviewed the retrospective notes from the last one)
- [ ] Added to the project communication channels
- [ ] Role-specific quick-start steps completed
