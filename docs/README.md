# OctoAcme Project Management Docs

Welcome to OctoAcme's project management documentation hub. This README is the central entry point for understanding how OctoAcme plans, delivers, and continuously improves its projects. Whether you are a new team member getting oriented or a seasoned contributor looking for a quick reference, start here.

---

## Summary

**Overview & Core Principles.** OctoAcme uses a structured, lifecycle-based project management framework that applies to all cross-functional initiatives delivering product features, services, or integrations. The framework is built on five foundational values: *customer-first* (prioritize customer value and usability), *iterative delivery* (ship small, testable increments), *clear ownership* (every project has a named Project Manager and Product Lead), *data-informed decisions* (measure impact and iterate from evidence), and *psychological safety* (encourage open feedback and continuous learning). These principles ensure that every team member understands their role, every stakeholder stays informed, and every release delivers measurable value.

**Key Roles & Workflows.** Three core personas drive delivery at OctoAcme. **Project Managers (PMs)** coordinate schedules, risk, and communication across the team. **Product Managers (PdMs)** define outcomes, prioritize the backlog, and measure success. **Developers** implement features and collaborate on design and testability. Work flows through a five-phase project lifecycle: *Initiation* (problem statement, stakeholders, high-level timeline) → *Planning* (scope, resources, milestones, dependencies) → *Execution* (build, test, review, iterate) → *Release* (deploy, verify, announce) → *Retrospective* (capture learnings and next steps). Day-to-day work is tracked in GitHub Projects using six columns: **Backlog → Ready → In Progress → In Review → QA → Done**.

**Quality Assurance & Risk Management.** OctoAcme maintains high quality through a layered testing strategy: unit tests, integration tests, smoke tests, and automated security scanning are all expected before a feature ships. Pull requests are kept small (≤ 400 lines) to make reviews faster and safer. Each project maintains a **Risk Register** to log, assess, and mitigate threats to delivery. When blockers arise, a three-level escalation path is followed: first attempt resolution within the team, then escalate to the PM/PdM, and finally escalate to stakeholders or leadership if unresolved within the agreed timeframe.

**Communication & Continuous Improvement.** Consistent communication keeps everyone aligned. The standard cadence includes weekly PM + PdM syncs, twice-weekly standups for the delivery team, and monthly stakeholder updates, supplemented by ad-hoc escalations as needed. Status updates follow a shared template (progress, blockers, next steps) so information is easy to scan and act on. After every release, the team runs a structured retrospective to surface what went well and what should change. Action items from retrospectives are tracked and reviewed, reinforcing a culture of continuous improvement across all projects.

---

## Personas Quick Reference

| Persona | Primary Responsibilities |
|---|---|
| **Project Manager (PM)** | Coordinates delivery, schedules, risk management, and communications |
| **Product Manager (PdM)** | Defines outcomes, prioritizes the backlog, and measures success |
| **Developer** | Implements features, collaborates on design and testability |

---

## Process Documents

The following documents cover each stage of the OctoAcme project lifecycle in detail:

| Document | Description |
|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | High-level introduction to the framework, principles, and artifacts |
| [Project Initiation](octoacme-project-initiation.md) | Problem statement, stakeholder identification, and project charter |
| [Project Planning](octoacme-project-planning.md) | Scope, milestones, resource planning, and dependency management |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Sprint workflow, GitHub Projects board, and progress tracking |
| [Risks & Communication](octoacme-risks-and-communication.md) | Risk register, escalation paths, and communication templates |
| [Release & Deployment](octoacme-release-and-deployment.md) | Release checklist, deployment steps, and go-live verification |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Retrospective format, action item tracking, and improvement culture |
| [Roles & Personas](octoacme-roles-and-personas.md) | Detailed responsibilities for every role on a project team |

---

## How to Use These Docs

**New team members:** Start with the [Project Management Overview](octoacme-project-management-overview.md) to get a broad picture of how OctoAcme runs projects, then read [Roles & Personas](octoacme-roles-and-personas.md) to understand where you fit in. Follow the lifecycle documents in order (Initiation → Planning → Execution → Release → Retrospective) as your project progresses.

**Project Managers:** Keep the Project Charter up to date in your project repository and reference [Risks & Communication](octoacme-risks-and-communication.md) whenever blockers or risks emerge.

**Developers:** Bookmark [Execution & Tracking](octoacme-execution-and-tracking.md) for day-to-day workflow guidance and [Release & Deployment](octoacme-release-and-deployment.md) for pre-ship checklists.

**Using with Copilot Spaces:** Add the relevant process documents to your project's `.copilot/` folder so GitHub Copilot can use them as context when answering questions about your team's processes.

---

*For questions or suggestions about this documentation, open an issue or pull request in this repository.*
