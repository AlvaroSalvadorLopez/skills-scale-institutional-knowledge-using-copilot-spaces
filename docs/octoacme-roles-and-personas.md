# OctoAcme Personas

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

## Additional Personas (proposed additions)

These personas clarify ownership for cross-cutting concerns and make handoffs explicit. Each entry includes a role summary, responsibilities, and primary interactions with existing roles.

### Technical Program Manager (TPM)
- Role Summary:
  - Coordinates across multiple engineering streams and cross-team dependencies at the program level.
- Responsibilities:
  - Track program-level milestones, timelines, and risks.
  - Coordinate cross-team planning and dependency resolution.
  - Facilitate integration checkpoints and syncs across delivery teams.
  - Maintain program dashboards and escalate unresolved blockers.
- Interactions:
  - Works with Project Managers (PMs) on scheduling and risk escalations.
  - Partners with Product Managers (PdMs) to align priorities across streams.
  - Coordinates with Developers, Tech Leads, and Release Engineers to unblock integrations.

### Release Engineer / Deployment Lead
- Role Summary:
  - Owns release automation, deployment pipelines, and operational runbooks.
- Responsibilities:
  - Maintain and improve CI/CD pipelines and release automation.
  - Define and test deployment and rollback procedures.
  - Coordinate release windows and validate deployment readiness.
  - Ensure release automation meets security and compliance checks.
- Interactions:
  - Works with Developers and QA to ensure artifacts are releasable.
  - Coordinates with PM for deployment windows and communications.
  - Engages with SRE/Observability for post-deploy verifications.

### Observability / SRE Engineer
- Role Summary:
  - Ensures systems are observable, reliable, and meet defined service-level objectives (SLOs).
- Responsibilities:
  - Define monitoring, alerting, and SLOs for services.
  - Implement instrumentation and dashboards for key metrics.
  - Participate in on-call rotations and incident response.
  - Run post-deploy verifications and reliability reviews.
- Interactions:
  - Works with Developers to implement telemetry and remediation.
  - Partners with PM/PdM to set reliability targets tied to product goals.
  - Collaborates with Support/On-call teams during incidents.

### UX Researcher / Designer
- Role Summary:
  - Validates user needs and shapes product decisions through research and design.
- Responsibilities:
  - Conduct lightweight research, usability tests, and prototypes.
  - Define UX acceptance criteria and validate designs against user needs.
  - Provide design assets, specs, and accessibility guidance.
- Interactions:
  - Partners with PdM to define user-focused success metrics.
  - Works with Developers and QA to ensure deliverables match UX intent.
  - Shares findings with stakeholders to inform prioritization.

### Business Analyst / Data Analyst
- Role Summary:
  - Bridges business requirements and data-driven measurement.
- Responsibilities:
  - Clarify and document business requirements and workflows.
  - Define metrics, instrumentation needs, and post-release analysis plans.
  - Analyze impact after release and report insights.
- Interactions:
  - Works with PdM to translate objectives into measurable metrics.
  - Collaborates with Developers to ensure telemetry and analytics are implemented.
  - Informs PM and Product Lead about measurement-related risks and mitigations.

### Support Lead / Customer Success Representative
- Role Summary:
  - Represents customer-facing teams and owns operational customer feedback loops.
- Responsibilities:
  - Triage and categorize customer-reported issues.
  - Surface recurring problems and customer impact to the team.
  - Maintain knowledge-base and runbooks for common support flows.
- Interactions:
  - Works with PM/PdM for prioritization and to inform the Risk Register.
  - Coordinates with Developers and QA to reproduce and fix issues.
  - Coordinates release and post-release communications with the Change Manager.

### Change Manager / Communications Lead
- Role Summary:
  - Owns stakeholder communications and rollout coordination for releases and major changes.
- Responsibilities:
  - Prepare release announcements, internal playbooks, and training materials.
  - Coordinate stakeholder briefings and external communications.
  - Manage rollout plans and adoption tracking.
- Interactions:
  - Partners with PM and Product Lead to craft messaging.
  - Works with Support and Customer Success to ensure documentation and training are available.
  - Coordinates with Release Engineer for timing and mitigation messaging.

---

## Suggested format for adding personas
For each persona added to this document, include:
- Role summary (1–2 sentences)
- Responsibilities (bulleted)
- Primary interactions (who they coordinate with and when)
- Example hand-offs / checklist entries (optional)

---

## How these additions improve outcomes
- Clarifies ownership for releases, reliability, and user research, reducing ambiguity.
- Reduces rework by making expectations explicit (for example, who ensures telemetry and release readiness).
- Shortens escalation paths and improves stakeholder communications.
- Speeds onboarding by providing clear role descriptions and typical handoffs.

---

## Next steps (implementation guidance)
- Add the above personas to docs/octoacme-roles-and-personas.md.
- Review with PM/PdM and representatives from Engineering, QA, Support, and Security.
- Iterate wording based on feedback and add short example checklists for critical handoffs, such as release readiness, observability signoff, and customer communications.

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

