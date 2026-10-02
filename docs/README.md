# OctoAcme Project Management Process Documentation

This document is the central entry point for OctoAcme's project management practices. It brings together the core workflows, roles, templates, and delivery expectations used across projects so teams have a consistent, shareable source of truth. OctoAcme follows a structured, iterative delivery model that starts with stakeholder alignment and problem validation, then moves through planning, execution, release, and retrospective improvement. The goal is to balance clear ownership with fast feedback, measurable outcomes, and disciplined execution while keeping communication simple and transparent.

## Summary of OctoAcme project management processes

OctoAcme manages projects through a repeatable lifecycle that begins with initiation and ends with reflection and improvement. Prior to planning, teams validate the business need, confirm stakeholders, and draft a one-pager with objectives, success metrics, timeline, and initial risks. Once approved, teams break work into prioritized backlog items with acceptance criteria, estimates, and clear ownership. Execution is tracked through a project board and a PR workflow that emphasizes small changes, issue linkage, CI validation, and required approvals before merge. This creates a consistent rhythm for delivery while making progress, blockers, and dependencies visible to the whole team.

The operating model relies on a small set of core roles and responsibilities. Project Managers coordinate delivery, schedules, risks, and communications; Product Managers define problems, priorities, and success metrics; Developers build, test, and document the work; QA validates acceptance criteria; and stakeholders provide input, approvals, and strategic direction. Communication is intentionally regular: daily standups surface work and blockers, weekly PM/PdM syncs track progress and risks, demos review completed work, and milestone or stakeholder updates keep decision-makers informed. Escalation paths are documented so issues can move from team-level triage to product leadership and, when needed, sponsor-level attention.

Quality assurance is built into the process as a standard part of delivery, not an afterthought. New logic should include unit tests, integration tests where relevant, and end-to-end smoke tests for critical user flows. CI is expected to enforce linting and security checks before code is approved, and release gates require acceptance criteria to be met, smoke tests to pass, and rollback plans to be documented. After each sprint or release, teams use retrospectives to capture what went well, what should improve, and which action items should be added back into the backlog. This creates a continuous improvement loop that helps the organization learn quickly and apply lessons consistently.

## Project lifecycle at a glance

1. Initiation — validate the business need, align stakeholders, and define success metrics.
2. Planning — create the backlog, estimate work, and agree on milestones and responsibilities.
3. Execution — build, test, review, and iterate in short delivery cycles.
4. Release — deploy with checks, release notes, smoke tests, and stakeholder communication.
5. Close and Retrospective — capture learnings and convert actions into future improvements.

## Process documentation

### Getting started
- [Project Management Overview](./octoacme-project-management-overview.md) — high-level introduction to roles, principles, and lifecycle
- [Roles & Personas](./octoacme-roles-and-personas.md) — definitions of common project roles and responsibilities

### Phase guides
- [Project Initiation Guide](./octoacme-project-initiation.md) — validate ideas, align stakeholders, and create a project one-pager
- [Project Planning Guide](./octoacme-project-planning.md) — build backlog, estimates, milestones, and a delivery roadmap
- [Execution & Tracking Guide](./octoacme-execution-and-tracking.md) — daily execution, quality checks, reporting, and blocker management
- [Release & Deployment Guide](./octoacme-release-and-deployment.md) — standard release checks, deployment steps, rollback planning, and incident response

### Cross-cutting concerns
- [Risk Management & Communication](./octoacme-risks-and-communication.md) — risk registers, stakeholder communication, and escalation paths
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — retrospective structure and action tracking

## Key artifacts and templates

- Project One-pager / charter
- Backlog with acceptance criteria and estimates
- Risk register and dependency tracker
- Weekly status updates and stakeholder communications
- Release notes and rollback plan
- Retrospective action items with owners and due dates
- Issue template for requesting documentation updates: [.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)

## Communication cadence

- Daily team standups (15 minutes)
- Weekly PM + Product Lead alignment
- Twice-weekly delivery team updates or agreed cadence
- Sprint demos and milestone reviews
- Ad-hoc escalation for blockers, dependencies, or incidents

## Quality and delivery practices

- Small, reviewable pull requests
- Clear issue linkage and acceptance criteria
- Required CI checks, including tests and security scanning
- Manual QA when needed for feature acceptance
- Definition of Done for backlog items and releases

## Related repository context

This documentation is intended to serve as the institutional knowledge base for OctoAcme projects and to provide a consistent foundation for Copilot Spaces, onboarding, and project operations.
