# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies; include Developers, QA, UX/UI Designer, and DevOps Engineer as appropriate
- Weekly delivery sync — show progress, updates, and flagged risks; include DevOps Engineer for release/environment topics
- Design reviews — UX/UI Designer shares designs before implementation begins; Developers and QA review for feasibility and testability
- Security reviews — Security Champion attends or reviews new features for security implications (see risk escalation below)
- Demo/Review at the end of each sprint or milestone — all roles invited; Customer Support/Success attends to preview upcoming changes

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)

## Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release (coordinated with DevOps Engineer for staging environments)
- Security scanning in CI (Security Champion reviews scan results and triages findings)
- UX acceptance: UX/UI Designer reviews implemented features against design specs before QA sign-off
- Manual QA for feature acceptance when needed

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- Level 1: Team-level triage in daily standup
- Level 2: PM escalates to Product Lead and dependent teams
- Level 3: Sponsor-level escalation for business-impacting issues
- Security escalation: Any security vulnerability or incident is escalated immediately to the Security Champion, who follows the security incident runbook (see [`octoacme-risks-and-communication.md`](octoacme-risks-and-communication.md))
- Customer escalation: Customer Support/Success raises critical user-impacting issues to PM/PdM outside the normal cadence when SLAs are at risk

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests, lint, and security scanning
- [ ] UX/UI design reviews scheduled and completed before implementation of new features
- [ ] DevOps Engineer engaged for environment setup, deployment automation, and staging readiness
- [ ] Security Champion included in review of security-sensitive changes
- [ ] Regular demos scheduled (Customer Support/Success invited to sprint demos)
- [ ] Risk register updated weekly
