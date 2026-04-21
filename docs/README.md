# OctoAcme Project Management Docs

Welcome! This README provides a summary of OctoAcme's project management approach and serves as an index for all procedural documentation. Use this guide to understand our core workflows, explore specific processes, and accelerate your onboarding.

## Summary of OctoAcme Project Management Processes

OctoAcme follows a structured lifecycle-based approach to project management that spans five core phases: **Initiation, Planning, Execution, Release, and Closure & Retrospective**. The Initiation phase focuses on validating business need and securing stakeholder alignment through a lightweight Project One-pager that captures the problem statement, success metrics, and key risks. Once approved, the Planning phase breaks work into shippable increments using a prioritized backlog with clear acceptance criteria, estimates, and a Definition of Done. This foundation enables the team to identify dependencies, manage risks proactively, and create a realistic release timeline before work begins.

During **Execution and Tracking**, OctoAcme emphasizes iterative delivery supported by a consistent team rhythm: daily 15-minute standups focused on progress and blockers, weekly delivery syncs to show status and flag risks, and regular demos at sprint or milestone boundaries. The team uses GitHub Projects to visualize workflow (Backlog → Ready → In Progress → In Review → QA → Done) and maintains quality through unit tests, integration tests, end-to-end smoke tests, security scanning in CI, and manual QA for feature acceptance. A three-level blocker escalation system (team triage → PM to Product Lead → sponsor-level escalation) ensures risks are surfaced and resolved promptly.

OctoAcme defines clear roles with distinct accountability: **Project Managers** coordinate schedules, risks, and communications; **Product Managers** own vision, prioritization, and success metrics; **Developers** implement features and collaborate on design and testability; and **QA/Testing** validates acceptance criteria. **Release and Deployment** is standardized to reduce risk, requiring all acceptance criteria met, CI passing, smoke tests prepared, and a documented rollback plan. Finally, **Retrospectives** are held after each sprint, release, or milestone to capture learnings and convert them into actionable improvements tracked in the backlog.

Throughout all phases, OctoAcme prioritizes **customer-first thinking, iterative delivery, clear ownership, data-informed decisions, and psychological safety**. Stakeholder communication is continuous through weekly status templates, milestone-based updates, and a single source of truth in project documentation. Risk management is embedded throughout via a Risk Register (ID, Description, Impact, Likelihood, Owner, Mitigation, Status) reviewed weekly, and cross-functional dependencies are marked and escalated during syncs to maintain transparency and alignment.

## Docs Index

Navigate to any process document below for detailed guidance:

- **[Project Management Overview](./octoacme-project-management-overview.md)** — High-level introduction to OctoAcme principles, core roles, key artifacts, and communication cadence.
- **[Project Initiation Guide](./octoacme-project-initiation.md)** — Steps to validate business need, align stakeholders, and create a Project One-pager before moving into detailed planning.
- **[Project Planning](./octoacme-project-planning.md)** — How to break work into shippable increments, define acceptance criteria, estimate scope, and identify dependencies.
- **[Execution & Tracking](./octoacme-execution-and-tracking.md)** — Daily standups, project board workflows, quality & testing practices, and blocker escalation during delivery.
- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** — Maintaining a risk register, identifying escalation paths, and providing consistent stakeholder updates.
- **[Release & Deployment Guide](./octoacme-release-and-deployment.md)** — Pre-release requirements, deployment checklists, rollback procedures, and release note templates.
- **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** — How to run retrospectives, capture action items, and convert learnings into ongoing improvements.
- **[Roles & Personas](./octoacme-roles-and-personas.md)** — Detailed descriptions of Project Manager, Product Manager, Developer, and QA/Testing responsibilities and goals.

## Quick Links for New Team Members

- **Getting started?** Begin with the [Project Management Overview](./octoacme-project-management-overview.md) for a 5-minute introduction.
- **Starting a new project?** Follow the [Project Initiation Guide](./octoacme-project-initiation.md).
- **Need a template or checklist?** Check the relevant process doc — each includes actionable checklists and templates.
- **Questions about your role?** See [Roles & Personas](./octoacme-roles-and-personas.md).

## Contributing to These Docs

If you'd like to propose updates or new content, please use the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template. This ensures your feedback is tracked and reviewed collaboratively.