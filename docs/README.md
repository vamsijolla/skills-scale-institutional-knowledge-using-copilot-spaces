# OctoAcme Project Management Docs

Welcome to the documentation for OctoAcme's project management processes!

## Summary

OctoAcme follows a structured, customer-first approach to project management built on **iterative delivery, clear ownership, data-informed decisions, and psychological safety**. Our methodology ensures consistent, repeatable execution across all cross-functional projects.

### Key Processes

**Initiation & Planning**: Every project begins with a One-pager that defines the problem, success metrics, stakeholders, and timeline. Projects move through a formal decision gate before planning, ensuring alignment and resource availability.

**Structured Roles**: We operate with clearly defined personas—Project Managers coordinate delivery and manage risks, Product Managers define outcomes and prioritize work, Developers implement features with quality standards, and QA/Testing validates acceptance criteria. This role clarity enables efficient execution and clear accountability.

**Execution & Communication**: Teams use GitHub Projects for workflow management and follow a consistent communication cadence: daily standups, weekly PM/Product Manager syncs, twice-weekly delivery team standups, and monthly stakeholder updates. A three-level risk escalation path ensures blockers surface quickly and receive appropriate attention.

**Quality & Release Management**: Small pull requests (≤400 lines) with automated CI testing, unit/integration/smoke tests, and security scanning maintain reliability. Pre-release requirements include passing tests, smoke tests in staging, and documented rollback plans. Post-release verification ensures production stability.

**Continuous Improvement**: Retrospectives after each sprint, release, or milestone capture learnings and prioritize 2–3 actionable improvements. A live Risk Register tracks risks throughout execution, and a single source of truth (project README or release doc) keeps stakeholders informed.

---

## Available Documentation

### Core Process Docs

- **[Project Management Overview](octoacme-project-management-overview.md)** — High-level introduction to OctoAcme's approach, principles, roles, and lifecycle.

- **[Project Initiation](octoacme-project-initiation.md)** — Guidance on validating business need, aligning stakeholders, and authorizing work with a One-pager.

- **[Project Planning](octoacme-project-planning.md)** — Steps to turn approved initiatives into actionable plans: backlog creation, estimation, dependencies, and release planning.

- **[Execution and Tracking](octoacme-execution-and-tracking.md)** — Day-to-day execution guidance: team rhythm, workflows, quality assurance, reporting, and blocker escalation.

- **[Risks and Communication](octoacme-risks-and-communication.md)** — Risk identification, assessment, and monitoring; stakeholder communication templates and escalation paths.

- **[Release and Deployment](octoacme-release-and-deployment.md)** — Standardized release process: pre-release requirements, deployment checklist, rollback procedures, and release notes.

- **[Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Running effective retrospectives and converting learnings into tracked action items.

### Reference

- **[Roles and Personas](octoacme-roles-and-personas.md)** — Definitions of typical roles (Developers, Product Managers, Project Managers) used throughout OctoAcme documentation.

---

## How to Use These Docs

- **New team members**: Start with the [Project Management Overview](octoacme-project-management-overview.md), then reference specific docs as you encounter each phase of a project.
- **Starting a new project**: Begin with [Project Initiation](octoacme-project-initiation.md), then follow the lifecycle through planning, execution, release, and retrospective.
- **Seeking guidance**: Use this README to locate the relevant process doc for your current activity.
- **Contributing improvements**: If you identify gaps, refinements, or best practices to add, use the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template.

---

## Feedback & Updates

These docs are living artifacts. If you have questions, identify gaps, or want to propose updates, please create an issue using the process doc update template.
