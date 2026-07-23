# OctoAcme Project Management Docs

## Overview

OctoAcme follows a structured, lifecycle-based approach to project management grounded in clear governance and customer value. The framework emphasizes iterative delivery, transparent communication, and data-driven decision-making to enable teams to deliver features reliably while maintaining high quality standards.

### Core Principles
- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager (PM) and Product Manager (PdM)
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Project Lifecycle

OctoAcme projects follow a five-phase lifecycle, each with dedicated guidance:

1. **Initiation** → [Project Initiation Guide](./octoacme-project-initiation.md)
   - Validate business need and measurable outcomes
   - Identify stakeholders and champions
   - Define success criteria and initial timeline

2. **Planning** → [Project Planning](./octoacme-project-planning.md)
   - Break work into shippable increments
   - Identify dependencies and risks
   - Align timelines, releases, and responsibilities

3. **Execution** → [Execution & Tracking](./octoacme-execution-and-tracking.md)
   - Daily standups and weekly syncs
   - GitHub Projects-based workflow management
   - Unit, integration, and end-to-end testing
   - Risk tracking and blocker escalation

4. **Release** → [Release & Deployment Guide](./octoacme-release-and-deployment.md)
   - Standardized deployment with risk mitigation
   - Pre-release requirements and smoke tests
   - Rollback and incident playbooks

5. **Close & Retrospective** → [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
   - Capture learnings and action items
   - Track improvements and measure impact
   - Build continuous improvement culture

## All Process Documents

**Foundation & Roles**
- **[Project Management Overview](./octoacme-project-management-overview.md)** — Core principles, roles, artifacts, and high-level lifecycle
- **[Roles & Personas](./octoacme-roles-and-personas.md)** — Detailed definitions of Developers, Product Managers, and Project Managers, including responsibilities and communication patterns

**Process Guides**
- **[Project Initiation Guide](./octoacme-project-initiation.md)** — Steps to validate and authorize work, align stakeholders, and create a lightweight plan
- **[Project Planning](./octoacme-project-planning.md)** — Turn an approved initiative into an actionable plan and prioritized backlog
- **[Execution & Tracking](./octoacme-execution-and-tracking.md)** — Day-to-day execution, team rhythm, quality assurance, and testing practices
- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** — Risk register, lifecycle, escalation paths, and stakeholder communication strategies
- **[Release & Deployment Guide](./octoacme-release-and-deployment.md)** — Release types, pre-release requirements, deployment checklists, and rollback procedures
- **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** — Capturing learnings, tracking improvements, and building a continuous improvement culture

## Key Workflows & Practices

### Team Rhythm
- **Daily standups** (15 min) — Focus on progress, blockers, and dependencies
- **Weekly delivery sync** — Show progress, updates, and flagged risks
- **Sprint/iteration planning** — Pull items that meet Definition of Done with clear acceptance criteria
- **Demo/Review** — End of sprint or milestone with stakeholders

### Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed

### Communication & Escalation
- **Level 1**: Team-level triage in daily standup
- **Level 2**: PM escalates to Product Lead and dependent teams
- **Level 3**: Sponsor-level escalation for business-impacting issues

**Stakeholder Updates**
- Weekly status updates with progress, next steps, risks, and decisions needed
- Monthly stakeholder briefings
- Ad-hoc incident communication following blameless retrospective model

### Roles & Responsibilities

**Project Manager** — Coordinates delivery, manages schedules, risks, and communications

**Product Manager** — Defines outcomes, prioritizes backlog, and measures success

**Developers** — Implement features, collaborate on design, participate in code reviews, assist in estimation

**QA/Testing** — Validate quality and acceptance criteria

## Getting Started

**New to OctoAcme?**
Start with the [Project Management Overview](./octoacme-project-management-overview.md) to understand core principles and roles.

**Starting a new project?**
Follow the [Project Initiation Guide](./octoacme-project-initiation.md) to validate business need and create your Project One-pager.

**Planning an approved project?**
Use the [Project Planning](./octoacme-project-planning.md) guide to create your prioritized backlog, estimate scope, and define your Definition of Done.

**Managing an active project?**
Reference [Execution & Tracking](./octoacme-execution-and-tracking.md) for daily workflows and [Risk Management & Communication](./octoacme-risks-and-communication.md) for escalation and stakeholder updates.

**Preparing for release?**
Review the [Release & Deployment Guide](./octoacme-release-and-deployment.md) for pre-release requirements, deployment checklists, and rollback procedures.

**Wrapping up a project?**
Follow the [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) guide to capture learnings and drive improvements.

## Issue Templates

Process improvement requests are managed via GitHub issues using the **[Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)** template. This helps track documentation updates, clarifications, and process improvements collaboratively.

## Questions?

If you have questions about OctoAcme processes or need clarification on a specific phase, create an issue using the process docs template or reach out to your Project Manager or Product Lead.
