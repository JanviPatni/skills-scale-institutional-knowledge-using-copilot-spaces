# OctoAcme Project Management Docs

Welcome to the OctoAcme project management documentation. This folder contains the canonical processes, templates, and guidance that govern how OctoAcme runs projects from initiation through retrospective and continuous improvement.

## Project Management Processes Overview

OctoAcme follows a structured, lifecycle-based approach to project management that emphasizes customer value, iterative delivery, and clear ownership. The process flows through five core phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. Each phase is governed by defined artifacts and decision gates.

During initiation, teams validate business needs by developing a lightweight Project One-pager that captures the problem statement, SMART goals, success metrics, stakeholder alignment, and initial risk assessment. Once stakeholders approve the initiative, the project moves into planning, where work is broken into shippable increments with prioritized backlogs, acceptance criteria, release timelines, and a Definition of Done.

Execution at OctoAcme is managed through a consistent team rhythm and transparent workflow. Daily standups (15 minutes) focus on progress and blockers, weekly delivery syncs review milestone advancement and flagged risks, and demos occur at sprint or milestone boundaries. Work is tracked via a project board with standardized columns—Backlog, Ready, In Progress, In Review, QA, Done—and pull requests are kept small (≤400 lines when possible) with automated testing, linting, and at least one approval required before merging. Quality is embedded throughout via unit tests, integration tests, smoke tests for critical flows, and security scanning in CI.

OctoAcme defines clear roles and accountability to prevent ambiguity. Project Managers coordinate schedules and risks; Product Managers define outcomes and prioritize the backlog; Developers implement features and identify technical risks; and QA/Testing validates quality. Risk management is proactive with a Risk Register reviewed weekly, and escalation follows a clear hierarchy—team-level → PM → Product Lead → Sponsor. After release and at milestone boundaries, the team holds retrospectives to capture learnings and convert them into actionable improvements.

## Documentation Index

Click on any document below to view the full content:

| Document | Purpose |
|----------|---------|
| [**Project Management Overview**](octoacme-project-management-overview.md) | Concise introduction to OctoAcme's approach, core roles, key artifacts, and lifecycle. Start here for a high-level understanding. |
| [**Project Initiation Guide**](octoacme-project-initiation.md) | Define initial steps to validate and authorize work, align stakeholders, and create a lightweight plan. Includes the Project One-pager template. |
| [**Project Planning**](octoacme-project-planning.md) | Turn an approved initiative into an actionable plan and backlog. Covers kickoff, backlog prioritization, risk identification, and release planning. |
| [**Execution & Tracking**](octoacme-execution-and-tracking.md) | Guidance for managing day-to-day execution, team rhythm, PR workflow, quality standards, and blocker escalation. |
| [**Release & Deployment**](octoacme-release-and-deployment.md) | Standardize how OctoAcme releases features to production. Includes pre-release requirements, deployment checklist, and rollback playbook. |
| [**Risk Management & Communication**](octoacme-risks-and-communication.md) | How to identify, manage, and communicate risks and dependencies. Includes the Risk Register template and escalation paths. |
| [**Retrospective & Continuous Improvement**](octoacme-retrospective-and-continuous-improvement.md) | Capture learnings after each sprint or release and convert them into actionable improvements. |
| [**Roles & Personas**](octoacme-roles-and-personas.md) | Detailed descriptions of typical roles (Developers, Product Managers, Project Managers) and their responsibilities, goals, and communication patterns. |

## How to Use These Docs

- **New to OctoAcme?** Start with the [Project Management Overview](octoacme-project-management-overview.md) for a high-level introduction.
- **Starting a new project?** Follow the [Project Initiation Guide](octoacme-project-initiation.md) and then [Project Planning](octoacme-project-planning.md).
- **In active delivery?** Reference [Execution & Tracking](octoacme-execution-and-tracking.md) and [Risk Management & Communication](octoacme-risks-and-communication.md).
- **Preparing for release?** See [Release & Deployment](octoacme-release-and-deployment.md).
- **Wrapping up or learning?** Check [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md).
- **Understanding roles?** Review [Roles & Personas](octoacme-roles-and-personas.md).

## Updating These Docs

To propose updates, additions, or new process documents, create an issue using the **"Add Content to Project Management Process Docs"** issue template in `.github/ISSUE_TEMPLATE/`. This ensures all process improvements are reviewed, discussed, and tracked.

---

*Last updated: June 2026*
