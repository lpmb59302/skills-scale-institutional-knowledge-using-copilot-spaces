# OctoAcme Project Management Processes

This folder contains OctoAcme's program management process documents. The README below provides quick links to each doc and a concise overview of the project management practices the team follows.

## Overview

OctoAcme runs iterative, customer-first projects with clearly defined roles and lightweight artifacts. Work begins with a Project One-pager to confirm the problem, objective, success metrics, stakeholders, and a high-level timeline. Once approved, initiatives move into planning where the team breaks work into shippable backlog items, defines acceptance criteria and a Definition of Done, and identifies dependencies and risks recorded in a Risk Register.

Execution follows short, iterative cycles supported by a project board (Backlog → Ready → In Progress → In Review → QA → Done). The team uses daily standups to surface progress and blockers, weekly delivery syncs to review progress and risks, and scheduled demos at sprint or milestone ends. Pull requests should be small, reference the related issue, include acceptance criteria, and run CI and security scans before merging. At least one approval is required before merging.

Quality assurance relies on a mix of automated checks and manual validation. Developers are expected to add unit and integration tests for new logic, and the team runs end-to-end smoke tests for critical flows prior to release. CI pipelines enforce tests, linting, and security scanning. Releases follow a checklist-driven process: deploy to staging, run smoke tests, and then deploy to production with rollback plans and post-deploy verification.

## Process Documents
- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Release & Deployment](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Roles & Personas](octoacme-roles-and-personas.md)

## How to use

- Start with the Project Management Overview to understand roles and cadence.
- Use the Project One-pager in Initiation when starting new work.
- Follow Planning and Execution docs for day-to-day practices and tracking.
- Capture improvements and action items in retrospectives and add them to the backlog.

---

*This README was added to improve discoverability and onboarding for OctoAcme's process docs.*