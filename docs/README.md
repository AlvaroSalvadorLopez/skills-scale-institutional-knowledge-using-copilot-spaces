# OctoAcme Project Management Processes

OctoAcme uses an iterative, customer-first approach to deliver product outcomes. Work follows a clear lifecycle—Initiation, Planning, Execution, Release, and Close/Retrospective—backed by a set of lightweight artifacts to keep decisions visible and actionable. A Project One‑pager captures the problem, objective, and success metrics at the start; planning breaks approved work into a prioritized backlog with acceptance criteria and estimates; execution is sprint-based with a disciplined PR + CI workflow; releases follow a checklist with smoke tests and rollback plans; and retrospectives convert learnings into tracked action items.

Workflows prioritize small, shippable increments and predictable handoffs. Backlog items use a consistent template (title, description, acceptance criteria, priority, estimate, owner) and sprint planning is timeboxed to match team capacity. The repository-level workflow uses a project board (Backlog → Ready → In Progress → In Review → QA → Done). Pull requests should be small when possible, reference the related issue and acceptance criteria, run automated tests and linting in CI, and require at least one approval before merging.

Roles and responsibilities are explicit: Product Managers (PdM) define outcomes and success metrics; Project Managers (PM) coordinate schedules, risks, and communications; Developers implement and maintain code and tests; and QA validates acceptance criteria and runs manual or exploratory testing as needed. Regular cadences include daily standups, weekly PM/PdM syncs and delivery syncs, sprint demos, and monthly stakeholder updates to ensure alignment and visibility.

Quality assurance is built into each stage. The CI pipeline requires unit tests, integration tests where applicable, and security scanning; end-to-end smoke tests validate critical flows prior to release; manual QA is used for feature acceptance when necessary; and post-deploy verifications confirm production health. Teams track velocity, burndown, and product success metrics, and use dashboards for observability. Risk management is documented in a Risk Register with escalation paths (team → PM → Product Lead → Sponsor) and communication templates for weekly status and incidents.

Included docs (links):
- docs/octoacme-project-management-overview.md — Project management overview and roles
- docs/octoacme-project-initiation.md — Project initiation guide and one-pager template
- docs/octoacme-project-planning.md — Planning activities, backlog template, and checklists
- docs/octoacme-execution-and-tracking.md — Team rhythms, workflows, and execution checklist
- docs/octoacme-risks-and-communication.md — Risk register, lifecycle, and communication templates
- docs/octoacme-release-and-deployment.md — Release types, deployment checklist, and rollback plan
- docs/octoacme-retrospective-and-continuous-improvement.md — Retrospective structure and action tracking
- docs/octoacme-roles-and-personas.md — Role descriptions and responsibilities

How to use
- Keep this README updated as process docs change.
- Link this file from onboarding materials and the project root README for discoverability.
