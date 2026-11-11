# OctoAcme Project Management Docs

This folder contains OctoAcme's project management processes, roles, and working guidance. Use this README as the starting point to understand the lifecycle and navigate to each detailed guide.

## Project management process at a glance

OctoAcme follows an iterative project lifecycle: **initiation, planning, execution, release, and closeout/retrospective**. During initiation, the team validates the business need and measurable outcomes, identifies stakeholders and resources, outlines milestones and risks, and makes a go/no-go decision. Planning turns approved work into a prioritized backlog with clear acceptance criteria, estimates, a Definition of Done, identified dependencies, and a release or milestone plan.

During execution, teams deliver small increments and track work on a project board, typically moving items from Backlog and Ready through In Progress, In Review, QA, and Done. The PM coordinates schedules, risks, dependencies, and communications; the Product Manager/Product Lead defines outcomes, prioritizes work, and measures success; developers build and test; QA validates acceptance; and stakeholders provide input and approvals. Regular standups and delivery or PM–Product syncs surface progress and blockers, while weekly or milestone-based stakeholder updates keep decisions and risks visible. Blockers escalate from the team to the PM, Product Lead, and sponsor as appropriate.

Quality is integrated throughout delivery. Work should meet its acceptance criteria and Definition of Done; pull requests should be small where possible, include issue context, pass automated tests and linting, and receive the required review approval. The test approach includes unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows, security scanning, and manual QA when needed. Before release, teams confirm acceptance criteria, passing CI and security checks, release notes, smoke tests, and rollback or mitigation readiness; after deployment, they verify the release and communicate it to stakeholders and support. Retrospectives after sprints, releases, milestones, or incidents capture learning and track a small number of owned improvement actions.

## Documents

- [OctoAcme Project Management Overview](octoacme-project-management-overview.md) — principles, lifecycle, roles, artifacts, and communication cadence.
- [Project Initiation Guide](octoacme-project-initiation.md) — validating proposals, defining outcomes, aligning stakeholders, and making the planning decision.
- [Project Planning](octoacme-project-planning.md) — scope, backlog, estimates, Definition of Done, risks, dependencies, and milestones.
- [Execution & Tracking](octoacme-execution-and-tracking.md) — team rhythm, project-board workflow, pull requests, testing, metrics, and blocker escalation.
- [Risk Management & Communication](octoacme-risks-and-communication.md) — risk lifecycle, stakeholder updates, incident communication, and escalation paths.
- [Release & Deployment Guide](octoacme-release-and-deployment.md) — release readiness, deployment checks, verification, rollback, and release notes.
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — retrospective structure and tracking improvement actions.
- [Roles and Personas](octoacme-roles-and-personas.md) — responsibilities, goals, and communication patterns for developers, product managers, and project managers.
