# OctoAcme Project Management Process Documentation

Welcome to the OctoAcme project management knowledge base. This guide centralizes all project management processes, roles, and artifacts used across OctoAcme projects.

## Quick Overview

OctoAcme follows a structured, iterative approach to project delivery built on these core principles:

- **Customer-first**: prioritize customer value and usability
- **Iterative delivery**: deliver small, testable increments
- **Clear ownership**: each project has a named Project Manager (PM) and Product Lead
- **Data-informed decisions**: measure impact and iterate based on evidence
- **Psychological safety**: encourage feedback and learning

## Project Lifecycle

Every OctoAcme project follows these phases:

1. **Initiation** — Validate the business need and align stakeholders
2. **Planning** — Break work into shippable increments and create a delivery roadmap
3. **Execution** — Build, test, review, and iterate toward milestones
4. **Release** — Deploy to production with proper safeguards and communication
5. **Close & Retrospective** — Capture learnings and plan improvements

## Process Documentation

### Getting Started

- [Project Management Overview](./octoacme-project-management-overview.md) — High-level introduction to OctoAcme's approach, roles, and artifacts
- [Roles & Personas](./octoacme-roles-and-personas.md) — Definitions of Project Managers, Product Managers, Developers, and QA roles

### Phase Guides

- [Project Initiation Guide](./octoacme-project-initiation.md) — Steps to validate an idea and get stakeholder alignment
- [Project Planning Guide](./octoacme-project-planning.md) — How to create a plan, backlog, and delivery roadmap
- [Execution & Tracking Guide](./octoacme-execution-and-tracking.md) — Day-to-day delivery, quality standards, and progress tracking
- [Release & Deployment Guide](./octoacme-release-and-deployment.md) — How to safely release features to production

### Cross-Cutting Concerns

- [Risk Management & Communication](./octoacme-risks-and-communication.md) — Identifying, tracking, and communicating risks and dependencies
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — Running retros and converting learnings into action items

## Key Artifacts & Templates

Common deliverables and templates used across projects:

- **Project One-pager** — High-level overview of problem, goals, success metrics, and timeline (see Project Initiation Guide)
- **Project Charter** — Detailed scope, resources, milestones, and stakeholders
- **Risk Register** — Tracking table for risks, impact, likelihood, and mitigation plans
- **Backlog with Acceptance Criteria** — Prioritized work items with clear acceptance criteria and Definition of Done
- **Release Notes** — Summary of changes, migrations, and known issues
- **Retrospective Action Items** — Learnings and improvements tracked with owners and due dates

## Communication Cadence

- **Daily**: Team standups (15 min) — progress, blockers, dependencies
- **Weekly**: PM + Product Lead sync; stakeholder status updates
- **Per Sprint**: Planning, demo/review, retrospective
- **As Needed**: Risk escalations and decision gates

## Roles at a Glance

| Role | Focus | Key Responsibilities |
|------|-------|----------------------|
| **Project Manager** | Delivery & coordination | Schedules, risks, communications, timelines |
| **Product Manager** | Outcomes & prioritization | Success metrics, roadmap, backlog prioritization |
| **Developers** | Implementation | Code quality, tests, design, technical risks |
| **QA/Testing** | Quality | Validation, acceptance criteria, smoke tests |
| **Stakeholders** | Business value | Inputs, approvals, sponsor support |

See [Roles & Personas](./octoacme-roles-and-personas.md) for detailed role definitions.

## Quick Reference Checklists

### Project Initiation Checklist
- [ ] One-pager completed and reviewed by Product Lead
- [ ] Stakeholder alignment confirmed
- [ ] Decision: Approve to move into planning?
- [ ] Initial artifacts added to repo

### Project Planning Checklist
- [ ] Kickoff meeting held
- [ ] Backlog prioritized and estimated
- [ ] Release timeline and milestones agreed
- [ ] Definition of Done documented
- [ ] Initial test plan drafted

### Execution Checklist
- [ ] Branching and PR conventions documented
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly

### Release Checklist
- [ ] All acceptance criteria met and PRs merged
- [ ] Passing CI and security scans
- [ ] Release notes drafted
- [ ] Rollback plan documented
- [ ] Smoke tests prepared
- [ ] Post-deploy verifications completed

## Getting Help

- **New to OctoAcme?** Start with [Project Management Overview](./octoacme-project-management-overview.md) and [Roles & Personas](./octoacme-roles-and-personas.md)
- **Starting a new project?** Follow the [Project Initiation Guide](./octoacme-project-initiation.md)
- **Need to update these docs?** Use the [Add/Update Content issue template](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)
- **Questions or gaps?** Raise an issue and tag the PM or Product Lead

---

**Last Updated**: October 2, 2026  
**Maintained by**: OctoAcme Project Management Team
