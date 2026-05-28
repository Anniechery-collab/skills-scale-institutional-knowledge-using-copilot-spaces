# OctoAcme Project Management Docs

Welcome! This README introduces how OctoAcme runs projects and provides direct links to all key process documents.

## Project Management Process Summary

OctoAcme follows a five-phase, iterative project lifecycle that emphasizes customer-first delivery, clear ownership, and continuous improvement. Here's how we work:

### Lifecycle & Core Workflows
Our projects move through five key phases: **Initiation → Planning → Execution → Release → Close & Retrospective**. During initiation, we validate business need and align stakeholders around a lightweight Project One-pager that captures the problem statement, success metrics, and key milestones. Once approved, planning breaks work into shippable increments with prioritized backlogs and clear acceptance criteria. In execution, we emphasize iterative delivery through daily standups and sprint planning, tracking work on a project board (Backlog → Ready → In Progress → In Review → QA → Done). Small pull requests (≤400 lines) require at least one approval and passing CI checks before merging. We maintain a risk register to identify dependencies and escalate blockers through a three-level structure: team triage → PM escalation → sponsor involvement.

### Key Roles & Communication
OctoAcme operates with clear role separation: **Project Managers** coordinate schedules, risks, and communications; **Product Managers** define outcomes and prioritize the backlog; **Developers** implement features with quality and testability in mind; and **QA/Testing** validates acceptance criteria. We maintain regular communication cadences including daily standups (15 min), weekly PM/PdM syncs, twice-weekly delivery team standups, and monthly stakeholder updates. Status updates follow a consistent template covering progress, next steps, risks, and decisions needed, ensuring transparency across all stakeholder groups.

### Quality & Continuous Improvement
Quality is embedded throughout execution with unit tests, integration tests, and end-to-end smoke tests for critical flows before release. Security scanning runs in CI, and manual QA validates feature acceptance when needed. Before any release, we verify all acceptance criteria are met, PRs are merged, CI and security scans pass, and both release notes and a rollback plan are documented. We capture continuous improvement through retrospectives held after each sprint or milestone, prioritizing 2–3 action items to avoid overload and tracking them through the project backlog.

## Process Documents

Navigate to the detailed guidance for each phase of the project lifecycle:

- **[Project Management Overview](octoacme-project-management-overview.md)** — Introduction to OctoAcme's project management approach, core roles, key artifacts, and high-level lifecycle
- **[Project Initiation Guide](octoacme-project-initiation.md)** — Steps to validate and authorize work, align stakeholders, and create a lightweight plan
- **[Project Planning](octoacme-project-planning.md)** — Turn an approved initiative into an actionable plan and backlog for delivery
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Day-to-day execution guidance, team rhythm, workflows, and progress tracking
- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — How to identify, manage, and communicate risks, dependencies, and status updates
- **[Release & Deployment Guide](octoacme-release-and-deployment.md)** — Standardized approach to releasing features to production and managing rollbacks
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and convert them into actionable improvements
- **[Roles and Personas](octoacme-roles-and-personas.md)** — Definition of typical roles and responsibilities in OctoAcme projects

## Getting Started

**For new team members:** Start with the [Project Management Overview](octoacme-project-management-overview.md) to understand our principles, roles, and artifacts. Then review [Roles and Personas](octoacme-roles-and-personas.md) to see how your role fits in.

**For Project Managers:** Use [Project Initiation Guide](octoacme-project-initiation.md) to kick off a new project, then [Project Planning](octoacme-project-planning.md) to build your plan. Reference [Risk Management & Communication](octoacme-risks-and-communication.md) and [Execution & Tracking](octoacme-execution-and-tracking.md) throughout delivery.

**For Product Managers:** Start with [Project Initiation Guide](octoacme-project-initiation.md) to define success metrics, then use [Project Planning](octoacme-project-planning.md) to prioritize the backlog.

**For Developers & QA:** Review [Execution & Tracking](octoacme-execution-and-tracking.md) for workflow and quality standards, and [Release & Deployment Guide](octoacme-release-and-deployment.md) before shipping.

## Questions or Feedback?

These docs are living artifacts. If you find gaps, have suggestions for improvement, or want to add new processes, open an issue using the ["Add Content to Project Management Process Docs"](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template.
