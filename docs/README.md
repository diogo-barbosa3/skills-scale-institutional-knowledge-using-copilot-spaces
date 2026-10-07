# OctoAcme Project Management Documentation

## Overview

This directory contains the complete OctoAcme project management process documentation. OctoAcme follows a customer-first, iterative delivery approach with clear ownership, data-informed decisions, and psychological safety.

## Core Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has named roles and accountability
- **Data-informed**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Project Management Lifecycle

OctoAcme projects follow these phases:

1. **Initiation** - Validate business need, align stakeholders, and create a lightweight plan
2. **Planning** - Break work into shippable increments, identify dependencies and risks
3. **Execution** - Build, test, review, and iterate with daily standups and weekly syncs
4. **Release** - Deploy to production with reduced risk and improved observability
5. **Retrospective** - Capture learnings and convert them into actionable improvements

## Core Processes Summary

### Project Initiation
Projects begin with stakeholder alignment and a lightweight plan. The initiation phase validates business need, confirms measurable outcomes, and identifies key stakeholders. Deliverables include a Project One-pager, stakeholder list, timeline, and initial risk assessment.

### Project Planning
Once initiated, projects are turned into actionable plans through kickoff meetings, backlog prioritization, and dependency mapping. The planning phase breaks work into shippable increments, defines acceptance criteria, and establishes a release timeline with clear milestones.

### Execution & Tracking
Day-to-day execution follows team rhythms: daily standups (15 min), weekly delivery syncs, and demos at sprint/milestone ends. Teams use project boards for workflow management, maintain PR quality standards (≤400 lines), and track velocity and burndown metrics. Blockers are escalated through defined tiers: team, PM/Product Lead, then sponsor.

### Release & Deployment
Releases are standardized to reduce risk and improve observability. Pre-release requirements include passing CI, security scans, drafted release notes, and documented rollback plans. Deployment follows a checklist with staging verification and post-deploy smoke tests.

### Risk Management & Communication
Risks are captured in a register with ID, description, impact, likelihood, mitigation plan, and owner. Risks are reviewed at weekly syncs and monitored throughout execution. Stakeholder communication follows a regular cadence with weekly status updates, incident communication protocols, and defined escalation paths.

### Retrospective & Continuous Improvement
After sprints, releases, or milestones, teams conduct retrospectives to capture learnings. Sessions focus on what went well, what could improve, and actionable items with clear owners and due dates. Improvements are tracked and reviewed in weekly PM syncs.

## Documentation Index

### Getting Started
- **[Project Management Overview](./octoacme-project-management-overview.md)** - High-level introduction to OctoAcme's approach, core roles, and key artifacts

### Process Guides
- **[Project Initiation](./octoacme-project-initiation.md)** - How to validate and authorize new work, align stakeholders, and create initial plans
- **[Project Planning](./octoacme-project-planning.md)** - How to turn approved initiatives into actionable plans and backlogs
- **[Execution & Tracking](./octoacme-execution-and-tracking.md)** - How to manage day-to-day execution and track progress toward milestones
- **[Release & Deployment](./octoacme-release-and-deployment.md)** - How to standardize releases and reduce deployment risk
- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** - How to identify, manage, and communicate risks and dependencies
- **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** - How to capture learnings and improve processes

### Reference
- **[Roles & Personas](./octoacme-roles-and-personas.md)** - Definitions of key roles (Developers, Product Managers, Project Managers) used across OctoAcme projects

## How to Use These Docs

- Keep the Project Charter updated in your project repo
- Add process-specific docs to `.copilot/` if you want Copilot Spaces to use them as context
- Refer to the appropriate process guide based on your project phase
- Use templates and checklists provided in each guide to ensure consistency
- Update the risk register and status reports according to cadences defined in each process

## Communication Cadence

- Weekly sync between PM and Product Manager
- Twice-weekly standups for delivery team (or as agreed)
- Monthly stakeholder updates
- Ad-hoc escalations as needed
