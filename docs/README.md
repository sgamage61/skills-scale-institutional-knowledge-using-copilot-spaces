# OctoAcme Project Management — Knowledge Hub

> **Closes #2** | [Issue link](https://github.com/sgamage61/skills-scale-institutional-knowledge-using-copilot-spaces/issues/2)

Welcome to the OctoAcme project management knowledge hub. This Copilot Space is the single source of truth for how OctoAcme teams plan, execute, and continuously improve projects. It is designed to help **new team members get up to speed quickly** and to give **contributors a clear path to propose or evolve our practices**.

---

## What Is This Space?

This repository serves two purposes:

1. **Onboarding hub** — concise, actionable documentation that new engineers, product managers, and project managers can read on day one to understand how work gets done at OctoAcme.
2. **Living process library** — a versioned set of process documents that teams can reference during every phase of delivery and improve over time through pull requests and issue templates.

---

## Project Management Lifecycle

OctoAcme follows a six-phase lifecycle. Each phase has a dedicated process document (linked below) with checklists, templates, and decision gates.

### 1. Initiation — [`octoacme-project-initiation.md`](octoacme-project-initiation.md)

| Goal | Key Artifact |
|---|---|
| Validate the business need and align stakeholders | Project One-pager (problem, goal, success metrics) |
| Confirm go/no-go for planning | Initiation Checklist |

**What happens here:** A concise One-pager is written and reviewed, stakeholders are identified, an initial risk list is captured, and the team decides whether to proceed to planning.

---

### 2. Planning — [`octoacme-project-planning.md`](octoacme-project-planning.md)

| Goal | Key Artifact |
|---|---|
| Turn the approved initiative into an actionable backlog | Prioritized Backlog with Acceptance Criteria |
| Align timelines, releases, and responsibilities | Release Plan & Milestone Map |

**What happens here:** A kickoff meeting aligns the team, work is broken into shippable increments, the Definition of Done (DoD) is documented, dependencies and risks are captured in the Risk Register, and a sprint/iteration cadence is agreed on.

---

### 3. Execution & Tracking — [`octoacme-execution-and-tracking.md`](octoacme-execution-and-tracking.md)

| Goal | Key Artifact |
|---|---|
| Build and ship value iteratively | Project Board (Backlog → Ready → In Progress → Review → QA → Done) |
| Surface and resolve blockers quickly | Status updates & escalation log |

**What happens here:** Daily standups, weekly syncs, and regular demos keep the team aligned. Pull requests are kept small and testable, peer reviews enforce quality, and blockers are escalated promptly.

---

### 4. Risk & Communication — [`octoacme-risks-and-communication.md`](octoacme-risks-and-communication.md)

| Goal | Key Artifact |
|---|---|
| Identify and mitigate risks before they become issues | Risk Register (ID, Description, Impact, Probability, Owner, Mitigation) |
| Keep stakeholders informed and aligned | Communication Plan & Escalation Path |

**What happens here:** Risks are reviewed weekly, owners are assigned mitigations, and a clear escalation path ensures that critical blockers reach the right stakeholders without delay.

---

### 5. Release & Deployment — [`octoacme-release-and-deployment.md`](octoacme-release-and-deployment.md)

| Goal | Key Artifact |
|---|---|
| Deploy reliably with minimal risk | Pre-release Checklist (CI passing, release notes, rollback plan) |
| Validate and announce the release | Incident playbook |

**What happens here:** All acceptance criteria must be met before release. Changes are deployed to staging first, then production. An incident playbook is ready in case issues arise post-deployment.

---

### 6. Retrospective & Continuous Improvement — [`octoacme-retrospective-and-continuous-improvement.md`](octoacme-retrospective-and-continuous-improvement.md)

| Goal | Key Artifact |
|---|---|
| Reflect on what worked and what to improve | Retrospective notes |
| Drive systematic improvements into future work | Prioritized Action Items |

**What happens here:** After every sprint or release, the team reviews what went well, what didn't, and agrees on concrete action items that feed back into the next cycle.

---

## Core Roles — [`octoacme-roles-and-personas.md`](octoacme-roles-and-personas.md)

| Role | Primary Responsibility |
|---|---|
| **Project Manager (PM)** | Coordinates delivery, schedules, risk management, and stakeholder communication |
| **Product Manager (PdM)** | Owns product vision, defines outcomes, prioritizes the backlog, measures success |
| **Developers** | Design, implement, test, and deliver software increments |
| **QA / Testing** | Validate features against acceptance criteria and quality standards |
| **Stakeholders** | Provide requirements, review key milestones, and approve releases |

---

## Key Artifacts at a Glance

| Artifact | Purpose | Phase |
|---|---|---|
| Project One-pager / Charter | Capture project intent and success metrics | Initiation |
| Backlog & Definition of Done | All approved and estimated work | Planning |
| Risk Register | Track, own, and mitigate risks | Planning → Execution |
| Release Plan & Release Notes | Standardize and communicate launches | Release |
| Retrospective Action Items | Drive continuous improvement | Retrospective |

---

## Communication Rhythms

| Cadence | Participants | Purpose |
|---|---|---|
| Daily standup | Delivery team | Progress, blockers, and coordination |
| Weekly PM + PdM sync | PM, PdM | Roadmap alignment and risk review |
| Weekly delivery sync | PM, engineers, QA | Sprint progress, dependencies, escalations |
| Monthly stakeholder update | PM, PdM, stakeholders | Status, milestones, upcoming decisions |
| Sprint demo / milestone review | All | Showcase increments and gather feedback |

---

## Process Documents

All process documents live in this `docs/` folder:

| Document | Contents |
|---|---|
| [`octoacme-project-management-overview.md`](octoacme-project-management-overview.md) | Principles, core roles, key artifacts, and communication cadence |
| [`octoacme-project-initiation.md`](octoacme-project-initiation.md) | Initiation goals, One-pager template, and decision gate |
| [`octoacme-project-planning.md`](octoacme-project-planning.md) | Kickoff, backlog templates, release planning, and planning checklist |
| [`octoacme-execution-and-tracking.md`](octoacme-execution-and-tracking.md) | Board workflow, standup routine, and status-tracking guidance |
| [`octoacme-risks-and-communication.md`](octoacme-risks-and-communication.md) | Risk Register format, escalation paths, and communication templates |
| [`octoacme-release-and-deployment.md`](octoacme-release-and-deployment.md) | Pre-release checklist, deployment steps, and incident playbook |
| [`octoacme-retrospective-and-continuous-improvement.md`](octoacme-retrospective-and-continuous-improvement.md) | Retrospective format and action-item tracking |
| [`octoacme-roles-and-personas.md`](octoacme-roles-and-personas.md) | Detailed role definitions and persona descriptions |

---

## How to Propose Improvements

OctoAcme welcomes contributions to these process documents. To suggest additions or changes:

1. **Open an issue** using the [Add Content to Project Management Process Docs](.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template found in `.github/ISSUE_TEMPLATE/`. The template guides you through:
   - Selecting the document you want to update (or proposing a new one).
   - Writing a summary of the new content.
   - Explaining why the update is needed.
   - Optionally pasting suggested content.
2. **Submit a pull request** that references your issue and updates the relevant document(s) in `docs/`.
3. **Request review** from a process owner or team lead.

> Following this lightweight workflow ensures all improvements are traceable, reviewed, and shared across the organization.

---

## Contributing

This repository uses a standard GitHub flow:

- Fork or branch from `main`.
- Make your changes in the appropriate `docs/` file.
- Open a PR referencing the related issue.
- Address review feedback and merge once approved.

For questions or onboarding help, reach out via the project's discussion board or open a new issue.
