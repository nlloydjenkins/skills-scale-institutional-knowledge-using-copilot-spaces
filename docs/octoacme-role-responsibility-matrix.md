# OctoAcme — Role Responsibility Matrix

## Purpose
Provide a lightweight RACI-style mapping of core project activities to roles, so every team member understands who is Responsible, Accountable, Consulted, and Informed for each activity.

**Legend:**
- **R** — Responsible: does the work
- **A** — Accountable: owns the outcome; makes final decisions
- **C** — Consulted: provides input before the work is complete
- **I** — Informed: kept updated on progress or decisions

> Abbreviations: PM = Project Manager, PdM = Product Manager, Dev = Developer(s), SM = Scrum Master, UX = UX Designer, TW = Technical Writer, QA = QA Lead, BA = Business Analyst

---

## Initiation & Planning

| Activity | PM | PdM | Dev | SM | UX | TW | QA | BA |
|---|---|---|---|---|---|---|---|---|
| Define problem statement & project goals | C | A | I | I | C | I | I | R |
| Create project charter / one-pager | A | C | I | I | I | C | I | R |
| Identify stakeholders and communication needs | A | C | I | I | I | I | I | C |
| Elicit and document requirements | I | A | C | I | C | I | C | R |
| Decompose requirements into user stories | C | A | C | C | C | I | C | R |
| Define acceptance criteria | C | A | C | I | C | I | R | R |
| Define Definition of Done (DoD) | C | C | R | A | C | C | R | C |
| Create and prioritize backlog | I | A | C | C | C | I | C | R |
| Estimate effort (story points / T-shirt sizing) | I | C | R | A | C | I | C | C |
| Identify dependencies and risks | A | C | R | C | C | I | C | C |
| Create release plan and milestones | A | C | C | C | I | I | C | C |
| Draft initial QA / test strategy | C | C | C | C | I | I | A | C |

---

## Execution & Tracking

| Activity | PM | PdM | Dev | SM | UX | TW | QA | BA |
|---|---|---|---|---|---|---|---|---|
| Sprint planning facilitation | C | C | R | A | C | I | C | C |
| Daily standup facilitation | I | I | R | A | I | I | I | I |
| Feature implementation | I | C | A | I | C | I | C | C |
| UX design and specifications | I | C | C | I | A | I | C | C |
| Code and design review | I | I | A | C | C | I | C | I |
| Test case creation and execution | I | C | C | C | C | I | A | C |
| Defect triage and resolution | C | C | R | C | C | I | A | C |
| Update risk register | A | C | C | C | I | I | C | C |
| Track and report project status | A | I | I | C | I | I | C | I |
| Remove team impediments | C | I | I | A | I | I | I | I |
| Update project board | I | I | R | A | I | I | C | I |
| Requirement clarification during development | I | A | C | I | C | I | C | R |

---

## Documentation & Communication

| Activity | PM | PdM | Dev | SM | UX | TW | QA | BA |
|---|---|---|---|---|---|---|---|---|
| Draft feature documentation | I | C | C | I | C | A | C | C |
| Draft release notes | C | C | C | I | I | A | C | I |
| Publish documentation at release | I | C | I | I | I | A | C | I |
| Maintain process documentation | C | I | I | C | I | A | I | C |
| Stakeholder status updates | A | C | I | I | I | I | I | C |
| Escalation communication | A | C | C | I | I | I | C | I |

---

## Release & Deployment

| Activity | PM | PdM | Dev | SM | UX | TW | QA | BA |
|---|---|---|---|---|---|---|---|---|
| Confirm all acceptance criteria met | C | A | C | I | C | I | R | C |
| QA signoff / release readiness | C | C | C | I | I | I | A | I |
| Release notes finalized | C | C | I | I | I | A | C | I |
| Rollback / mitigation plan documented | A | C | R | I | I | I | C | I |
| Deploy to staging and run smoke tests | C | I | R | I | I | I | A | I |
| Deploy to production | A | C | R | I | I | I | C | I |
| Post-deploy verification | C | C | R | I | I | I | A | I |
| Announce release to stakeholders | A | C | I | I | I | R | I | I |

---

## Retrospective & Improvement

| Activity | PM | PdM | Dev | SM | UX | TW | QA | BA |
|---|---|---|---|---|---|---|---|---|
| Facilitate retrospective | C | I | R | A | I | I | I | I |
| Capture retrospective action items | C | I | R | A | I | I | I | I |
| Update process documentation post-retro | C | I | I | C | I | A | I | C |
| Track improvement action item completion | A | I | C | R | I | I | C | I |

---

## Related Documents
- [Roles and Personas](octoacme-roles-and-personas.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Release & Deployment](octoacme-release-and-deployment.md)
- [Feature & Release Readiness Checklist](octoacme-feature-readiness-checklist.md)
