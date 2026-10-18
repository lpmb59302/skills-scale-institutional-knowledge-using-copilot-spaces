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

## Additional Personas (proposed)

These personas expand clarity and accountability across delivery, design, operations, and cross-team coordination. For each persona below, include a short responsibilities list and a note on interactions with existing roles (PM, PdM, Developers, QA) when updating the roles doc.

### Engineering Manager
Responsibilities:
- Team capacity planning, hiring input, and resource allocation.
- Performance coaching, development plans, and career growth support.
- Escalate resourcing or technical impediments that impact delivery.

How they interact with existing roles:
- Works with Project Managers to align capacity and timelines.
- Coordinates with Tech Leads on implementation trade-offs and technical risks.
- Supports Developers through mentoring and staffing decisions.

### Tech Lead
Responsibilities:
- Own technical design and architecture decisions for features.
- Mentor developers, review complex code changes, and enforce coding standards.
- Coordinate technical risk mitigations and spike investigations.

How they interact with existing roles:
- Partners with Product Managers (PdM) to ensure technical feasibility of proposals.
- Works with QA to ensure testability and maintainability.
- Collaborates with Release Engineer / SRE on safe rollout strategies.

### UX Researcher / Designer
Responsibilities:
- Lead user research, usability testing, prototyping, and accessibility guidance.
- Translate qualitative findings into actionable design requirements.
- Provide design assets and interaction guidance for implementation.

How they interact with existing roles:
- Works with Product Managers to validate problems and prioritize UX work.
- Collaborates with Developers to ensure designs are implemented correctly.
- Partners with QA on accessibility and usability checks during acceptance.

### Release Engineer / SRE
Responsibilities:
- Maintain CI/CD pipelines, deployment automation, and environment hygiene.
- Define and validate rollback plans, release checklists, and post-deploy verifications.
- Monitor production health signals and own runbook automation.

How they interact with existing roles:
- Coordinates with Developers and Tech Leads to ensure changes are deployable.
- Works with Project Managers to schedule releases and communicate risk.
- Partners with Security Liaison to ensure compliance checks are integrated into pipelines.

### Support Lead / Customer Ops
Responsibilities:
- Own incident triage, customer-facing communications, and initial diagnosis for production issues.
- Maintain escalation paths and coordinate with on-call engineering.
- Feed post-release customer issues and prioritization inputs into the backlog.

How they interact with existing roles:
- Notifies Project Managers and Developers during incidents and participates in post-incident reviews.
- Provides Product Managers with customer feedback and context for prioritization.
- Works with QA to validate fixes for customer-impacting issues.

### Data Analyst / Insights
Responsibilities:
- Define success metrics, build dashboards, and analyze experiments.
- Provide data-backed recommendations for prioritization and product decisions.
- Help instrument metrics and validate data quality.

How they interact with existing roles:
- Works closely with Product Managers to set measurable outcomes and interpret results.
- Shares insights with Project Managers to inform progress tracking and reporting.
- Provides Developers with metric requirements and validation checks for instrumentation.

### Security Liaison
Responsibilities:
- Coordinate security scanning, threat assessments, dependency audits, and compliance reviews.
- Track remediation items and verify fixes before release.
- Maintain communication with security teams and escalate critical findings.

How they interact with existing roles:
- Works with Developers and Release Engineer to remediate findings before deployment.
- Alerts Project Managers and Product Managers of high-impact security issues affecting timelines.
- Partners with QA for security-focused test scenarios.

### Program Manager (if applicable)
Responsibilities:
- Coordinate schedules and dependencies across multiple projects or teams.
- Manage cross-team roadmaps, stakeholder communications, and program-level risks.
- Facilitate cross-team planning and alignment workshops.

How they interact with existing roles:
- Partners with Project Managers to align release windows and surface cross-team dependencies.
- Works with Product Managers to coordinate portfolio priorities and reporting.
- Escalates issues to leadership when cross-team alignment is required.

---

## How these personas are used in practice
- When assigning work, call out primary and secondary owners and handoff points (e.g., “Tech Lead — architecture; Developer — implementation; QA — acceptance”).
- Add a short "Interactions" bullet for each role in the roles doc to reduce ambiguity.
- Use the personas to clarify RACI-style responsibilities for critical workflows such as releases, incidents, and major architectural changes.

---
