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

---

## Scrum Master

### Role Summary
The Scrum Master facilitates agile ceremonies, removes team impediments, and coaches the team on agile values and practices. They protect the team's focus and help continuously improve delivery processes.

### Responsibilities
- Facilitate daily standups, sprint planning, sprint reviews, and retrospectives
- Coach the team in agile values, principles, and practices
- Identify and remove blockers and impediments that slow delivery
- Shield the team from external interruptions and scope changes mid-sprint
- Track sprint metrics (velocity, burndown) and surface trends to the team
- Partner with the Project Manager to align sprint goals with project milestones

### Goals
- Maintain a predictable, sustainable delivery cadence
- Foster a culture of continuous improvement and psychological safety
- Reduce impediment resolution time and unplanned disruptions

### Typical Communication
- Facilitation of all agile ceremonies
- Impediment log updates shared with PM and team
- Sprint metrics and retrospective action items

### Interactions
- **Developers**: Daily support in removing blockers; coaches on agile practices during ceremonies.
- **Product Managers**: Aligns sprint goals with roadmap priorities; surfaces backlog readiness gaps.
- **Project Managers**: Coordinates on milestone alignment, risk escalation, and release timing.
- **QA Lead**: Ensures QA activities are included in sprint capacity and Definition of Done.
- **Business Analyst**: Coordinates on backlog refinement to ensure stories are ready before sprint planning.
- **Lifecycle engagement**: Most active during Planning, Execution, and Retrospective phases.

---

## UX Designer

### Role Summary
The UX Designer owns the design of user experiences, ensuring features are usable, accessible, and aligned with customer needs. They bridge user research insights and engineering implementation.

### Responsibilities
- Conduct user research and synthesize findings into design decisions
- Translate product requirements into UX flows, wireframes, and prototypes
- Produce design specifications and assets for Developers
- Participate in design and usability reviews
- Ensure accessibility standards are met across features
- Collaborate on acceptance criteria to include UX quality signals

### Goals
- Deliver intuitive, accessible, and delightful user experiences
- Reduce rework caused by UX misalignment during implementation
- Maintain design consistency across the product

### Typical Communication
- Design briefs and wireframes shared with Developers and Product Managers
- Usability review findings documented and shared post-testing
- Design feedback during PR and demo reviews

### Interactions
- **Developers**: Provides design specs and assets; participates in implementation reviews.
- **Product Managers**: Aligns on user needs, prioritizes UX work with roadmap decisions.
- **Project Managers**: Communicates design timelines and flags UX-related risks.
- **QA Lead**: Collaborates on visual and interaction acceptance criteria for testing.
- **Business Analyst**: Reviews requirements to ensure user needs are represented.
- **Lifecycle engagement**: Involved from Initiation through Execution; validates designs during QA and demos.

---

## Technical Writer

### Role Summary
The Technical Writer creates clear, accurate documentation for end users and internal audiences. They ensure product features, APIs, and processes are well-documented and maintainable.

### Responsibilities
- Document product features, APIs, user flows, and release notes
- Maintain and improve process documentation (e.g., project management docs)
- Collaborate with Developers and Product Managers to gather documentation inputs
- Review documentation as part of the Definition of Done
- Publish documentation in sync with releases

### Goals
- Ensure every release includes complete, accurate documentation
- Reduce support burden through clear self-service documentation
- Keep internal process docs current and actionable

### Typical Communication
- Documentation drafts and reviews shared with Developers and Product Managers
- Release notes published alongside each release
- Process doc updates communicated to the full team

### Interactions
- **Developers**: Gathers technical details for feature and API documentation.
- **Product Managers**: Aligns documentation scope with release scope and user needs.
- **Project Managers**: Incorporates documentation milestones into project timeline.
- **QA Lead**: Reviews documentation accuracy against implemented behavior.
- **Scrum Master**: Ensures documentation tasks are included in sprint planning.
- **Lifecycle engagement**: Active during Execution (drafting), Release (publishing), and Retrospective (process doc updates).

---

## QA Lead

### Role Summary
The QA Lead oversees testing strategy and activities to ensure product quality standards are met before release. They are the primary owner of release readiness from a quality perspective.

### Responsibilities
- Define and implement the QA strategy (manual and automated testing)
- Coordinate test planning, test case creation, and test execution
- Track, triage, and report defects; ensure critical defects block release
- Own the release readiness signoff from a QA perspective
- Collaborate with Developers on testability and CI quality gates
- Contribute to and enforce the Definition of Done

### Goals
- Prevent regressions and critical defects from reaching production
- Shift quality left by engaging early in the feature lifecycle
- Maintain a reliable, fast test suite that supports continuous delivery

### Typical Communication
- QA status reports shared at weekly delivery syncs
- Defect reports and triage notes in the project board
- Release readiness signoff documented before each release

### Interactions
- **Developers**: Partners on testability, code review, and defect resolution.
- **Product Managers**: Aligns on acceptance criteria and quality expectations.
- **Project Managers**: Communicates QA timelines, risks, and release readiness status.
- **Scrum Master**: Ensures QA tasks are included in sprint capacity and impediments are resolved.
- **UX Designer**: Reviews UI/UX against design specs as part of acceptance testing.
- **Lifecycle engagement**: Engaged from Planning (test strategy) through Release (signoff); critical gatekeeper before production deployment.

---

## Business Analyst

### Role Summary
The Business Analyst gathers and analyzes business requirements, identifies process improvements, and ensures that delivered solutions meet stakeholder needs. They bridge business intent and technical delivery.

### Responsibilities
- Elicit, document, and validate requirements from stakeholders and subject-matter experts
- Decompose business needs into clear user stories with acceptance criteria
- Identify process gaps and propose improvements
- Facilitate requirement workshops and grooming sessions
- Support QA Lead in defining acceptance test scenarios
- Maintain a traceability matrix linking requirements to delivered features

### Goals
- Ensure the team builds the right thing by clarifying requirements early
- Reduce ambiguity and mid-sprint scope changes
- Increase stakeholder confidence through clear requirement documentation

### Typical Communication
- Requirement documents and user stories shared in the backlog
- Requirement clarifications and decisions logged in the project wiki or board
- Stakeholder updates on requirement status and changes

### Interactions
- **Developers**: Clarifies requirements during refinement and development; answers questions during implementation.
- **Product Managers**: Translates business goals into structured requirements; aligns on prioritization.
- **Project Managers**: Communicates requirement risks and changes that affect timeline or scope.
- **QA Lead**: Provides acceptance criteria and supports test scenario definition.
- **Scrum Master**: Coordinates on backlog readiness to ensure stories meet Definition of Ready before sprint planning.
- **Lifecycle engagement**: Most active during Initiation (requirement gathering) and Planning (backlog refinement); continues into Execution to resolve ambiguities.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- See [Role Responsibility Matrix](octoacme-role-responsibility-matrix.md) for a RACI-style mapping of activities to roles.

