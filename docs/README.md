# OctoAcme Project Management Documentation

This folder is the central reference for OctoAcme's project management processes. It is intended to help new and existing team members quickly understand how projects are run and where to find the relevant process documents.

## Overview of OctoAcme Project Management

OctoAcme follows a lightweight, repeatable delivery lifecycle designed to keep work iterative and transparent. Projects progress through five stages: **Initiation → Planning → Execution → Release → Close & Retrospective**. In Initiation, the team validates the business need, defines measurable success criteria, and produces minimum artifacts such as a Project One-pager, a stakeholder communication plan, and an initial risk list. Work moves into Planning once stakeholders have aligned on priority and team availability is confirmed, at which point scope is broken into a prioritized backlog with clear acceptance criteria and a documented Definition of Done.

OctoAcme emphasizes clear ownership across defined roles to avoid ambiguity. **Project Managers (PMs)** coordinate delivery, timelines, risk management, and communications. **Product Managers (PdMs)** define outcomes, own the roadmap and backlog, and measure success against agreed metrics. **Developers** implement features, write tests, participate in design and code reviews, and surface technical risks. **QA/Testing** validates quality and acceptance criteria, and **Stakeholders** provide inputs and approvals at key decision gates. Day-to-day work is managed on a project board (e.g., GitHub Projects) using a consistent flow — Backlog → Ready → In Progress → In Review → QA → Done — keeping status visible and work-in-progress controlled.

Communication follows a structured cadence to keep all parties aligned: twice-weekly standups for the delivery team, a weekly sync between PM and PdM, and monthly stakeholder updates. A weekly status template (Progress · Next steps · Risks & blockers · Decisions needed) provides a single source of truth for reporting. Escalation paths run from team-level triage in standups, to PM escalation with dependent teams, up to sponsor-level escalation for business-impacting issues.

Quality and release practices are built into execution. Pull requests are kept small (≤ 400 lines where possible), must include an issue link and acceptance criteria, and require at least one approval after automated tests, linting, and security scanning pass in CI. End-to-end smoke tests are run on critical flows before each release, and every project closes with a blameless retrospective to capture learnings and drive continuous improvement.

## Process Documents

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](octoacme-roles-and-personas.md)

## Contributing / Proposing Changes

To propose additions or updates to these process documents, please use the issue template located in [`.github/ISSUE_TEMPLATE/`](../.github/ISSUE_TEMPLATE/) — specifically the **"Add Content to Project Management Process Docs"** template. This helps ensure changes are reviewed and consistent with existing processes before they are merged.
