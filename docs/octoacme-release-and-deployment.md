# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged (including UX sign-off where applicable)
- Passing CI and security scans (Security Champion reviews any outstanding findings)
- Release notes drafted (Customer Support/Success receives a copy ahead of deployment)
- DevOps Engineer has confirmed deployment automation and rollback plan
- Rollback / mitigation plan documented
- Smoke tests prepared (coordinated with DevOps Engineer and QA)

## Deployment Checklist
- [ ] Deployment window scheduled (coordinated by DevOps Engineer with PM)
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests (DevOps Engineer + QA)
- [ ] Security Champion confirms no critical open vulnerabilities before production deploy
- [ ] Deploy to production (automated pipeline preferred, executed by DevOps Engineer)
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders and support (Customer Support/Success notified to prepare for user questions)

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
