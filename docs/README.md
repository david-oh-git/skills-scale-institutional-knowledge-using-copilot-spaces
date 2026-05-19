# OctoAcme Project Management Docs

This README provides an entry point to all OctoAcme project management process documentation. It summarizes key processes and offers direct links to each core doc.

## Project Management Process Summary

OctoAcme operates a structured lifecycle approach to project management that spans five distinct phases: Initiation, Planning, Execution, Release, and Close & Retrospective. The Initiation phase focuses on validating business need and stakeholder alignment through a lightweight Project One-pager that captures the problem statement, goals, success metrics, and initial risk assessment. Once approved, the Planning phase breaks work into a prioritized, estimated backlog with clear acceptance criteria and dependencies. Execution follows a team rhythm of daily standups, weekly delivery syncs, and sprint-based iterations, with work managed through a GitHub Projects board organized in columns: Backlog, Ready, In Progress, In Review, QA, and Done. Quality is ensured through a combination of unit tests, integration tests, end-to-end smoke tests, and security scanning in CI, with manual QA applied for feature acceptance when needed.

The organization operates under five core principles—Customer-first prioritization, Iterative delivery, Clear ownership, Data-informed decisions, and Psychological safety—and relies on three primary roles to drive projects forward. The **Product Manager** defines outcomes, prioritizes the backlog, and measures success based on customer and business value. The **Project Manager** coordinates delivery schedules, manages risks and dependencies, and maintains transparent communication across stakeholders. **Developers** implement features collaboratively, write and maintain tests, and help identify technical risks. This clear separation of concerns ensures alignment between product vision and engineering execution.

Communication and risk management are central to OctoAcme's approach. The team operates on a cadence of twice-weekly standups for the delivery team, weekly PM and Product Lead syncs, and monthly stakeholder updates. A Risk Register is maintained throughout the project lifecycle to identify, assess, and monitor risks by impact and likelihood, with escalation paths defined at three levels: team-level triage, PM escalation to Product Lead, and sponsor-level escalation for business-impacting issues. Weekly status updates follow a standard template covering progress, next steps, risks, blockers, and decisions needed, ensuring stakeholders remain informed and aligned.

The Release and Retrospective phases complete the cycle with standardized deployment practices and continuous improvement. Pre-release requirements include passing CI and security scans, drafted release notes, and a documented rollback plan. Post-release, the team conducts retrospectives after each sprint or milestone to capture learnings (what went well, what could improve), identify 2–3 prioritized action items with clear owners and due dates, and track improvements back into the project backlog. This systematic approach to capturing and acting on team feedback creates a culture of continuous learning and iterative enhancement across all OctoAcme projects.

## Docs Index

- [Project Management Overview](octoacme-project-management-overview.md) — Concise introduction to OctoAcme's approach, core roles, key artifacts, and high-level project lifecycle.

- [Project Initiation Guide](octoacme-project-initiation.md) — Initial steps to validate need, align stakeholders, and create a lightweight plan with the Project One-pager template.

- [Project Planning](octoacme-project-planning.md) — Turn approved initiatives into actionable plans, prioritized backlogs, and release timelines with clear acceptance criteria.

- [Execution & Tracking](octoacme-execution-and-tracking.md) — Day-to-day execution guidance including team rhythm, PR workflow, quality practices, metrics, and blocker escalation.

- [Risk Management & Communication](octoacme-risks-and-communication.md) — Risk Register maintenance, lifecycle, stakeholder communication templates, and escalation paths.

- [Release & Deployment Guide](octoacme-release-and-deployment.md) — Standardized release types, pre-release requirements, deployment checklist, rollback procedures, and release notes template.

- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Structure for capturing learnings, tracking action items, and building a continuous improvement culture.

- [Roles and Personas](octoacme-roles-and-personas.md) — Definitions of typical roles (Developers, Product Managers, Project Managers) and their responsibilities, goals, and communication patterns.

## How to Use These Docs

- **New team members**: Start with the [Project Management Overview](octoacme-project-management-overview.md) to understand roles and principles, then refer to phase-specific docs as you progress through projects.
- **Project leads**: Use the [Project Initiation Guide](octoacme-project-initiation.md) and [Project Planning](octoacme-project-planning.md) to set up new projects and checklists.
- **Delivery teams**: Reference [Execution & Tracking](octoacme-execution-and-tracking.md) during active development and [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) after milestones.
- **Risk and communication**: Use [Risk Management & Communication](octoacme-risks-and-communication.md) to maintain registers and stakeholder updates.
- **Release activities**: Follow the [Release & Deployment Guide](octoacme-release-and-deployment.md) for production deployments.

## Adding or Updating Process Docs

If you want to propose changes to existing process docs or add new content, please use the [Process Doc Update issue template](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml). This ensures proposed changes are reviewed and aligned with team practices.
