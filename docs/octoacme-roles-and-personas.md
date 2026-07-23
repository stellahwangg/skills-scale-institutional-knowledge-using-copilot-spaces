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

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Additional Personas (proposed additions)

Below are cross-functional and specialized roles to be added. For each persona we provide: short role summary, responsibilities, typical deliverables, and interactions with existing roles.

### Technical Program Manager (TPM)
Role summary:
- Coordinates cross-team technical dependencies, timelines, and escalations for complex or multi-team initiatives.

Responsibilities:
- Own cross-team milestones and dependency tracking.
- Facilitate technical tradeoff discussions and decision tracking.
- Run cross-team escalations and track remediation progress.

Typical deliverables:
- Cross-team dependency tracker, milestone plan, escalation log.

Interactions:
- Works closely with PMs, Engineering Leads, Release Manager, and Program stakeholders to ensure alignment and unblock technical progress.

### Engineering Lead / Tech Lead
Role summary:
- Owns technical design, architecture, and engineering quality for the project.

Responsibilities:
- Define and communicate technical approach and architecture.
- Review and approve designs and PRs, mentor developers.
- Identify technical risks and propose mitigations.

Typical deliverables:
- Technical design docs, architecture diagrams, code review approvals.

Interactions:
- Partners with Developers on implementation, advises PdM on technical tradeoffs and estimation, and coordinates with DevOps for deployments.

### Release Manager
Role summary:
- Plans and coordinates releases and deployment activities to production.

Responsibilities:
- Maintain deployment schedule and release checklist.
- Coordinate release verification, rollback plans, and communications.
- Ensure required approvals and readiness are in place before deployment.

Typical deliverables:
- Release checklist, deployment runbook, rollback plan, post-release verification report.

Interactions:
- Coordinates with DevOps, QA Lead, PM, PdM, and Support Liaison to schedule and execute releases.

### DevOps / Platform Engineer
Role summary:
- Maintains CI/CD pipelines, infrastructure, and production observability.

Responsibilities:
- Implement and maintain pipelines, infra-as-code, and monitoring.
- Support deployments and incident response.
- Improve platform reliability and automation.

Typical deliverables:
- CI/CD configurations, runbooks, monitoring dashboards.

Interactions:
- Works with Developers and Release Manager to ensure deployments succeed and respond to incidents with Engineering Leads.

### Security Liaison
Role summary:
- Integrates security requirements and reviews into project planning and execution.

Responsibilities:
- Review threat models and security scans; surface blockers and mitigations.
- Ensure security gating is considered early in design.
- Coordinate with Security on-call for incidents.

Typical deliverables:
- Security review notes, scan remediation plans, threat model artifacts.

Interactions:
- Engages with Engineering Leads, PdM, and QA Lead to incorporate security criteria into acceptance and deployment gating.

### Data Analyst / Measurement Lead
Role summary:
- Defines success metrics, implements tracking, and validates measurable outcomes.

Responsibilities:
- Design and validate event/metric schemas and dashboards.
- Implement instrumentation and verify data quality.
- Analyze results to inform product decisions.

Typical deliverables:
- Metrics definitions, dashboards, validation reports, measurement plan.

Interactions:
- Partners with PdM to define success criteria and with Developers to implement instrumentation.

### QA Lead / Test Owner
Role summary:
- Defines test strategy, manages test coverage, and coordinates manual and automated testing.

Responsibilities:
- Create test plans and acceptance gating criteria.
- Coordinate manual QA and ensure adequate automation coverage.
- Sign off on release readiness from a quality perspective.

Typical deliverables:
- Test strategy, test cases, QA sign-off, automation reports.

Interactions:
- Works with Developers, Release Manager, and PM to validate acceptance criteria and manage test execution.

### UX Researcher / Designer
Role summary:
- Provides user research, design guidance, and validates UX acceptance criteria.

Responsibilities:
- Conduct research and usability testing; produce design assets and flows.
- Define UX acceptance criteria and participate in design reviews.
- Ensure accessibility and usability considerations are included.

Typical deliverables:
- Research reports, wireframes, prototypes, design specs.

Interactions:
- Collaborates with PdM, Developers, and QA to ensure UX goals are met.

### Support Liaison / Customer Success Representative
Role summary:
- Represents customer perspective and coordinates post-release feedback and prioritization.

Responsibilities:
- Triage customer issues and prioritize fixes or improvements.
- Communicate release information to support and customers.
- Collect usage feedback and escalate critical issues.

Typical deliverables:
- Customer impact reports, prioritized post-release issue lists, stakeholder communications.

Interactions:
- Works with PM, PdM, and Engineering to ensure customer issues are tracked and addressed.

### Accessibility / Localization Lead (as needed)
Role summary:
- Ensures features meet accessibility and localization requirements.

Responsibilities:
- Review designs and implementations for accessibility compliance and localization readiness.
- Coordinate tests and provide remediation guidance.

Typical deliverables:
- Accessibility checklists, localization guidance, compliance notes.

Interactions:
- Engages with UX, Developers, QA, and PdM to ensure accessibility/localization acceptance criteria are met.

---

## How to use these additional personas
- Add a short entry for each persona in the process document (summary, responsibilities, interactions).
- Link personas to acceptance criteria and checklists (release, security, analytics) so handoffs are explicit.
- During planning, tag backlog items with required personas for sign-off (e.g., requires Security Liaison review).
