# OctoAcme — Cross-Role Collaboration, Onboarding & Handoff Guide

> **Related to [Issue #4](https://github.com/sgamage61/skills-scale-institutional-knowledge-using-copilot-spaces/issues/4)** — Adding more personas and roles to the project management processes.

## Purpose

This document provides onboarding checklists, handoff templates, and collaboration guides for all OctoAcme project roles — including the four roles added in this process improvement cycle: UX/UI Designer, DevOps Engineer, Customer Support/Success, and Security Champion. It closes the gap between role definitions and day-to-day collaboration.

For full role descriptions, see [`octoacme-roles-and-personas.md`](octoacme-roles-and-personas.md).

---

## Role Onboarding Checklists

Use these checklists when a team member joins or takes on a new role mid-project.

### All Roles — General Onboarding
- [ ] Review [`octoacme-project-management-overview.md`](octoacme-project-management-overview.md)
- [ ] Review [`octoacme-roles-and-personas.md`](octoacme-roles-and-personas.md) for your role and collaborating roles
- [ ] Get access to project board, repo, and communication channels
- [ ] Attend first standup and introduce yourself
- [ ] Review the current Risk Register and backlog
- [ ] Identify your primary contact for each role you interact with

---

### UX/UI Designer Onboarding
- [ ] Complete general onboarding steps above
- [ ] Review existing design system, component library, and style guide
- [ ] Access design tooling (e.g., Figma, Sketch) and review current designs
- [ ] Meet with Product Manager to understand current roadmap and design backlog
- [ ] Meet with lead Developer to understand implementation constraints
- [ ] Attend a sprint demo to understand current product state
- [ ] Schedule recurring design review cadence with Developers and QA

### DevOps Engineer Onboarding
- [ ] Complete general onboarding steps above
- [ ] Review CI/CD pipeline documentation and get access to pipeline tooling
- [ ] Review infrastructure architecture and get access to cloud/environment management tools
- [ ] Meet with PM to understand upcoming release schedule and deployment windows
- [ ] Meet with Security Champion to review existing security scanning setup
- [ ] Confirm access to staging and production environments
- [ ] Review incident runbook and on-call schedule

### Customer Support / Success Onboarding
- [ ] Complete general onboarding steps above
- [ ] Review product documentation and release notes for recent releases
- [ ] Set up access to support ticketing system and communication channels
- [ ] Meet with Product Manager to understand product vision and roadmap
- [ ] Attend a sprint demo to understand upcoming features
- [ ] Establish recurring sync with PM to report user feedback and escalations
- [ ] Review SLA definitions and escalation paths

### Security Champion Onboarding
- [ ] Complete general onboarding steps above
- [ ] Review existing security policies, threat models, and the security incident runbook
- [ ] Get access to security scanning tools in CI/CD (with DevOps Engineer)
- [ ] Review the current Risk Register for open security risks
- [ ] Meet with DevOps Engineer to review infrastructure security posture
- [ ] Meet with lead Developer to review secure coding standards in use
- [ ] Schedule security review cadence in the sprint cycle (e.g., at sprint planning)

---

## Handoff Templates

### Design-to-Development Handoff (UX/UI Designer → Developers)

Use this template when handing off designs for implementation.

```
Design Handoff: [Feature Name]

- Feature summary:
- Link to design files (Figma / Sketch):
- User flows covered:
- Key interactions and states (hover, focus, error, loading):
- Accessibility notes (WCAG requirements):
- Open questions for engineers:
- Design review date:
- Expected implementation sprint:
- QA / visual acceptance notes:
```

### Development-to-QA Handoff (Developers → QA / Testing)

Use this template when a feature is ready for QA.

```
Development-to-QA Handoff: [Feature Name / PR Link]

- Feature summary:
- Acceptance criteria (link to backlog item):
- Known limitations or deferred items:
- Test environment and branch/build:
- Steps to test:
- Security notes (reviewed by Security Champion?):
- UX design reference (link):
- Edge cases to verify:
- Expected handoff date:
```

### Release Handoff (DevOps Engineer → All)

Use this template when notifying the team before a production deployment.

```
Release Notification: [Release Name / Version]

- Release summary:
- Deployment window: [Date/time and timezone]
- Changes included (link to release notes):
- Staging verification status:
- Security Champion sign-off: [ ] Yes / [ ] Pending
- Rollback plan:
- Post-deploy verification steps:
- Customer Support/Success notified: [ ] Yes
- Stakeholder communication sent: [ ] Yes
- On-call contact during deployment: [Name / contact]
```

### Customer Feedback Handoff (Customer Support/Success → Product Manager)

Use this template when escalating user feedback for backlog consideration.

```
Customer Feedback Summary: [Topic / Theme]

- Date range of feedback collected:
- Volume of reports (approximate):
- Summary of user pain points:
- Sample verbatim quotes (anonymized):
- Suggested backlog items or priority adjustments:
- Any urgent / SLA-impacting issues:
- Next steps requested from Product Manager:
```

### Security Finding Handoff (Security Champion → Developers / DevOps Engineer)

Use this template when communicating a security finding.

```
Security Finding: [Finding Title / CVE / ID]

- Severity: [Critical / High / Medium / Low]
- Component / area affected:
- Description of vulnerability:
- Evidence or reproduction steps:
- Recommended remediation:
- Proposed owner:
- Target remediation date:
- Risk Register entry created: [ ] Yes / No
- Escalation required: [ ] PM / [ ] Sponsor / [ ] Security on-call
```

---

## Cross-Role Collaboration Quick Reference

| Collaboration Touchpoint | Roles Involved | When |
|---|---|---|
| Design review | UX/UI Designer, Developers, QA, PM | Before development starts on a new feature |
| Sprint planning (security input) | Security Champion, Developers, PM | Each sprint; Security Champion flags security items |
| Sprint planning (UX input) | UX/UI Designer, PM, Developers | Each sprint; UX/UI Designer confirms design readiness |
| Daily standup | Developers, QA, UX/UI Designer, DevOps Engineer | Daily during active sprints |
| Weekly delivery sync | PM, Developers, QA, DevOps Engineer | Weekly; DevOps raises env/release topics |
| Risk review | PM, Security Champion, DevOps Engineer | Weekly or bi-weekly |
| Sprint demo | All roles (Customer Support/Success invited) | End of each sprint |
| Release sign-off | PM, DevOps Engineer, QA, Security Champion | Before every production deployment |
| Customer feedback review | Customer Support/Success, PM, PdM | Monthly or after major releases |
| Retrospective | All roles involved in the sprint or release | End of sprint or after incidents |

---

## Onboarding Resource Index

| Resource | Purpose |
|---|---|
| [`octoacme-roles-and-personas.md`](octoacme-roles-and-personas.md) | Role definitions, responsibilities, and interaction guides |
| [`octoacme-project-management-overview.md`](octoacme-project-management-overview.md) | High-level overview of the OctoAcme delivery process |
| [`octoacme-project-initiation.md`](octoacme-project-initiation.md) | How to start a new project |
| [`octoacme-project-planning.md`](octoacme-project-planning.md) | Sprint and release planning guidance |
| [`octoacme-execution-and-tracking.md`](octoacme-execution-and-tracking.md) | Day-to-day execution and quality standards |
| [`octoacme-risks-and-communication.md`](octoacme-risks-and-communication.md) | Risk management and escalation paths |
| [`octoacme-release-and-deployment.md`](octoacme-release-and-deployment.md) | Deployment checklists and incident playbook |
| [`octoacme-retrospective-and-continuous-improvement.md`](octoacme-retrospective-and-continuous-improvement.md) | Retrospective format and continuous improvement |
