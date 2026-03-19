# OctoAcme — Feature & Release Readiness Checklist

## Purpose
Provide a shared checklist to ensure consistent quality gates before a feature is considered done and before a release is deployed to production. Use this in conjunction with the [Definition of Done](#definition-of-done-dod-template) below.

---

## Feature Readiness Checklist

Use this checklist before moving a feature from **In Review** to **QA** on the project board.

### Requirements & Design
- [ ] User story has clear, testable acceptance criteria (owned by: **Business Analyst / Product Manager**)
- [ ] UX designs and specs are finalized and shared with Developers (**UX Designer**)
- [ ] Edge cases and error states are documented in the story (**Business Analyst**)
- [ ] Any API contracts or data schema changes are documented (**Developer**)

### Implementation
- [ ] Feature implementation is complete and meets acceptance criteria (**Developer**)
- [ ] Unit and integration tests are written and passing in CI (**Developer**)
- [ ] No unresolved merge conflicts; PR is approved (**Developer / Reviewer**)
- [ ] Security and linting checks pass in CI (**Developer**)

### QA
- [ ] QA Lead has reviewed the test plan for this feature (**QA Lead**)
- [ ] Manual QA sign-off completed (if required) (**QA Lead**)
- [ ] All defects raised during QA are resolved or risk-accepted (**QA Lead / Product Manager**)
- [ ] Regression tests updated to cover new behavior (**QA Lead / Developer**)

### Documentation
- [ ] Feature documentation drafted or updated (**Technical Writer**)
- [ ] Release notes entry added (**Technical Writer**)
- [ ] Internal process docs updated if the feature changes a workflow (**Technical Writer / PM**)

### Handoff
- [ ] Stakeholders notified of feature completion (**Project Manager**)
- [ ] Feature demo scheduled or demo recording shared (**Project Manager / Scrum Master**)

---

## Definition of Done (DoD) Template

> **Customize this template** for your project and agree on it during planning. Reference: [Project Planning](octoacme-project-planning.md).

A story / feature is **Done** when:

1. **Code**: Implementation meets acceptance criteria; PR reviewed and merged.
2. **Tests**: Unit, integration, and/or E2E tests written and passing in CI.
3. **Quality**: No open critical or high defects; QA Lead sign-off obtained.
4. **Security**: Security scan passes; no new vulnerabilities introduced.
5. **Documentation**: Feature docs and release notes updated.
6. **Observability**: Required logging, metrics, or alerts added (if applicable).
7. **Accessibility**: UX accessibility requirements met (if applicable).
8. **Stakeholder acceptance**: Acceptance criteria validated with Product Manager or Business Analyst.

---

## Release Readiness Checklist

Use this checklist before deploying to production. The **QA Lead** owns overall release readiness; the **Project Manager** owns the release coordination.

### Pre-Release Verification
- [ ] All features in scope have passed the Feature Readiness Checklist (**QA Lead**)
- [ ] All acceptance criteria met and confirmed by Product Manager (**Product Manager**)
- [ ] Release branch is stable; no failing CI checks (**Developer / QA Lead**)
- [ ] Security scans and dependency checks passed (**Developer**)
- [ ] Performance and load testing completed (if applicable) (**QA Lead / Developer**)

### Documentation & Communication
- [ ] Release notes finalized and reviewed (**Technical Writer / Product Manager**)
- [ ] Migration steps documented (if applicable) (**Developer / Technical Writer**)
- [ ] Known issues documented (**QA Lead / Technical Writer**)
- [ ] Stakeholder release announcement prepared (**Project Manager / Technical Writer**)

### Deployment Readiness
- [ ] Deployment window scheduled and communicated (**Project Manager**)
- [ ] Rollback plan documented and tested (**Developer / Project Manager**)
- [ ] On-call / support team briefed on the release (**Project Manager**)
- [ ] Feature flags or toggles configured (if applicable) (**Developer**)
- [ ] Staging deployment and smoke tests completed (**Developer / QA Lead**)

### QA Signoff
- [ ] QA Lead has formally signed off on release readiness (**QA Lead**)
- [ ] Product Manager has confirmed scope and acceptance (**Product Manager**)
- [ ] Project Manager has confirmed timeline and communication readiness (**Project Manager**)

### Post-Release
- [ ] Production deployment completed (**Developer**)
- [ ] Post-deploy smoke tests passed (**Developer / QA Lead**)
- [ ] Release announced to stakeholders (**Project Manager / Technical Writer**)
- [ ] Monitoring dashboards checked for anomalies (**Developer / QA Lead**)
- [ ] Incident response on standby for defined observation period (**Developer / PM**)

---

## Role Summary for Readiness Activities

| Role | Feature Readiness | Release Readiness |
|---|---|---|
| Product Manager | Validates acceptance criteria | Confirms scope and final acceptance |
| Project Manager | Coordinates handoff and comms | Owns release coordination and comms |
| Developer | Implements, tests, and merges | Deploys and monitors |
| Scrum Master | Facilitates feature demo | Ensures sprint includes release tasks |
| UX Designer | Provides designs; reviews UX acceptance | Reviews UX post-deploy if applicable |
| Technical Writer | Drafts feature docs and release notes | Finalizes and publishes docs |
| QA Lead | Signs off feature QA | Owns overall release readiness signoff |
| Business Analyst | Validates acceptance criteria | Confirms requirements are fully delivered |

---

## Related Documents
- [Roles and Personas](octoacme-roles-and-personas.md)
- [Role Responsibility Matrix](octoacme-role-responsibility-matrix.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Release & Deployment](octoacme-release-and-deployment.md)
