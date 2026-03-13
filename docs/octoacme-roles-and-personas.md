# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## QA / Test Engineer

### Role Summary
QA / Test Engineers own quality assurance across the full delivery lifecycle. They define acceptance criteria alongside Product Managers, design and execute test strategies, and act as the final gate before releases reach production.

### Responsibilities
- Define, document, and maintain test plans and test cases
- Execute manual and automated tests (unit, integration, end-to-end, regression)
- Triage and log defects with clear reproduction steps and severity ratings
- Validate acceptance criteria together with Product Managers before sign-off
- Maintain and improve CI quality gates and automated test suites
- Track and report on defect trends and test coverage metrics

### Goals
- Prevent defects from reaching production
- Continuously improve test coverage and automation
- Provide clear, data-driven quality signals to the team

### Typical Communication
- Defect reports and bug triage in the issue tracker
- Test execution summaries shared after each sprint or release
- Collaboration with Developers on failing tests and acceptance criteria
- Input to retrospectives on quality trends and process gaps

### Interaction with Existing Roles
- Works with **Developers** to review code changes, share failing tests, and clarify acceptance criteria
- Partners with **Product Managers** to validate that delivered features meet user-facing requirements
- Reports quality status and risks to **Project Managers** for escalation decisions
- Participates in sprint ceremonies alongside the full delivery team

---

## Tech Lead / Architect

### Role Summary
Tech Leads and Architects provide technical direction for the project. They make or facilitate key architectural decisions, enforce engineering standards, and mentor developers to ensure the system is reliable, maintainable, and scalable.

### Responsibilities
- Define and document architectural patterns, technology choices, and design constraints
- Conduct and coordinate technical design reviews for significant changes
- Set and enforce coding standards, review guidelines, and Definition of Done criteria
- Identify and mitigate technical risks and long-term maintainability concerns
- Mentor developers and facilitate knowledge-sharing on complex technical topics
- Ensure non-functional requirements (performance, security, scalability) are addressed

### Goals
- Maintain a coherent, sustainable system architecture
- Reduce technical debt while enabling fast, safe delivery
- Grow the technical capability of the team

### Typical Communication
- Architecture Decision Records (ADRs) and technical design documents
- Code review feedback focused on patterns, standards, and long-term maintainability
- Regular syncs with Developers and Project Manager on technical progress and blockers
- Input to sprint planning on complexity, risk, and feasibility

### Interaction with Existing Roles
- Guides **Developers** on design decisions and reviews high-risk code changes
- Advises **Product Managers** on technical feasibility, trade-offs, and effort estimates
- Collaborates with **Project Managers** to surface technical risks early and inform scheduling
- Works with **QA / Test Engineers** to define quality gates and testability requirements
- Partners with the **Security Champion** to embed security into architecture

---

## Stakeholder

### Role Summary
Stakeholders are individuals or groups with a vested interest in the outcome of a project. They provide strategic direction, business requirements, and sign-off authority. Keeping Stakeholders informed and aligned is critical to project success.

### Responsibilities
- Provide business context, goals, and success criteria at project initiation
- Participate in milestone reviews and give timely approvals or feedback
- Raise and prioritize business constraints, compliance requirements, and dependencies
- Champion the project within their organizational area
- Escalate or unblock issues that require organizational authority

### Goals
- Ensure the project delivers measurable business value
- Maintain visibility into progress and risk without being in every meeting
- Drive adoption and support for delivered outcomes across the organization

### Typical Communication
- Monthly stakeholder updates and milestone review meetings
- Executive summaries and high-level status reports from the Project Manager
- Ad-hoc escalation calls when Level 3 business-impacting risks arise
- Release announcements and outcomes summaries

### Interaction with Existing Roles
- Works primarily with **Project Managers** for status updates and escalations
- Engages **Product Managers** on roadmap priorities and trade-offs
- Receives quality and risk signals filtered through the PM layer
- May provide direct acceptance sign-off to **QA / Test Engineers** for critical deliverables

---

## Security Champion

### Role Summary
The Security Champion is a team member—often an experienced Developer or Tech Lead—designated to own security awareness and practices within the delivery team. They act as the primary liaison with any central security or compliance team and ensure security is considered at every stage of development.

### Responsibilities
- Promote secure coding practices and raise security awareness within the team
- Conduct or coordinate threat modeling and security reviews for new features and architecture changes
- Monitor automated security scanning results in CI (SAST, DAST, dependency scanning) and triage findings
- Ensure secrets, credentials, and sensitive data are handled correctly
- Maintain the security section of the risk register
- Liaise with external security or compliance teams when required

### Goals
- Prevent security vulnerabilities from reaching production
- Build a security-conscious culture within the delivery team
- Reduce mean time to detect and remediate security issues

### Typical Communication
- Security review notes attached to design documents and pull requests
- Vulnerability reports and remediation tracking in the issue tracker
- Regular briefings to the Project Manager on security risk posture
- Coordination with the Tech Lead / Architect on security architecture decisions

### Interaction with Existing Roles
- Embedded within the **Developer** team as a peer and coach
- Collaborates with the **Tech Lead / Architect** to embed security into design decisions
- Reports security risks and compliance concerns to the **Project Manager**
- Coordinates with **QA / Test Engineers** to include security test cases in regression suites
- Supports **Product Managers** in understanding security implications of product decisions

---

## UX / Designer

### Role Summary
UX Designers and Designers are responsible for the user experience and visual design of product features. They translate user needs and business requirements into intuitive, accessible interfaces and ensure that delivered features meet usability standards.

### Responsibilities
- Conduct user research, usability studies, and synthesize user feedback
- Create wireframes, prototypes, and high-fidelity design specifications
- Define interaction patterns and ensure design consistency across features
- Collaborate with Product Managers to translate requirements into design solutions
- Work with Developers to ensure accurate, accessible implementation of designs
- Maintain a design system or component library where applicable

### Goals
- Deliver intuitive, accessible, and consistent user experiences
- Reduce user friction and support adoption of new features
- Bridge the gap between user needs and technical implementation

### Typical Communication
- Design files and prototypes shared via the team's design tool (e.g., Figma)
- Design review sessions with Product Managers and Developers before implementation begins
- Acceptance feedback during QA to confirm visual and interaction fidelity
- Participation in user research readouts and retrospective discussions on UX quality

### Interaction with Existing Roles
- Partners closely with **Product Managers** to understand requirements and success metrics
- Hands off design specifications to **Developers** and is available to clarify intent during implementation
- Collaborates with **QA / Test Engineers** to define usability acceptance criteria
- Engages the **Tech Lead / Architect** early to understand technical constraints that affect design
- Presents design decisions and research findings to **Stakeholders** during milestone reviews

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

