# OctoAcme Project Management Documentation

## Overview

OctoAcme follows a lightweight, outcome-driven project management approach organized around a simple lifecycle: Initiation → Planning → Execution → Release → Close & Retrospective. The process emphasizes customer-first decision making, iterative delivery of small, testable increments, clear ownership of outcomes (with a named Project Manager and Product Lead for each initiative), and data-informed adjustments. Psychological safety and continuous learning are encouraged so teams can iterate quickly and improve their practices over time.

Work is tracked using a prioritized backlog and a project board with defined workflow states. Planning turns approved initiatives into a release plan and a set of shippable backlog items with clear acceptance criteria and estimates. During execution, teams follow a pull-request driven workflow with automated CI checks, small changelists, and required approvals to ensure quality and maintainability. Releases are governed by checklists and smoke tests, and retrospectives capture learnings and convert them into action items.

Roles and communication cadence are explicit: Product Managers define outcomes and success metrics, Project Managers coordinate delivery, Developers implement and test, and QA validates acceptance criteria. The team rhythm includes daily standups for blocking and coordination, weekly delivery syncs, demos at the end of each sprint/milestone, and regular stakeholder updates. Escalation paths are defined to route risks from the team level to Product Lead and Sponsor as needed.

Quality assurance is integrated into every stage. Authors are expected to include unit and integration tests, run end-to-end smoke tests for critical flows, and use security scanning in CI. Manual QA is applied where appropriate. Release and rollback playbooks ensure safe deployments, while dashboards and velocity/burndown tracking close the loop on progress and reliability.

---

## Project Lifecycle at a Glance

- Initiation: Problem definition, one-pager, stakeholder alignment, decision gate
- Planning: Backlog creation, estimations, Definition of Done, release plan
- Execution: Development, PR reviews, CI, QA, and tracking on the project board
- Release: Pre-release checks, staging verification, production rollout, post-deploy verification
- Close & Retrospective: Capture learnings, create action items, and feed improvements back into the backlog

---

## Core Documentation

- **Project Management Overview** — [octoacme-project-management-overview.md](octoacme-project-management-overview.md)
- **Project Initiation Guide** — [octoacme-project-initiation.md](octoacme-project-initiation.md)
- **Project Planning** — [octoacme-project-planning.md](octoacme-project-planning.md)
- **Execution & Tracking** — [octoacme-execution-and-tracking.md](octoacme-execution-and-tracking.md)
- **Risks & Communication** — [octoacme-risks-and-communication.md](octoacme-risks-and-communication.md)
- **Release & Deployment Guide** — [octoacme-release-and-deployment.md](octoacme-release-and-deployment.md)
- **Retrospective & Continuous Improvement** — [octoacme-retrospective-and-continuous-improvement.md](octoacme-retrospective-and-continuous-improvement.md)
- **Roles & Personas** — [octoacme-roles-and-personas.md](octoacme-roles-and-personas.md)

---

## Quick Reference: When to use each doc

- Getting started / overview: Read **Project Management Overview**
- Starting a new project: Follow **Project Initiation Guide** and create the One-pager
- Planning work and releases: Use **Project Planning** to build the backlog and schedule
- Day-to-day delivery: Operate from **Execution & Tracking** and the project board
- Managing risks & stakeholders: Follow **Risks & Communication** and maintain the Risk Register
- Preparing and performing releases: Follow **Release & Deployment Guide**
- Learning and improvement: Run retrospectives per **Retrospective & Continuous Improvement** and add action items to the backlog

---

## How to contribute or request changes

To propose edits or additions to these process docs, please open an issue using the "Add Content to Project Management Process Docs" template located in `.github/ISSUE_TEMPLATE/`. Provide a summary, rationale, and suggested content. This repository uses issues to review documentation changes before merging.

---

Closes #2
