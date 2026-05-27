# OctoAcme Project Management Docs

This README serves as a central index and orientation resource for all project management process documents used by the OctoAcme team.

## Overview of OctoAcme Project Management Processes

OctoAcme follows a structured, customer-first project lifecycle that emphasizes iterative delivery and clear ownership. The process spans five key phases: **Initiation** (problem statement and stakeholder alignment), **Planning** (scope definition and backlog creation), **Execution** (build, test, and iterate), **Release** (deploy to production with safety checks), and **Close & Retrospective** (capture learnings). Each phase is governed by decision gates and checkpoints to ensure alignment before proceeding. The organization prioritizes data-informed decisions, psychological safety, and delivering small, testable increments to users.

OctoAcme operates with clear role separation to ensure accountability and expertise: **Project Managers** coordinate schedules, risks, and communications while managing dependencies; **Product Managers** define what to build, prioritize the backlog, and measure success through metrics; **Developers** implement features with quality standards, write tests, and contribute to planning; and **QA/Testing** teams validate acceptance criteria and quality gates. Each project has a named PM and Product Lead who own the delivery outcome. This role clarity, combined with cross-functional collaboration during kickoffs and planning sessions, enables faster decision-making and reduces bottlenecks.

OctoAcme maintains a structured communication cadence—daily standups (15 min), weekly delivery syncs, and monthly stakeholder updates—to keep all parties informed and enable rapid escalation when needed. The organization uses a Risk Register to track potential issues by ID, description, impact, likelihood, owner, and mitigation plan, with reviews embedded in weekly syncs. An escalation hierarchy (team → PM → Product Lead → Sponsor) ensures blockers surface quickly. Weekly status templates, incident playbooks, and consistent use of a project board (GitHub Projects) as a single source of truth help stakeholders stay synchronized without excessive meetings.

Quality is embedded throughout OctoAcme's execution model, not bolted on at the end. Requirements include unit tests for new logic, integration tests where applicable, end-to-end smoke tests before release, and security scanning in CI. Pull requests are kept small (≤ 400 lines when possible), require at least one approval, and must link to issues with clear acceptance criteria. The team uses a Definition of Done checklist, tracks velocity and burndown, and conducts demos at the end of each sprint. This combination of automated testing, code review discipline, and regular demonstrations ensures features meet acceptance criteria before reaching production, while continuous improvement retrospectives after each sprint or release drive process refinement.

---

## Core Processes

OctoAcme's project management approach is organized into six core processes:

- **Project Initiation** — Validate business need, identify stakeholders, define success criteria, and make go/no-go decision
- **Planning & Backlog** — Break work into shippable increments, estimate scope, define DoD, and identify dependencies
- **Execution & Tracking** — Build, test, review, and iterate using project boards, standups, and CI/testing
- **Risk & Communication** — Maintain risk register, provide stakeholder updates, and escalate blockers
- **Release & Deployment** — Deploy to production with pre-release gates, checklists, and rollback plans
- **Retrospective & Improvement** — Capture learnings and convert them into actionable improvements

---

## Docs Index

- [Project Management Overview](./octoacme-project-management-overview.md) — High-level introduction to OctoAcme's approach, roles, and key artifacts
- [Project Initiation Guide](./octoacme-project-initiation.md) — Steps to validate and authorize work, align stakeholders, and create a lightweight plan
- [Project Planning](./octoacme-project-planning.md) — Turn approved initiatives into actionable plans and backlogs
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — Manage day-to-day execution and track progress toward milestones
- [Risks & Communication](./octoacme-risks-and-communication.md) — Identify, manage, and communicate risks and dependencies
- [Release & Deployment Guide](./octoacme-release-and-deployment.md) — Standardize how to release features to production
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — Capture learnings and drive process improvements
- [Roles and Personas](./octoacme-roles-and-personas.md) — Define typical roles and responsibilities used in OctoAcme projects

---

## Getting Started

**New to OctoAcme?** Start with the [Project Management Overview](./octoacme-project-management-overview.md) for a concise introduction to our approach and key roles.

**Starting a new project?** Follow the [Project Initiation Guide](./octoacme-project-initiation.md) to validate your idea and align stakeholders.

**Planning or executing work?** Reference [Project Planning](./octoacme-project-planning.md) and [Execution & Tracking](./octoacme-execution-and-tracking.md) for process steps and checklists.

**Need help with risks or communication?** Consult [Risks & Communication](./octoacme-risks-and-communication.md) for templates and escalation paths.

**Preparing a release?** Use the [Release & Deployment Guide](./octoacme-release-and-deployment.md) for checklists and safety measures.

**Wrapping up or improving?** Review [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) to capture learnings and drive improvements.
