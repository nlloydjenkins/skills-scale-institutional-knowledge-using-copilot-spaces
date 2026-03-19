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

## UX Designer

### Role Summary
Responsible for understanding user needs and designing solutions that ensure usability and accessibility. Bridges the gap between product vision and the end-user experience.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, prototypes, and design specs
- Advocate for user-centered design principles
- Provide iterative design feedback throughout development
- Collaborate on accessibility requirements

### Goals
- Ensure delivered features are usable, accessible, and meet user needs
- Reduce rework caused by usability issues discovered late
- Maintain a consistent and intuitive product experience

### Typical Communication
- Design reviews and usability test readouts
- Annotated wireframes and prototype links shared in project board
- Feedback on acceptance criteria and feature specs

### Interactions with Existing Roles
- **Product Managers**: Collaborates to clarify user problems and validate that designs meet success metrics
- **Developers**: Partners on feasibility, design handoff, and implementation fidelity
- **Project Managers**: Keeps PM informed of design progress, risks (e.g., unresolved UX decisions blocking dev), and timeline impacts
- **Scrum Master / Agile Coach**: Participates in sprint planning and retrospectives; flags UX-related impediments

### Interactions with Process Docs
- **[Project Planning](octoacme-project-planning.md)**: Contributes design estimates and ensures UX tasks are represented in the backlog
- **[Execution & Tracking](octoacme-execution-and-tracking.md)**: Reviews PRs for design fidelity; participates in demos and sprint reviews
- **[Kickoff Meeting Checklist](octoacme-kickoff-meeting-checklist.md)**: Attends kickoff to align on user goals and design scope

---

## Scrum Master / Agile Coach

### Role Summary
Facilitates Agile ceremonies and continuous improvement. Removes obstacles to team progress and champions process discipline to keep delivery on track.

### Responsibilities
- Lead sprint planning, daily standups, reviews, and retrospectives
- Coach the team on Agile best practices and continuous improvement
- Identify and remove blockers and impediments
- Gather metrics (velocity, cycle time) and drive process experiments
- Shield the team from unplanned interruptions

### Goals
- Maintain a sustainable, predictable delivery cadence
- Continuously improve team processes and collaboration
- Reduce waste and increase flow efficiency

### Typical Communication
- Facilitates all sprint ceremonies and keeps them time-boxed
- Publishes retrospective action items and tracks follow-through
- Shares team health metrics with stakeholders and leadership

### Interactions with Existing Roles
- **Developers**: Removes technical and organizational blockers; coaches on Agile engineering practices
- **Product Managers**: Partners to ensure the backlog is groomed and sprint goals are clear
- **Project Managers**: Aligns on milestones, dependencies, and escalation paths; shares velocity data for forecasting
- **UX Designer**: Ensures design work is reflected in sprint capacity and backlog

### Interactions with Process Docs
- **[Project Planning](octoacme-project-planning.md)**: Owns or co-facilitates sprint planning and ensures Definition of Done is applied
- **[Execution & Tracking](octoacme-execution-and-tracking.md)**: Drives team rhythm (standups, demos, syncs) and escalation protocols
- **[Kickoff Meeting Checklist](octoacme-kickoff-meeting-checklist.md)**: Facilitates the project kickoff meeting and ensures all items are addressed
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)**: Owns the retrospective process and tracks improvement actions

---

## Business Analyst

### Role Summary
Bridges the gap between business goals and technical solutions. Captures requirements, analyzes processes, and supports validation to ensure the right problems are solved.

### Responsibilities
- Elicit and document requirements from stakeholders
- Analyze existing workflows and identify areas for improvement
- Write user stories and clear acceptance criteria
- Support User Acceptance Testing (UAT)
- Maintain requirement traceability throughout the project lifecycle

### Goals
- Ensure solutions address validated business needs
- Reduce requirement ambiguity and costly late-stage rework
- Enable smooth handoffs between business stakeholders and the delivery team

### Typical Communication
- Requirements workshops and stakeholder interviews
- User story reviews and backlog grooming sessions
- UAT reports and sign-off documentation

### Interactions with Existing Roles
- **Product Managers**: Works closely to translate business goals into prioritized, actionable requirements
- **Developers**: Clarifies acceptance criteria and answers questions during implementation
- **Project Managers**: Flags requirement gaps or scope changes that affect timelines and risk
- **UX Designer**: Collaborates to ensure requirements address both functional needs and user experience

### Interactions with Process Docs
- **[Project Initiation](octoacme-project-initiation.md)**: Contributes to the Project One-pager by eliciting and validating problem statements and success metrics
- **[Project Planning](octoacme-project-planning.md)**: Drafts and refines backlog items with clear acceptance criteria; ensures DoD is well-defined
- **[Risks & Communication](octoacme-risks-and-communication.md)**: Flags requirement-related risks (e.g., unclear scope, stakeholder misalignment)
- **[Kickoff Meeting Checklist](octoacme-kickoff-meeting-checklist.md)**: Participates in kickoff to confirm requirements scope and stakeholder alignment

---

## Technical Writer

### Role Summary
Ensures clear, accurate, and up-to-date project documentation, release notes, and end-user guides. Helps maintain shared understanding across the team and with external stakeholders.

### Responsibilities
- Write and maintain internal docs, user guides, and release notes
- Edit and improve clarity of technical content produced by other roles
- Standardize documentation templates and practices across the project
- Coordinate documentation reviews and approvals

### Goals
- Reduce knowledge silos by centralizing and versioning key documentation
- Ensure documentation keeps pace with product changes
- Improve onboarding speed for new team members and stakeholders

### Typical Communication
- Documentation review requests via PRs or shared drafts
- Release note previews shared with PM before release
- Regular check-ins with Developers and PM to capture in-progress changes

### Interactions with Existing Roles
- **Developers**: Extracts technical knowledge to produce accurate docs; reviews developer-written documentation
- **Product Managers**: Aligns release notes and user-facing content with product messaging
- **Project Managers**: Ensures process docs are kept current; contributes to status reports and stakeholder communications
- **Business Analyst**: Incorporates finalized requirements and acceptance criteria into documentation

### Interactions with Process Docs
- **[Project Planning](octoacme-project-planning.md)**: Ensures documentation tasks are included in the backlog and estimated
- **[Execution & Tracking](octoacme-execution-and-tracking.md)**: Maintains documentation as a "done" criterion; reviews PRs for documentation completeness
- **[Release & Deployment](octoacme-release-and-deployment.md)**: Drafts and publishes release notes; coordinates documentation sign-off as part of pre-release requirements
- **[Kickoff Meeting Checklist](octoacme-kickoff-meeting-checklist.md)**: Participates in kickoff to understand documentation scope and audiences

---

## Engineering Manager

### Role Summary
Leads the engineering team by managing people, aligning technical direction, and ensuring the team has the capacity and environment to deliver effectively.

### Responsibilities
- Recruit, onboard, and develop engineering team members
- Set technical direction and facilitate architectural decisions
- Partner with Project and Product Managers on capacity planning and trade-offs
- Ensure engineering health (code quality, technical debt, on-call burden)
- Remove organizational blockers and escalate when needed

### Goals
- Build a high-performing, sustainable engineering team
- Align technical investments with product and business priorities
- Reduce technical risk and unplanned incidents

### Typical Communication
- 1:1s with engineers and cross-functional leadership
- Engineering updates in stakeholder syncs
- Capacity and risk inputs for project planning

### Interactions with Existing Roles
- **Developers**: Provides career guidance, removes blockers, and sets technical standards
- **Product Managers**: Negotiates scope, capacity, and technical feasibility trade-offs
- **Project Managers**: Collaborates on resourcing, timelines, and escalation paths
- **Scrum Master / Agile Coach**: Partners to improve team processes and resolve structural impediments

### Interactions with Process Docs
- **[Project Initiation](octoacme-project-initiation.md)**: Confirms team availability and technical feasibility during the initiation phase
- **[Project Planning](octoacme-project-planning.md)**: Contributes to capacity planning and architectural risk identification
- **[Risks & Communication](octoacme-risks-and-communication.md)**: Owns technical risk items in the risk register; escalates engineering-related issues

---

## SRE / DevOps Engineer

### Role Summary
Ensures reliable, scalable, and secure delivery pipelines and production systems. Partners with development teams to embed reliability and operational best practices throughout the delivery lifecycle.

### Responsibilities
- Design, maintain, and improve CI/CD pipelines
- Define and monitor Service Level Objectives (SLOs) and reliability metrics
- Lead incident response and post-incident reviews
- Automate infrastructure provisioning and configuration
- Champion security scanning, secrets management, and compliance in delivery workflows

### Goals
- Maximize system reliability and minimize mean time to recovery (MTTR)
- Enable fast, safe, and repeatable deployments
- Reduce toil through automation

### Typical Communication
- Incident reports and post-mortems
- Deployment runbooks and rollback plans
- SLO/SLI dashboards shared with stakeholders

### Interactions with Existing Roles
- **Developers**: Partners on CI/CD integration, observability, and production readiness
- **Project Managers**: Coordinates deployment windows and communicates infrastructure risks
- **Engineering Manager**: Aligns on on-call burden, reliability investment, and incident patterns
- **Technical Writer**: Collaborates on runbooks, deployment guides, and incident playbooks

### Interactions with Process Docs
- **[Execution & Tracking](octoacme-execution-and-tracking.md)**: Maintains CI pipeline health, security scanning gates, and deployment readiness criteria
- **[Risks & Communication](octoacme-risks-and-communication.md)**: Owns infrastructure and reliability risk items; leads incident communication
- **[Release & Deployment](octoacme-release-and-deployment.md)**: Owns the deployment process, rollback plan, and post-deploy verification; co-owns the deployment checklist
- **[Kickoff Meeting Checklist](octoacme-kickoff-meeting-checklist.md)**: Participates in kickoff to identify infrastructure, environment, and operational requirements

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

