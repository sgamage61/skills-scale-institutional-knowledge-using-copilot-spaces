# OctoAcme Personas

> **Related to [Issue #4](https://github.com/sgamage61/skills-scale-institutional-knowledge-using-copilot-spaces/issues/4)** — Adding more personas and roles to the project management processes.

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

## UX/UI Designer

### Role Summary
UX/UI Designers create user-centered designs — including flows, wireframes, and visual assets — that ensure product features are usable, accessible, and consistent. They act as the voice of the user within the delivery team.

### Responsibilities
- Design user flows, wireframes, prototypes, and high-fidelity visual assets
- Ensure usability standards and accessibility guidelines (e.g., WCAG) are met
- Conduct user research, usability testing, and synthesize findings for the team
- Collaborate on design reviews and iterate based on feedback from engineers and QA
- Maintain and evolve the design system and component library

### Goals
- Deliver intuitive, accessible, and delightful user experiences
- Reduce rework by aligning design and engineering early in each sprint
- Ensure product decisions are grounded in user research and data

### Typical Communication
- Design reviews shared with Product Manager, Developers, and QA before implementation
- Participates in sprint planning and daily standups to flag design dependencies
- Collaborates with QA/Testing during feature acceptance to verify visual and UX standards
- Presents usability findings in sprint demos and retrospectives

### Key Interactions
| Role | Interaction |
|---|---|
| Product Manager | Translates requirements into user flows and design specs |
| Developers | Provides design assets and answers implementation questions |
| QA / Testing | Reviews feature acceptance for UX and visual correctness |
| Project Manager | Flags design-related risks or timeline dependencies |

---

## DevOps Engineer

### Role Summary
DevOps Engineers manage CI/CD pipelines, infrastructure automation, and deployment operations. They bridge the gap between development and operations, ensuring reliable, repeatable releases and healthy production systems.

### Responsibilities
- Design, build, and maintain CI/CD pipelines and deployment automation
- Manage cloud infrastructure, environments (dev, staging, production), and secrets
- Implement observability tooling: logging, metrics, and alerting
- Support incident response, perform root-cause analysis, and drive post-incident improvements
- Coordinate release logistics including deployment windows and rollback procedures

### Goals
- Enable fast, low-risk, and repeatable deployments
- Maximize system reliability, uptime, and observability
- Reduce manual toil through automation

### Typical Communication
- Coordinates with Project Manager during release planning for deployment windows
- Participates in release standup or release sync with Developers and QA
- Responds to escalations for environment or infrastructure issues during execution
- Contributes incident updates and post-incident action items to the risk register

### Key Interactions
| Role | Interaction |
|---|---|
| Developers | Supports integration, environment setup, and deployment troubleshooting |
| QA / Testing | Provides staging environments for testing; coordinates smoke-test execution |
| Project Manager | Aligns on release schedules and deployment windows |
| Security Champion | Collaborates on security scanning in CI/CD, patch management, and infrastructure hardening |

---

## Customer Support / Success

### Role Summary
Customer Support/Success professionals serve as the frontline interface between users and the product team. They gather user feedback, manage escalations, and channel real-world insights to drive prioritization and continuous improvement.

### Responsibilities
- Handle user escalations, bug reports, and post-release issues in a timely manner
- Synthesize recurring themes and pain points from customer interactions
- Communicate user needs and blockers to Product and Project Managers
- Participate in release reviews to assess customer impact of upcoming changes
- Produce post-release feedback summaries for retros and backlog grooming

### Goals
- Maximize customer satisfaction and time-to-resolution for issues
- Ensure the product team stays informed of real-world user pain points
- Reduce support ticket volume through proactive product improvements

### Typical Communication
- Attends sprint demos and release reviews to preview upcoming changes
- Reports critical user-impacting issues to PM and PdM during weekly syncs or ad hoc escalation
- Contributes feedback items to retrospectives representing the customer perspective
- Coordinates with Developers and QA on reproduction steps for bugs

### Key Interactions
| Role | Interaction |
|---|---|
| Product Manager | Channels user pain points and feature requests into backlog prioritization |
| Project Manager | Escalates production issues that affect release timelines or customer SLAs |
| QA / Testing | Shares reproduction steps and customer-reported defect details |
| Developers | Collaborates on bug triage and workarounds for active customer issues |

---

## Security Champion

### Role Summary
Security Champions promote security best practices across the delivery team. They provide security guidance in design and development, participate in risk reviews, and lead the response to security incidents.

### Responsibilities
- Review designs, architectures, and code changes for security risks and compliance gaps
- Ensure security requirements are captured as acceptance criteria in the backlog
- Lead or coordinate threat modeling sessions for new features or integrations
- Champion security scanning in CI/CD and monitor vulnerability reports
- Lead incident response for security events and facilitate post-incident blameless retrospectives
- Train and advise teammates on secure coding, secrets management, and dependency hygiene

### Goals
- Embed security-by-design into every phase of the project lifecycle
- Reduce vulnerability exposure and accelerate detection-to-remediation time
- Foster a security-aware culture across the team

### Typical Communication
- Participates in sprint planning to review security implications of upcoming work
- Attends design reviews to identify and document threat vectors
- Raises security risks in the Risk Register and escalates critical issues to PM and PdM
- Contributes security retrospective action items after incidents or findings

### Key Interactions
| Role | Interaction |
|---|---|
| Developers | Provides secure coding guidance, reviews PRs for security issues |
| DevOps Engineer | Collaborates on CI security scans, infrastructure hardening, and secrets management |
| Product Manager | Ensures security requirements are prioritized alongside feature work |
| Project Manager | Supports risk management discussions and escalates security-related blockers |
| QA / Testing | Coordinates security and penetration test planning |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- See [`octoacme-cross-role-collaboration.md`](octoacme-cross-role-collaboration.md) for handoff templates and onboarding checklists covering all roles.

