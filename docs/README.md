# OctoAcme Project Management Docs

Overview
OctoAcme uses a lightweight, iterative project management approach focused on clear ownership, measurable outcomes, and continuous improvement. These docs collect the core process guides for initiation, planning, execution & tracking, release & deployment, risk management & communication, and retrospectives so teams can discover and follow consistent practices.

Quick links to process docs
- Project Management Overview: docs/octoacme-project-management-overview.md
- Project Initiation Guide: docs/octoacme-project-initiation.md
- Project Planning: docs/octoacme-project-planning.md
- Execution & Tracking: docs/octoacme-execution-and-tracking.md
- Risks & Communication: docs/octoacme-risks-and-communication.md
- Release & Deployment: docs/octoacme-release-and-deployment.md
- Retrospective & Continuous Improvement: docs/octoacme-retrospective-and-continuous-improvement.md
- Roles & Personas: docs/octoacme-roles-and-personas.md

Project management overview
OctoAcme runs projects with a lightweight, repeatable lifecycle that moves work from initiation through planning, execution, release, and retrospective. Initiation centers on a Project One-pager that captures the problem, measurable goals, stakeholders, and a high-level timeline; a decision gate ensures work only moves into planning when success metrics and team availability are confirmed. Planning breaks approved initiatives into shippable backlog items with clear acceptance criteria, estimates, a Definition of Done, and a release plan that identifies dependencies and risks.

Execution relies on a project board workflow (Backlog → Ready → In Progress → In Review → QA → Done) and a disciplined pull-request process: small PRs when possible, linked issues and acceptance criteria, automated CI checks (tests, linter, security scans), and at least one approval before merging. The team rhythm includes daily standups for blockers, weekly delivery syncs for progress and risk review, and demos at the end of sprints or milestones. Escalation paths (team → PM → Product Lead → Sponsor) and a security incident runbook are provided to handle higher-severity issues.

Quality is enforced through unit and integration tests, end-to-end smoke tests for critical flows, CI-based security scanning, and manual QA when needed. Releases follow a checklist (acceptance criteria met, passing CI/security scans, release notes, rollback plan, and staging smoke tests) and include a rollback/incident playbook to restore a known-good state when needed. Continuous improvement is supported by regular retrospectives that produce prioritized action items tracked in the backlog and reviewed during PM syncs.

How to use and update these docs
- Keep documents updated under docs/ and propose changes using the ".github/ISSUE_TEMPLATE/Add Content to Project Management Process Docs" issue template.
- Project-specific adjustments should live in the individual project repo README or in .copilot/ for Copilot Spaces context.
- For changes to this set of process docs, open a PR that references the relevant issue (use the issue template to start).
