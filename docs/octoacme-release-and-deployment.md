# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans (verified by Security Lead)
- Release notes drafted (by Technical Writer or Release Manager)
- Rollback / mitigation plan documented
- Smoke tests prepared
- Release Manager go/no-go decision obtained
- Support Engineer briefed on release changes and support expectations

## Deployment Checklist
- [ ] Deployment window scheduled (if needed) by Release Manager
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests
- [ ] Security Lead confirms security gates passed
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders and support
- [ ] Support Engineer confirms support handoff received
- [ ] Technical Writer confirms documentation is updated

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call
  - Notify Security Lead if security-related incident
  - Support Engineer to communicate with affected users
  - Rollback to last known-good release if necessary
  - Triage root cause and capture action items

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
