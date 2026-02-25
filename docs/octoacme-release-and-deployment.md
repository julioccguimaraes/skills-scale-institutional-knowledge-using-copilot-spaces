# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans (DevOps Engineer)
- QA Lead sign-off on release readiness
- Release notes drafted (Release Manager)
- Rollback / mitigation plan documented (Release Manager + DevOps Engineer)
- Smoke tests prepared (QA Lead)

## Deployment Checklist
- [ ] Go/no-go confirmed by Release Manager, QA Lead, and PM
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot (if applicable) — DevOps Engineer
- [ ] Deploy to staging and run smoke tests (DevOps Engineer + QA Lead)
- [ ] Deploy to production (automated pipeline preferred — DevOps Engineer)
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders and support (Release Manager)

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
