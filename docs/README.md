# OctoAcme Project Management Docs

Welcome to the OctoAcme project management documentation hub. These guides help team members execute projects consistently, manage risks effectively, and scale institutional knowledge.

## What is OctoAcme?

OctoAcme is a lightweight, customer-focused project management approach used across cross-functional initiatives. We prioritize iterative delivery, clear ownership, data-informed decisions, and psychological safety.

## Core Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager (PM) and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## OctoAcme Project Management Overview

OctoAcme follows a structured, lifecycle-based approach to project management that emphasizes customer value, iterative delivery, and clear ownership. The methodology spans five key phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. Each phase is guided by well-defined roles—Project Manager (PM), Product Manager (PdM), Developers, QA/Testing, and Stakeholders—who coordinate through a regular communication cadence including weekly PM-PdM syncs, twice-weekly standups, and monthly stakeholder updates. Core artifacts like Project Charters, roadmaps, sprint backlogs, and risk registers serve as single sources of truth, ensuring transparency and alignment across teams.

The planning and execution workflow emphasizes breaking work into shippable increments with clear acceptance criteria and Definition of Done. During the **Planning phase**, teams conduct kickoff meetings, build prioritized backlogs with T-shirt sizing or story points, and identify dependencies and integration points. Once planning is approved, the **Execution & Tracking phase** leverages GitHub Projects with columns (Backlog, Ready, In Progress, In Review, QA, Done) to visualize progress. Daily standups focus on blockers and dependencies, while weekly delivery syncs review progress against milestones. Small pull requests (≤400 lines) include issue links and acceptance criteria, require automated CI tests and linting, and need at least one approval before merging.

Quality and risk management are integral to OctoAcme's delivery culture. Teams implement unit and integration tests, end-to-end smoke tests for critical flows, and security scanning in CI pipelines, with manual QA for feature acceptance when needed. The **Risk Register** captures risks by ID, description, impact, likelihood, owner, and mitigation plan, reviewed weekly during syncs. A three-level escalation path (team-level triage → PM escalation to Product Lead → Sponsor-level escalation) ensures blockers are surfaced and resolved quickly. Before any release, teams verify all acceptance criteria are met, CI/security scans pass, release notes are drafted, and rollback plans are documented. Finally, the **Retrospective & Continuous Improvement phase** captures learnings after each sprint, release, or milestone, prioritizing 2–3 actionable improvements and tracking their impact to foster a culture of iterative enhancement.

## Core Processes

OctoAcme consists of six interconnected processes that form a complete project lifecycle:

1. **Project Initiation** — Validate the business need, align stakeholders, and authorize work
2. **Project Planning** — Break work into shippable increments, identify dependencies, and define success
3. **Execution & Tracking** — Manage day-to-day delivery, maintain quality, and escalate blockers
4. **Risk Management & Communication** — Identify and mitigate risks, keep stakeholders informed
5. **Release & Deployment** — Standardize releases to production with clear rollback plans
6. **Retrospectives & Continuous Improvement** — Capture learnings and drive iterative improvements

## Documentation

- [Project Management Overview](octoacme-project-management-overview.md) — High-level introduction to roles, principles, and lifecycle
- [Project Initiation Guide](octoacme-project-initiation.md) — Steps to validate and authorize new work
- [Project Planning](octoacme-project-planning.md) — How to create an actionable plan and backlog
- [Execution & Tracking](octoacme-execution-and-tracking.md) — Daily standups, PRs, quality, and blocker escalation
- [Risk Management & Communication](octoacme-risks-and-communication.md) — Managing risks, dependencies, and stakeholder updates
- [Release & Deployment Guide](octoacme-release-and-deployment.md) — Release types, deployment checklist, and rollback procedures
- [Retrospectives & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Capturing learnings and driving improvements
- [Roles & Personas](octoacme-roles-and-personas.md) — Core roles and responsibilities

## Quick Reference

**Starting a new project?**  
Begin with the [Project Initiation Guide](octoacme-project-initiation.md).

**Need to escalate a blocker?**  
See [Execution & Tracking — Blocker Escalation](octoacme-execution-and-tracking.md#blocker-escalation).

**Planning a release?**  
Refer to the [Release & Deployment Guide](octoacme-release-and-deployment.md).

**Running a retrospective?**  
Use the [Retrospectives & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) guide.

**How do I define success for my project?**  
Start with the [Project Initiation Guide — Project One-pager Template](octoacme-project-initiation.md#project-one-pager-template).

## Core Roles

- **Project Manager (PM)**: Coordinates delivery, schedules, risk, and communications
- **Product Manager (PdM)**: Defines outcomes, prioritizes backlog, and measures success
- **Developers**: Implement features, collaborate on design and testability
- **QA/Testing**: Validate quality and acceptance criteria
- **Stakeholders**: Provide inputs and approvals

For detailed role descriptions and responsibilities, see [Roles & Personas](octoacme-roles-and-personas.md).

## Contributing to Process Docs

To suggest updates or additions to OctoAcme process documentation, create an issue using the [Add Content to Project Management Process Docs](.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template.

All contributions should:
- Align with existing process docs
- Improve clarity or close a documented gap
- Be reviewed with stakeholders when needed

---

*Last updated: 2026-09-04*
