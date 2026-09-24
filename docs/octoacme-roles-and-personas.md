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

## Security Leads

### Role Summary
Security Leads guide security and compliance activities throughout the project lifecycle. They help teams identify threats early and establish the security requirements needed for a safe release.

### Responsibilities
- Define security requirements and review project risks
- Coordinate threat modeling, security testing, and compliance checks
- Advise on secure architecture, data handling, and access controls
- Track security findings and confirm remediation or documented acceptance
- Provide security input for release readiness and incident response

### Interaction with Existing Roles
- Partner with the Product Manager to translate customer, regulatory, and business needs into security requirements
- Work with Developers on secure design, implementation, and remediation of findings
- Coordinate with the Project Manager to track security risks, dependencies, and escalations
- Consult with QA Leads and Release Managers to include security checks in quality gates and deployment decisions

---

## QA Leads / Test Managers

### Role Summary
QA Leads and Test Managers own the overall test strategy and quality gates for a project. They coordinate validation activities so that delivered work meets acceptance criteria and is fit for release.

### Responsibilities
- Define the test strategy, coverage expectations, and quality risks
- Coordinate unit, integration, end-to-end, regression, and manual testing as appropriate
- Confirm acceptance criteria and Definition of Done are testable
- Track defects, risks, and unresolved quality issues
- Recommend release readiness based on evidence from testing

### Interaction with Existing Roles
- Work with Product Managers to clarify acceptance criteria and validate feature behavior against intended outcomes
- Collaborate with Developers on testability, automation, defect triage, and fixes
- Coordinate with the Project Manager on test milestones, risks, and status reporting
- Partner with Security Leads and Release Managers to include security and deployment smoke tests in release gates

---

## Release Managers

### Role Summary
Release Managers coordinate the movement of completed work through staging and production. They make deployment responsibilities, readiness checks, rollback plans, and post-release verification explicit.

### Responsibilities
- Maintain the release plan, deployment schedule, and release checklist
- Confirm required approvals, CI results, security scans, and smoke tests are complete
- Coordinate deployment communications and operational handoffs
- Ensure rollback or mitigation plans are documented and actionable
- Track post-deployment verification, issues, and release follow-up actions

### Interaction with Existing Roles
- Work with Project Managers to align release milestones, dependencies, stakeholder updates, and escalation paths
- Coordinate with Product Managers on scope, release notes, customer impact, and outcome measurement
- Partner with Developers on deployment automation, migrations, observability, and rollback implementation
- Rely on QA Leads for quality readiness and Security Leads for security sign-off or risk acceptance

---

## Data / Analytics Owners

### Role Summary
Data and Analytics Owners ensure that project decisions and outcome measurement are supported by reliable data. They connect delivery work to the success metrics defined during initiation and planning.

### Responsibilities
- Define measurement plans, instrumentation needs, and reporting requirements
- Validate the availability, quality, and interpretation of project data
- Build or coordinate dashboards for usage, errors, latency, and other key signals
- Report baseline, launch, and post-release results
- Identify insights that support prioritization and continuous improvement

### Interaction with Existing Roles
- Partner with Product Managers to define measurable success criteria and assess customer impact
- Work with Developers on instrumentation, event definitions, data contracts, and observability
- Coordinate with Project Managers on reporting cadence, milestone reviews, and decision logs
- Collaborate with Release Managers on launch monitoring and post-deployment verification
- Share findings with stakeholders to support evidence-based decisions and retrospectives

---

## Engineering Leads / Team Leads

### Role Summary
Engineering Leads and Team Leads provide technical direction and help delivery teams coordinate implementation, dependencies, and engineering trade-offs across workstreams.

### Responsibilities
- Guide technical design and implementation decisions
- Break down complex work and support estimation and capacity planning
- Coordinate technical dependencies and integration points
- Raise engineering risks and propose mitigations
- Support code quality, operational readiness, and knowledge sharing

### Interaction with Existing Roles
- Collaborate with Developers on design reviews, implementation, testing, and technical growth
- Partner with Product Managers and Project Managers to balance scope, timeline, capacity, and technical debt
- Coordinate with QA Leads on testability and with Security Leads on secure design
- Work with Release Managers on operational readiness, deployment automation, and rollback plans

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Assign the applicable persona as an accountable owner in project plans, risk registers, quality gates, release checklists, and outcome reports.

