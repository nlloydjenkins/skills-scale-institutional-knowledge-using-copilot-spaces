# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans
- Release notes drafted
- Rollback / mitigation plan documented
- Smoke tests prepared

## Deployment Checklist
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders and support

> **Use the full [Release Readiness Checklist](octoacme-feature-readiness-checklist.md#release-readiness-checklist)** to confirm QA signoff, documentation, rollback plan, and stakeholder communications are complete before deploying.

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call
  - Rollback to last known-good release if necessary
  - Triage root cause and capture action items

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:

## Related Documents
- [Roles and Personas](octoacme-roles-and-personas.md)
- [Role Responsibility Matrix](octoacme-role-responsibility-matrix.md)
- [Feature & Release Readiness Checklist](octoacme-feature-readiness-checklist.md)
