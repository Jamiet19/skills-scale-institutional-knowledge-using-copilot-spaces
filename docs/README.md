# OctoAcme Project Management Docs

This folder contains the process documentation for how OctoAcme plans, executes, and continuously improves its projects. Use it as the starting point for understanding our project management approach and finding the right process guide for your needs.

---

## Overview

OctoAcme follows a structured project lifecycle — from initiation through retrospectives — built around iterative delivery, clear ownership, and continuous improvement.

### Project Lifecycle

Projects move through five stages:

1. **Initiation** — Define the problem, align stakeholders, establish success metrics, and produce a lightweight one-pager with key milestones, risks, and resource needs.
2. **Planning** — Kick off with stakeholders, build a prioritized backlog, define acceptance criteria and a Definition of Done, estimate work, and map dependencies.
3. **Execution** — Track work on a project board (Backlog → Ready → In Progress → In Review → QA → Done) to maintain visibility and keep flow moving.
4. **Release** — Verify that acceptance criteria are met, CI and security scans pass, release notes are prepared, and rollback plans are documented before deploying.
5. **Retrospective** — Capture what went well, what can improve, and concrete action items to continuously refine the process.

### Core Roles

| Role | Primary Responsibility |
|---|---|
| **Project Manager (PM)** | Coordinates delivery, schedules, risk management, and communications |
| **Product Manager (PdM)** | Owns product vision, backlog prioritization, and success metrics |
| **Developers** | Implement features, write tests, and participate in reviews |
| **QA / Testing** | Validates quality against acceptance criteria |
| **Stakeholders** | Provide input, alignment, and approvals |

### Communication & Escalation

- **Daily standups** — surface progress, blockers, and dependencies.
- **Weekly delivery syncs** — review progress, risks, and decisions.
- **Regular stakeholder updates** — keep everyone aligned on status.
- **Escalation path**: team-level triage → PM → Product Lead → Sponsor.

A single source of truth (the project README or release document) is maintained for status to avoid confusion and keep updates consistent.

### Quality Assurance & Release

Quality is built into the workflow rather than treated as a final gate:

- Unit tests for all new logic; integration tests where appropriate.
- End-to-end smoke tests for critical flows.
- CI-based linting, automated tests, and security scanning on every change.
- Manual QA for feature acceptance when needed.
- Release readiness requires passing CI, security scans, documented release notes, and a rollback plan.

---

## Document Index

| Document | Description |
|---|---|
| [Project Initiation](octoacme-project-initiation.md) | Problem validation, one-pager template, and the initiation checklist |
| [Project Planning](octoacme-project-planning.md) | Kickoff steps, backlog setup, milestones, and Definition of Done |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Project board workflow, daily standups, and progress tracking |
| [Risks & Communication](octoacme-risks-and-communication.md) | Risk register, escalation paths, and stakeholder communication templates |
| [Release & Deployment](octoacme-release-and-deployment.md) | Release checklist, deployment steps, and rollback guidance |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Retrospective format, action items, and process improvement loop |
| [Roles & Personas](octoacme-roles-and-personas.md) | Detailed responsibilities and communication patterns for each role |
| [Project Management Overview](octoacme-project-management-overview.md) | Principles, key artifacts, and a high-level lifecycle summary |
