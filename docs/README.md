# OctoAcme Project Management Documentation

## Overview

OctoAcme follows an iterative, customer-first approach to project delivery. Our process is designed around small, testable increments with clear ownership and continuous feedback loops. Each project moves through a structured lifecycle—from initiation and planning through execution, release, and retrospective—ensuring teams deliver value while maintaining quality and psychological safety.

Our workflows center on pull request-driven development with automated quality gates. Teams work in sprints with daily standups and weekly syncs, using project boards to track work from backlog through QA to done. Pull requests are kept small (<=400 lines when possible), linked to issues, and require CI checks and peer review before merging. This approach ensures transparency, reduces risk, and enables rapid iteration.

OctoAcme defines explicit roles and responsibilities for each project. Project Managers coordinate delivery, schedules, and risk management. Product Managers define outcomes, prioritize the backlog, and measure success. Developers implement features with strong testing and documentation practices. QA validates acceptance criteria and quality standards. This role clarity ensures accountability while fostering cross-functional collaboration.

Communication follows both asynchronous and synchronous patterns. Teams maintain regular cadences including daily standups, weekly PM-PdM syncs, and monthly stakeholder updates. Risk registers are updated weekly, and status reports follow consistent templates. Ad-hoc escalations happen through defined paths from team to PM to product lead to sponsor. All retrospectives capture learnings and convert them into tracked action items, ensuring continuous improvement.

## Documentation

This directory contains comprehensive guides for each phase of the OctoAcme project lifecycle:

- [OctoAcme Project Management Overview](octoacme-project-management-overview.md) - Core principles, roles, artifacts, and lifecycle
- [OctoAcme Project Initiation](octoacme-project-initiation.md) - Starting a new project: problem statements, stakeholders, and timelines
- [OctoAcme Project Planning](octoacme-project-planning.md) - Scope definition, resource allocation, milestones, and dependencies
- [OctoAcme Execution and Tracking](octoacme-execution-and-tracking.md) - Day-to-day workflows, PR processes, quality gates, and team rhythm
- [OctoAcme Risks and Communication](octoacme-risks-and-communication.md) - Risk management, stakeholder communication, and escalation paths
- [OctoAcme Release and Deployment](octoacme-release-and-deployment.md) - Release planning, deployment processes, and verification
- [OctoAcme Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) - Learning capture and improvement tracking
- [OctoAcme Roles and Personas](octoacme-roles-and-personas.md) - Detailed role definitions and responsibilities

## How to Use These Docs

**For Project Teams:**
- Keep your Project Charter and process artifacts updated in your project repository
- Reference these process docs when setting up new projects or onboarding team members
- Adapt templates and workflows to your specific project needs while maintaining core principles

**For Copilot Spaces:**
- Add project-specific process docs into the `.copilot/` directory if you want GitHub Copilot Spaces to use them as context
- This allows Copilot to provide role-specific guidance and process-aware suggestions aligned with OctoAcme practices

**For Continuous Improvement:**
- Use retrospectives to identify gaps or improvements to these processes
- Submit updates via pull requests to keep documentation current and useful

## Acceptance Criteria

- [ ] Content aligns with existing OctoAcme process documentation
- [ ] Documentation update improves clarity and accessibility
- [ ] Reviewed with stakeholders (if needed)
