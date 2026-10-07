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

## QA / Testing Lead

### Role Summary
QA / Testing Leads own quality assurance strategy, test planning, and release readiness. They partner with Developers and Product Managers to validate features against acceptance criteria and shipping standards.

### Responsibilities
- Define test strategy, test plans, and quality gates for features and releases
- Create and maintain automated and manual test coverage for critical user flows
- Validate acceptance criteria and provide go / no-go signals for release readiness
- Identify, triage, and track defects and regression risks
- Collaborate with engineering to improve testability and quality practices

### Goals
- Reduce production defects and release risk
- Improve confidence in quality before deployment
- Align testing activities to product goals and delivery milestones

### Typical Communication
- QA planning and release readiness reviews
- Defect triage and bug severity discussions
- Weekly status updates with PMs and engineering leads
- Pre-release sign-off and post-release quality checks

### Interaction with existing roles
- Works closely with Developers to define testability, automation coverage, and defect ownership.
- Aligns with Product Managers on acceptance criteria, user impact, and release quality thresholds.
- Supports Project Managers by flagging delivery risks, known issues, and readiness milestones.

---

## Technical Lead / Architect

### Role Summary
Technical Leads define architecture direction, guide design decisions, and reduce technical risk across the project. They help the team make scalable, maintainable choices while balancing speed and quality.

### Responsibilities
- Define and evolve the technical approach for features and platform changes
- Review designs, architecture choices, and technical trade-offs
- Identify dependencies, pinch points, and system-level risks early
- Mentor Developers on standards, patterns, and technical quality
- Balance short-term delivery needs with long-term maintainability

### Goals
- Deliver robust and scalable solutions
- Reduce technical debt and architectural drift
- Clarify technical decisions for the team and stakeholders

### Typical Communication
- Architecture reviews and design discussions
- Technical estimation and dependency planning
- Code review guidance and mentoring conversations
- Weekly syncs with PMs and cross-functional stakeholders on technical risks

### Interaction with existing roles
- Partners with Developers to ensure implementation aligns with architecture and quality standards.
- Works with Product Managers to translate business needs into feasible technical scope and sequencing.
- Helps Project Managers understand dependencies, effort estimates, and cross-team risk exposure.

---

## Scrum Master / Agile Coach

### Role Summary
Scrum Masters or Agile Coaches help the team work effectively, remove friction, and improve delivery flow. They facilitate rituals and coach the team on sustainable, high-performing ways of working.

### Responsibilities
- Facilitate sprint planning, standups, backlog refinement, and retrospectives
- Identify blockers, bottlenecks, and process issues that slow delivery
- Coach the team on agile practices, collaboration, and continuous improvement
- Help maintain healthy team dynamics and clear accountability
- Support the team in converting feedback into improvements

### Goals
- Improve team flow, predictability, and delivery consistency
- Reduce waste and unnecessary friction in the delivery process
- Strengthen collaboration across project roles and dependencies

### Typical Communication
- Team ceremonies and cross-team alignment meetings
- Retrospectives and process improvement discussions
- Weekly delivery check-ins with PMs and stakeholders
- Coaching sessions focused on team practices and communication

### Interaction with existing roles
- Works with Developers and Product Managers to keep priorities, planning, and delivery cadence aligned.
- Supports Project Managers by improving meeting quality, removing blockers, and strengthening execution rhythm.
- Helps Stakeholders understand team capacity, delivery constraints, and the value of iterative progress.

---

## Design / UX Lead

### Role Summary
Design / UX Leads shape the user experience and ensure that product decisions remain customer-centered, usable, and consistent with the brand or design system.

### Responsibilities
- Translate user needs and business goals into UX flows and design decisions
- Define UX patterns, accessibility expectations, and visual consistency
- Partner with Product Managers to validate assumptions through user research and feedback
- Collaborate with Developers to ensure designs are feasible and testable
- Support release quality by reviewing usability and edge-case experiences

### Goals
- Improve product usability, clarity, and customer satisfaction
- Keep design work aligned with user needs and product strategy
- Ensure accessibility and consistency across experiences

### Typical Communication
- Discovery and UX review sessions
- Design critiques and usability testing feedback loops
- Product planning conversations and release validation discussions
- Collaboration with engineering on implementation questions and edge cases

### Interaction with existing roles
- Works with Product Managers to prioritize customer experience goals and validate problem statements.
- Partners with Developers to turn UX flows into practical, maintainable implementation decisions.
- Gives Project Managers and Stakeholders a clear view of user impact and any design-related delivery dependencies.

---

## DevOps / Infrastructure Engineer

### Role Summary
DevOps / Infrastructure Engineers ensure that systems are reliable, observable, and deployable. They support the delivery pipeline, operational health, and environment readiness needed for stable releases.

### Responsibilities
- Manage CI/CD pipelines, deployment automation, and environment configuration
- Monitor system health, performance, and reliability signals
- Support incident response, recovery, and operational readiness
- Maintain infrastructure standards, security baselines, and environment consistency
- Enable safe, repeatable release processes and rollback planning

### Goals
- Improve deployment reliability and system observability
- Reduce operational risk and recovery time
- Create scalable infrastructure that supports product delivery

### Typical Communication
- Release planning and deployment check-ins
- Incident response coordination and operational reviews
- Weekly engineering and platform updates
- Collaboration with security and development teams on configuration and risk controls

### Interaction with existing roles
- Works with Developers to ensure environments, tooling, and deployment workflows support delivery goals.
- Partners with Project Managers to understand release windows, dependencies, and operational risk.
- Coordinates with Security Leads to ensure infrastructure and deployment controls align with compliance and best practices.

---

## Security Lead

### Role Summary
Security Leads protect the product, data, and users by embedding security practices into planning, implementation, and release activities.

### Responsibilities
- Review risks, threats, and compliance considerations across the project
- Define security requirements, controls, and validation steps
- Partner with engineering to assess vulnerabilities and remediate issues
- Support incident response and security escalation processes when needed
- Help the team balance speed with secure delivery practices

### Goals
- Reduce security and compliance risk
- Improve confidence in the product's resilience and data protections
- Embed security into normal delivery rather than treating it as a final gate

### Typical Communication
- Security review sessions and risk assessments
- Dependency and compliance discussions with engineering leads
- Release readiness checks for sensitive or critical changes
- Incident communication and follow-up actions when necessary

### Interaction with existing roles
- Works with Developers and Technical Leads to review design and implementation choices for security risk.
- Collaborates with Product Managers and Project Managers to ensure security requirements are reflected in scope, timelines, and release decisions.
- Coordinates with DevOps / Infrastructure Engineers to enforce secure deployment patterns and monitoring.

---

## Stakeholder / Sponsor

### Role Summary
Stakeholders and Sponsors represent business needs, provide strategic direction, and help unblock decision-making. They ensure the project stays aligned to organizational goals and value creation.

### Responsibilities
- Define business context, outcomes, and strategic priorities
- Approve scope, budget, and resource allocation where needed
- Provide guidance on stakeholder expectations and milestone decisions
- Help remove enterprise-level blockers and escalate decisions when necessary
- Participate in key project gates such as initiation, planning, and release approval

### Goals
- Ensure projects deliver measurable value and business impact
- Maintain alignment between project execution and organizational objectives
- Support timely, informed decisions at critical checkpoints

### Typical Communication
- Stakeholder updates and executive briefings
- Decision gates for scope, funding, and release readiness
- Cross-functional alignment meetings and escalation calls
- Roadmap reviews and business impact reporting

### Interaction with existing roles
- Works with Product Managers to validate priorities and success metrics.
- Engages with Project Managers to confirm timelines, key milestones, and resourcing.
- Supports Developers, QA, and delivery teams by clarifying business intent and helping resolve cross-functional challenges.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- These roles are designed to clarify accountability, support collaboration, and improve project outcomes across cross-functional teams.


