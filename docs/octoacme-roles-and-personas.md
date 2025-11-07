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

## Change Manager

### Role Summary
Oversees change control and ensures changes are evaluated, approved, communicated, and implemented with minimal disruption.

### Responsibilities
- Maintain change log and change request backlog
- Triage and document change requests
- Coordinate impact analysis with Project Manager, Product Owner, and Engineering leads
- Convene change review sessions (ad-hoc or scheduled)
- Coordinate with Release Manager for scheduling approved changes

### Interactions
- Project Manager: for impact and scheduling
- Release Manager: for release coordination and gating
- Stakeholder Liaison: for external stakeholder communications

### Decision Authority
Can approve non-scope-impacting changes; escalates higher-impact changes to Steering Committee or Sponsor.

### Typical Deliverables
Change Request forms, change log, change review minutes

### Hand-off Acceptance Criteria
Change has documented scope, impact assessment, and approvals recorded in the change log.

---

## Stakeholder Liaison

### Role Summary
Single point of contact for external stakeholders and cross-team stakeholder management.

### Responsibilities
- Maintain stakeholder contact list and communication preferences
- Gather and synthesize stakeholder feedback
- Escalate stakeholder concerns to Project Manager or Sponsor
- Coordinate stakeholder demos and updates

### Interactions
- Project Manager & Product Owner: to align priorities and messaging
- Change Manager: to reflect stakeholder impacts of proposed changes

### Decision Authority
Can request clarifications and escalate concerns; does not unilaterally change scope.

### Typical Deliverables
Stakeholder register, summary notes, stakeholder-facing updates

### Hand-off Acceptance Criteria
Stakeholder requests logged, with owner and expected response timeline assigned.

---

## Compliance Lead

### Role Summary
Ensures projects adhere to legal, regulatory, and organizational policy requirements.

### Responsibilities
- Identify applicable regulations and policy requirements
- Conduct compliance reviews at initiation and major milestones
- Maintain records and evidence of compliance checks
- Liaise with Risk Manager for compliance-related risks

### Interactions
- Risk Manager & Project Manager: for risk treatment and mitigating plans
- QA/Engineering: for audit evidence and implementation details

### Decision Authority
Can require additional controls or testing to meet compliance; escalates to Sponsor if remediation impacts schedule/budget.

### Typical Deliverables
Compliance checklist, audit evidence, remediation plans

### Hand-off Acceptance Criteria
Compliance checks completed and evidence attached to milestone artifacts.

---

## Quality Assurance Coordinator

### Role Summary
Owns cross-team QA coordination, acceptance criteria, and quality metrics for project deliverables.

### Responsibilities
- Define acceptance criteria templates and ensure they are attached to deliverables
- Coordinate cross-team testing activities and test sign-offs
- Track quality metrics and report status to Project Manager and Stakeholders
- Maintain regression and test artifact registry if applicable

### Interactions
- Product Owner: to align acceptance criteria and acceptance tests
- Engineers & Testers: to coordinate execution and defect triage
- Compliance Lead: for compliance-related tests

### Decision Authority
Can block acceptance of a deliverable if acceptance criteria are not met; escalates to Project Manager for dispute resolution.

### Typical Deliverables
Acceptance criteria artifacts, test plans, quality dashboards

### Hand-off Acceptance Criteria
Acceptance criteria passed, with evidence in test reports and no open critical defects.

---

## RACI Matrix for Core Lifecycle Activities

| Activity | Project Manager | Product Manager | Developer | Change Manager | Stakeholder Liaison | Compliance Lead | QA Coordinator |
|----------|----------------|-----------------|-----------|----------------|---------------------|-----------------|----------------|
| Initiation | A | R | C | I | C | C | I |
| Planning | A | R | C | I | I | C | C |
| Change Control | C | C | I | A/R | I | C | C |
| Execution | A | C | R | I | I | I | C |
| QA/Acceptance | C | C | I | I | I | C | A/R |
| Release | A | I | C | C | I | C | C |

**Legend:**
- R = Responsible (Does the work)
- A = Accountable (Ultimately answerable)
- C = Consulted (Input requested)
- I = Informed (Kept updated)

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

