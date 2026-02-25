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

## UX Designer

### Role Summary
UX Designers ensure that interfaces and user flows are intuitive, accessible, and aligned with user needs. They bridge user research and product development to deliver experiences that meet both customer and business goals.

### Responsibilities
- Conduct user research, usability tests, and gather feedback
- Produce wireframes, mockups, and interactive prototypes
- Define and maintain design guidelines and accessibility standards
- Collaborate with Product Managers on feature definitions and acceptance criteria
- Partner with Developers to ensure designs are implemented correctly

### Goals
- Deliver user experiences that are intuitive, inclusive, and consistent
- Reduce usability issues caught late in the cycle
- Promote user-centered thinking across the team

### Typical Communication
- Design reviews and prototype walkthroughs with Product and Engineering
- Usability test reports shared with PM and Project Manager
- Design specs and annotated assets handed off to Developers

### Interaction with Other Roles
- Works closely with **Product Managers** to align designs with product vision
- Partners with **Developers** during implementation and review
- Coordinates with **QA Lead** on usability and acceptance validation

---

## QA Lead

### Role Summary
The QA Lead owns the quality strategy and ensures that releases meet acceptance criteria and quality standards. They coordinate testing activities across the team and surface quality metrics to inform decisions.

### Responsibilities
- Define and maintain the test strategy (unit, integration, end-to-end, regression)
- Plan and coordinate test execution across sprints and releases
- Report quality metrics (defect rates, coverage, test results)
- Validate that acceptance criteria are met before features are marked done
- Identify, track, and triage defects in collaboration with Developers

### Goals
- Prevent regressions and reduce defect escape rate to production
- Maintain comprehensive, automated test coverage
- Ensure the Definition of Done includes testability standards

### Typical Communication
- Test plans and quality reports shared with PM and Project Manager
- Daily standup participation for QA progress and blockers
- Release readiness sign-off communicated to Release Manager

### Interaction with Other Roles
- Works with **Developers** to establish testability requirements and triage bugs
- Coordinates with **Release Manager** for release readiness sign-off
- Aligns with **Product Managers** on acceptance criteria and edge cases
- Provides feedback to **UX Designer** on usability and accessibility testing

---

## Release Manager

### Role Summary
The Release Manager plans and coordinates all aspects of the release process to ensure safe, timely, and well-communicated deployments.

### Responsibilities
- Maintain the release calendar and communicate deployment windows to stakeholders
- Define and verify release readiness criteria before each deployment
- Coordinate go/no-go decisions with QA Lead, DevOps Engineer, and PM
- Draft and publish release notes and stakeholder announcements
- Manage rollback plans and incident communication when releases cause issues

### Goals
- Deliver releases on schedule with minimal disruption
- Ensure every release has a verified rollback plan
- Maintain clear communication between engineering, operations, and business stakeholders

### Typical Communication
- Release schedule updates to Project Manager and stakeholders
- Go/no-go decisions documented and shared with the delivery team
- Post-release summaries and incident retrospectives

### Interaction with Other Roles
- Partners with **DevOps Engineer** on deployment pipelines and environments
- Works with **QA Lead** to confirm release readiness
- Aligns with **Project Manager** on timeline and stakeholder communications
- Coordinates with **Product Manager** on release notes and feature announcements

---

## DevOps Engineer

### Role Summary
DevOps Engineers automate infrastructure, maintain CI/CD pipelines, and ensure that deployments are reliable, observable, and secure.

### Responsibilities
- Design, build, and maintain CI/CD pipelines and deployment automation
- Manage cloud infrastructure, environments, and configuration
- Monitor application and infrastructure performance; respond to alerts
- Enforce security, compliance, and backup policies in the pipeline
- Support Developers and Release Manager in troubleshooting environment and deployment issues

### Goals
- Reduce deployment lead time and increase release frequency
- Ensure high availability and fast incident recovery
- Automate repetitive operations to free up developer capacity

### Typical Communication
- Infrastructure change announcements and maintenance windows
- Incident alerts, postmortems, and runbooks
- Pipeline status and deployment reports shared with Release Manager and PM

### Interaction with Other Roles
- Partners with **Release Manager** on deployment automation and release coordination
- Enables **Developers** with reliable environments, tooling, and fast feedback loops
- Works with **QA Lead** to integrate automated tests into CI pipelines
- Reports infrastructure risks and incidents to **Project Manager**

---

## Business Analyst

### Role Summary
Business Analysts bridge the gap between business stakeholders and technical teams, translating needs into clear, actionable requirements.

### Responsibilities
- Elicit, document, and validate business and functional requirements
- Translate stakeholder needs into user stories and acceptance criteria
- Facilitate workshops and working sessions to clarify scope
- Validate that delivered features meet business objectives
- Maintain traceability between business requirements and delivered features

### Goals
- Ensure technical solutions address the underlying business problem
- Reduce re-work caused by unclear or missing requirements
- Provide a clear link between project scope and business value

### Typical Communication
- Requirements documents and user story write-ups shared with Product and Developers
- Workshop summaries and decision logs shared with Project Manager
- Validation reports confirming feature acceptance from the business perspective

### Interaction with Other Roles
- Works closely with **Product Managers** to refine the backlog and acceptance criteria
- Partners with **Project Manager** on scope management and change requests
- Collaborates with **Developers** to clarify ambiguous requirements during implementation
- Supports **QA Lead** with test case scenarios derived from business requirements

---

## Role Coverage Checklist

Use this checklist at the start of every new project to confirm that key roles are assigned and responsibilities are covered. Unassigned roles should be explicitly noted with a named DRI (Directly Responsible Individual) or marked as out-of-scope.

| Role | Assigned? | DRI / Notes |
|---|---|---|
| Project Manager | ☐ | |
| Product Manager | ☐ | |
| Developer(s) | ☐ | |
| UX Designer | ☐ | |
| QA Lead | ☐ | |
| Release Manager | ☐ | |
| DevOps Engineer | ☐ | |
| Business Analyst | ☐ | |

**Instructions:**
- Check each box once a named person or team is confirmed for the role.
- If a role is not required for this project, add "N/A — [reason]" in the Notes column.
- Review this table during kickoff and update it whenever team composition changes.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Addendum: Keeping this document current

This persona list reflects the roles most commonly seen in OctoAcme cross-functional delivery teams as of the last update. Team structures evolve — new specializations emerge, responsibilities shift, and tooling changes how roles interact. **Review and update this document at least once per quarter, or whenever a significant change in team composition or process is introduced.** Proposed updates should be submitted as a pull request and reviewed by the Project Management lead and at least one representative from affected teams.

