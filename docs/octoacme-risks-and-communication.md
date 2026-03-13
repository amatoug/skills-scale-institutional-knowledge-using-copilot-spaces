# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies.

## Risk Register
Maintain a simple table with:
- ID
- Description
- Impact (High/Med/Low)
- Likelihood (High/Med/Low)
- Owner
- Mitigation plan
- Status

## Risk Lifecycle
- Identify: during planning and ongoing execution
- Assess: estimate impact and likelihood
- Mitigate: reduced via actions, contingency plans
- Monitor: review at weekly syncs and update status

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support)
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status

## Communication Templates
Weekly Status Template:
- Progress this week:
- Next steps:
- Risks & blockers:
- Ask / decisions needed:

Incident Communication
- Triage summary
- Actions being taken
- Expected timeline
- Post-incident blameless retrospective scheduled

## Escalation Paths
- Team-level -> PM -> Product Lead -> Sponsor
- For security incidents, follow the security incident runbook and notify Security on-call

### Expanded Escalation Matrix

| Level | Trigger | Owner | Escalates To | Timeframe |
|-------|---------|-------|-------------|-----------|
| **L1 – Team** | Blocker identified; impedes one person or task | Developer / QA / Designer | Project Manager (if unresolved in 1 day) | Same-day standup |
| **L2 – PM** | Risk threatens sprint delivery or a cross-team dependency | Project Manager | Product Manager + Tech Lead | Within 24 hours |
| **L3 – Leadership** | Risk threatens milestone, budget, or business outcome | Project Manager + Product Manager | Stakeholder / Sponsor | Within 24 hours; async summary required |
| **Security** | Critical vulnerability or data exposure identified | Security Champion | Project Manager + dedicated Security team | Immediate; follow security runbook |

### Role-Specific Escalation Responsibilities

- **Developers**: raise technical blockers in standup (L1); flag security findings to the Security Champion immediately
- **QA / Test Engineer**: escalate critical defects blocking release readiness to Project Manager (L2)
- **Tech Lead / Architect**: escalate design-blocking technical risks to Product Manager and PM (L2)
- **Security Champion**: own all security escalations; follow security incident runbook for any critical finding
- **UX / Designer**: escalate usability blockers preventing acceptance sign-off to Product Manager (L2)
- **Stakeholder**: provides L3 approval authority and can unblock organizational dependencies
