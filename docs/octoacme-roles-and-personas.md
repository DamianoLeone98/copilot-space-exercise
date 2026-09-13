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

## Delivery Leads

### Role Summary
Delivery Leads coordinate day-to-day execution across the delivery team. They focus on flow, dependency management, and blocker removal so planned work can move steadily from kickoff to release.

### Responsibilities
- Track progress against sprint or milestone commitments
- Surface blockers, risks, and dependency conflicts early
- Coordinate day-to-day delivery decisions with PM and technical contributors
- Help keep work scoped into clear, deliverable increments
- Support escalation when delivery issues threaten timelines or outcomes

### Goals
- Maintain predictable delivery flow
- Reduce delays caused by unresolved blockers or handoff gaps
- Keep teams aligned on near-term priorities and commitments

### Typical Communication
- Daily standups and delivery check-ins
- Dependency reviews with PM and technical leads
- Progress updates in project boards and team channels

### How They Interact with Existing Roles
- Partner with Project Managers on schedule health, risk escalation, and delivery reporting
- Align with Product Managers on scope trade-offs and sequencing when priorities shift
- Work closely with Developers to remove blockers and clarify day-to-day execution needs
- Coordinate with QA/Testing on validation timing so testing keeps pace with delivery
- Provide concise progress signals to Stakeholders when commitments or dates change

---

## QA Leads / Test Leads

### Role Summary
QA Leads or Test Leads define the validation approach for a project and coordinate quality activities across the team. They help ensure features meet acceptance criteria, quality expectations, and release readiness standards.

### Responsibilities
- Define test strategy, coverage expectations, and validation checkpoints
- Coordinate functional, regression, and smoke testing activities
- Clarify acceptance criteria with PM, Product, and Developers
- Track quality risks, defect trends, and unresolved test gaps
- Recommend go/no-go input based on testing outcomes and known issues

### Goals
- Increase confidence in feature quality and release readiness
- Catch defects early and reduce production regressions
- Keep quality expectations consistent across the delivery lifecycle

### Typical Communication
- Test planning sessions and bug triage
- Validation status updates during execution and release prep
- Documentation of test coverage, risks, and sign-off recommendations

### How They Interact with Existing Roles
- Work with Project Managers to plan test windows, defect follow-up, and readiness checkpoints
- Collaborate with Product Managers to confirm acceptance criteria and customer-impact priorities
- Partner with Developers on testability, defect resolution, and regression prevention
- Coordinate directly with QA/Testing contributors on execution priorities and coverage gaps
- Share release quality status and residual risk with Stakeholders before launch decisions

---

## Release Managers

### Role Summary
Release Managers coordinate release readiness, deployment planning, and cross-functional go-live activities. They help ensure releases are prepared, communicated, and executed with clear ownership and rollback awareness.

### Responsibilities
- Maintain release plans, readiness checklists, and deployment timelines
- Confirm dependencies, approvals, and communication plans before release
- Coordinate release rehearsals, cutover steps, and rollback preparation
- Track release risks and unresolved items that affect launch confidence
- Facilitate go/no-go decisions with the appropriate owners

### Goals
- Deliver smooth, low-risk releases
- Improve coordination across deployment, validation, and communications
- Reduce confusion during launch and post-release verification

### Typical Communication
- Release readiness reviews and deployment checklists
- Go/no-go meetings and launch coordination messages
- Post-release summaries and follow-up actions

### How They Interact with Existing Roles
- Coordinate with Project Managers on milestone readiness, approvals, and escalation paths
- Align with Product Managers on release scope, business timing, and launch expectations
- Work with Developers on deployment sequencing, rollback plans, and post-release support
- Depend on QA/Testing for test results, smoke-test readiness, and quality sign-off input
- Keep Stakeholders informed on release timing, status, and any production-impacting decisions

---

## Stakeholder Champions / Business Owners

### Role Summary
Stakeholder Champions or Business Owners represent business priorities and help ensure delivered outcomes remain aligned with customer, operational, or organizational needs. They provide timely decisions, validation, and feedback throughout the project lifecycle.

### Responsibilities
- Clarify business goals, constraints, and success measures
- Validate that proposed scope and delivered outcomes meet business needs
- Provide timely feedback on priorities, trade-offs, and open decisions
- Help resolve ambiguity when multiple stakeholder perspectives exist
- Support adoption, communication, and outcome measurement after release

### Goals
- Keep delivery aligned with real business outcomes
- Improve decision speed when priorities or trade-offs are unclear
- Strengthen accountability for value realization after launch

### Typical Communication
- Planning workshops, roadmap reviews, and milestone demos
- Business decision logs and feedback summaries
- Release communications and post-launch outcome reviews

### How They Interact with Existing Roles
- Provide Project Managers with timely decisions and escalation input when scope or dependencies shift
- Work with Product Managers to refine priorities, value hypotheses, and acceptance expectations
- Join Developers and QA/Testing during demos or clarifications when business context affects implementation or validation
- Represent broader Stakeholders by consolidating feedback into clearer direction for the team

---

## Technical Leads / Architects

### Role Summary
Technical Leads or Architects guide the technical approach for a project. They help the team make sound engineering decisions, manage architectural risks, and align implementation choices with delivery constraints.

### Responsibilities
- Define or review the high-level technical approach for major work
- Identify architectural risks, technical dependencies, and key trade-offs
- Support estimation and feasibility discussions during planning
- Guide design quality, non-functional requirements, and maintainability concerns
- Mentor Developers and help unblock complex technical decisions

### Goals
- Improve technical clarity and feasibility early in the project
- Reduce rework caused by poor architectural choices
- Balance delivery speed with long-term maintainability and reliability

### Typical Communication
- Technical design reviews and architecture discussions
- Planning sessions for estimates, dependencies, and trade-offs
- Ongoing engineering guidance through reviews and implementation check-ins

### How They Interact with Existing Roles
- Partner with Project Managers on technical dependency visibility, sequencing, and risk mitigation
- Advise Product Managers on feasibility, trade-offs, and impact of scope decisions
- Support Developers with implementation guidance, standards, and complex problem solving
- Coordinate with QA/Testing on non-functional quality concerns such as performance, reliability, and integration risk
- Help Stakeholders understand technical constraints that influence timing, scope, or release risk

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
