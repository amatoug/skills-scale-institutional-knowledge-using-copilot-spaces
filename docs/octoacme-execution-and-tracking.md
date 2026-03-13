# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies
- Weekly delivery sync — show progress, updates, and flagged risks
- Demo/Review at the end of each sprint or milestone

### Standup Agenda Template
> **What did I complete since last standup?**
> **What am I working on today?**
> **Are there any blockers or dependencies I need help with?**

Role-specific focus areas:
- **Developers**: code progress, PR reviews pending, blockers
- **QA / Test Engineer**: test execution status, defects found, release readiness signals
- **Tech Lead / Architect**: design review progress, technical blockers
- **Security Champion**: security scan results, active vulnerability remediation
- **UX / Designer**: design review readiness, dev implementation questions

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)

## Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed

## Definition of Done (DoD)

A backlog item is considered **Done** only when all of the following are true:

| Criterion | Owner |
|-----------|-------|
| All acceptance criteria verified and passed | QA / Test Engineer + Product Manager |
| Unit and integration tests written and passing in CI | Developer |
| No critical or high-severity defects open | QA / Test Engineer |
| Security scans passing; no new critical vulnerabilities | Security Champion |
| Code reviewed and approved (≥1 reviewer) | Tech Lead / Architect or Developers |
| PR merged to main/target branch | Developer |
| Feature flag or rollout configuration verified (if applicable) | Developer + Project Manager |
| Release notes or changelog entry drafted | Project Manager |
| Documentation updated (user-facing or technical) | Developer or UX / Designer |

> Teams may extend this list with project-specific criteria. Document any additions in the project repo.

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- Level 1: Team-level triage in daily standup
- Level 2: PM escalates to Product Lead and dependent teams
- Level 3: Sponsor-level escalation for business-impacting issues

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly
