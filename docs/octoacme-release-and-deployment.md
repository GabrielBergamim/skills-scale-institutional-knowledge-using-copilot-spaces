# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged (validated by QA Lead)
- Passing CI and security scans (verified by DevOps Engineer)
- Release notes drafted (coordinated by Project Manager)
- Rollback / mitigation plan documented (owned by DevOps Engineer)
- Smoke tests prepared (defined by QA Lead)
- Design assets and documentation complete (verified by UX Designer for user-facing features)

For detailed release responsibilities, see the [Responsibility Matrix](octoacme-role-onboarding-and-collaboration.md#responsibility-matrix-raci).

## Deployment Checklist
- [ ] Deployment window scheduled (if needed) — Project Manager
- [ ] Backup or snapshot (if applicable) — DevOps Engineer
- [ ] Deploy to staging and run smoke tests — DevOps Engineer + QA Lead
- [ ] Deploy to production (automated pipeline preferred) — DevOps Engineer
- [ ] Run post-deploy verifications — DevOps Engineer + QA Lead
- [ ] Announce release to stakeholders and support — Project Manager

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
