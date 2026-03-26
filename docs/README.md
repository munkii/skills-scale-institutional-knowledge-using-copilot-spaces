# OctoAcme Project Management Docs

Welcome! This directory contains the complete project management process documentation for OctoAcme. Whether you're a new team member getting oriented or an experienced contributor looking for specific guidance, this README will help you navigate our processes and find the right document.

## Overview of Project Management Processes

OctoAcme follows a structured, iterative approach to project management built around clear ownership, customer value, and continuous improvement. Our organization operates through a **five-phase lifecycle**: Initiation, Planning, Execution, Release, and Close & Retrospective. Each project begins with a lightweight Project One-pager that establishes the problem statement, SMART objectives, success metrics, stakeholders, and timeline. This initial document serves as a decision gate—once the Product Lead and sponsor approve it, the project moves into planning where the team breaks work into shippable increments, estimates effort, defines acceptance criteria, and maps dependencies. Throughout this process, psychological safety and data-informed decision-making are core principles, ensuring teams can experiment, learn, and adapt based on measurable outcomes.

The **core roles** driving OctoAcme projects include the **Project Manager (PM)**, who coordinates delivery, timelines, risk, and communications; the **Product Manager (PdM)**, who defines outcomes, prioritizes the backlog, and measures success; **Developers**, who implement and test features collaboratively; and **QA/Testing**, who validate acceptance criteria. This clear ownership model is supported by consistent communication cadences—daily 15-minute standups, weekly delivery syncs, twice-weekly team standups, and monthly stakeholder updates—ensuring alignment without overloading the team. A **Risk Register** tracks potential issues by impact, likelihood, owner, and mitigation plan, with a three-level escalation path: team triage, PM escalation to Product Lead, and sponsor-level escalation for business-critical blockers.

**Execution and quality assurance** are managed through GitHub Projects boards with defined workflow columns (Backlog, Ready, In Progress, In Review, QA, Done) and a disciplined Pull Request workflow that emphasizes small PRs (≤400 lines when possible), automated CI testing, security scanning, and at least one approval before merging. Teams maintain unit, integration, and end-to-end smoke tests for critical flows, and track velocity, burndown, and key success metrics via dashboards. Release management is equally rigorous: deployments are categorized by type (Patch, Minor, Major), require passing tests and drafted release notes, and include rollback plans. Smoke tests run in staging before production deployment, followed by post-deploy verification and stakeholder announcements.

OctoAcme embeds **continuous improvement** through regular retrospectives after each sprint, release, or incident. These timeboxed sessions (45–75 minutes) capture what went well, what could improve, and generate 2–3 prioritized action items with clear owners and due dates. Action items are tracked in the backlog and reviewed in weekly PM syncs, creating a feedback loop that converts lessons learned into tangible process enhancements. By centralizing these practices in versioned documentation stored in `docs/` and supported by GitHub issue templates in `.github/ISSUE_TEMPLATE/`, OctoAcme ensures that institutional knowledge is accessible, searchable, and continuously refined—reducing dependency on individual team members and accelerating onboarding for new contributors.

## Documentation Index

### Getting Started

- **[Project Management Overview](./octoacme-project-management-overview.md)** — Introduction to OctoAcme's approach, principles, core roles, and lifecycle
- **[Roles and Personas](./octoacme-roles-and-personas.md)** — Detailed definitions of Developer, Product Manager, and Project Manager roles and responsibilities

### Project Lifecycle

- **[Project Initiation Guide](./octoacme-project-initiation.md)** — How to validate and authorize new work with a Project One-pager, stakeholder alignment, and decision gates
- **[Project Planning](./octoacme-project-planning.md)** — Turn approved initiatives into actionable backlogs with acceptance criteria, estimates, and release plans
- **[Execution & Tracking](./octoacme-execution-and-tracking.md)** — Day-to-day execution guidance including team rhythm, workflows, quality practices, and blocker escalation
- **[Release & Deployment Guide](./octoacme-release-and-deployment.md)** — Standardized release processes covering deployment checklists, rollback plans, and release notes

### Cross-Cutting Practices

- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** — How to identify, assess, and communicate risks using the Risk Register and escalation paths
- **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and convert them into actionable improvements after each sprint, release, or milestone

## How to Use These Docs

- **New to OctoAcme?** Start with the [Project Management Overview](./octoacme-project-management-overview.md) and [Roles and Personas](./octoacme-roles-and-personas.md) to understand our approach and your role.
- **Starting a new project?** Follow the [Project Initiation Guide](./octoacme-project-initiation.md) → [Project Planning](./octoacme-project-planning.md) sequence to kick off work the right way.
- **Managing active work?** Reference [Execution & Tracking](./octoacme-execution-and-tracking.md) and [Risk Management & Communication](./octoacme-risks-and-communication.md) for day-to-day guidance.
- **Preparing for release?** See the [Release & Deployment Guide](./octoacme-release-and-deployment.md) for checklists, rollback plans, and stakeholder communication.
- **After a milestone?** Use the [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) guide to capture learnings and drive meaningful change.

## Contributing to These Docs

Process documentation lives and evolves with our team. To suggest improvements or additions:

1. Open a new issue using the **[Add/Update Content to Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)** issue template.
2. Provide context on what is missing or unclear.
3. Suggest specific content or wording where possible.
4. Link to relevant examples or rationale to help reviewers.

All documentation is versioned in this repository, making it searchable and accessible to the entire team.

## Questions?

If you have questions about these processes or need clarification:

- Reach out to your **Project Manager** for project-specific guidance.
- Contact the **Product Lead** for process improvements or exceptions.
- Join the **#project-management** channel for general questions and discussions.
