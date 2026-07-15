# OctoAcme Project Management Documentation

Welcome to the OctoAcme Project Management Docs. This directory contains standardized processes, templates, and guidance for running projects at OctoAcme.

## Our Approach

OctoAcme follows a structured project lifecycle centered on clear ownership, iterative delivery, and data-informed decisions. We believe in psychological safety, customer focus, and continuous improvement.

## Core Principles
- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager and Product Lead
- **Data-informed**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## OctoAcme Project Management Overview

### Lifecycle & Workflow Structure

OctoAcme operates on a structured five-phase project lifecycle designed to deliver customer value through iterative, manageable increments. Projects begin with **Initiation**, where business needs are validated and stakeholders are aligned around a lightweight Project One-pager that defines the problem, goals, success metrics, and initial timeline. This phase includes a decision gate before moving to **Planning**, where the approved initiative is broken down into shippable increments with prioritized backlogs, acceptance criteria, and a Definition of Done. During the **Execution & Tracking** phase, teams follow daily standups, weekly delivery syncs, and use GitHub Projects boards organized in columns (Backlog, Ready, In Progress, In Review, QA, Done). Pull requests are kept small (≤400 lines when possible), require at least one approval before merging, and must pass automated tests and security scanning. The **Release & Deployment** phase includes pre-release requirements such as passing CI, documented rollback plans, and smoke tests in staging before production deployment. Finally, teams conduct **Retrospectives** after each sprint, release, or milestone to capture learnings and convert them into actionable improvements tracked with clear owners and due dates.

### Roles, Responsibilities & Communication Cadence

OctoAcme defines four core roles with clear ownership: **Project Managers** coordinate delivery activities, manage risks, and maintain project documentation and stakeholder communications; **Product Managers** define what should be built by prioritizing the backlog and measuring outcomes; **Developers** implement features, write tests, and identify technical risks; and **QA/Testing** validates quality and acceptance criteria. This structure ensures psychological safety, customer-first decisions, and data-informed prioritization. The communication cadence includes daily standups (15 minutes, focused on progress and blockers), weekly delivery syncs between the PM and Product Lead, twice-weekly team standups, monthly stakeholder updates, and ad-hoc escalations as needed. A single source of truth—maintained in the project repository—ensures all stakeholders have access to the current status, risks, and decisions.

### Quality Assurance & Risk Management

Quality is embedded throughout the OctoAcme process through multiple layers: unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows before release, security scanning in CI, and manual QA for feature acceptance when needed. The **Risk Register** captures identified risks with ID, description, impact, probability, owner, and mitigation plan, reviewed weekly during syncs. Escalation follows a three-level path: Level 1 (team-level triage in standups), Level 2 (PM escalates to Product Lead and dependent teams), and Level 3 (sponsor-level escalation for business-impacting issues). This approach, grounded in principles of clear ownership, iterative delivery, and data-informed decisions, enables OctoAcme teams to minimize unplanned work, reduce cycle time from idea to production, and maintain transparency and alignment across all stakeholders and delivery phases.

## Key Roles

- **Project Manager (PM)**: Coordinates delivery, schedules, risks, and communications
- **Product Manager (PdM)**: Defines outcomes, prioritizes the backlog, and measures success
- **Developers**: Implement features and collaborate on design
- **QA/Testing**: Validates quality and acceptance criteria

## Process Documentation

Our project lifecycle is divided into key phases. Start here based on where your project is:

### Phase 1: Initiation
📖 [Project Initiation Guide](octoacme-project-initiation.md)

Define the initial steps to validate and authorize work, align stakeholders, and create a lightweight plan.

### Phase 2: Planning
📖 [Project Planning](octoacme-project-planning.md)

Turn an approved initiative into an actionable plan and backlog for delivery.

### Phase 3: Execution & Tracking
📖 [Execution & Tracking](octoacme-execution-and-tracking.md)

Guidance for managing day-to-day execution and tracking progress toward project milestones.

### Phase 4: Release & Deployment
📖 [Release & Deployment Guide](octoacme-release-and-deployment.md)

Standardize how OctoAcme releases features to production to reduce risk and improve observability.

### Phase 5: Retrospective & Improvement
📖 [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)

Capture learnings and convert them into actionable improvements.

## Cross-Cutting Topics

📖 [Risk Management & Communication](octoacme-risks-and-communication.md)

Identify, manage, and communicate risks and dependencies throughout your project.

📖 [Roles & Personas](octoacme-roles-and-personas.md)

Detailed descriptions of typical roles and responsibilities in OctoAcme projects.

📖 [Project Management Overview](octoacme-project-management-overview.md)

Concise introduction to how OctoAcme runs projects, roles, and key artifacts.

## Quick Start

**Starting a new project?** → Begin with [Project Initiation Guide](octoacme-project-initiation.md)

**Need to plan upcoming work?** → Check out [Project Planning](octoacme-project-planning.md)

**Executing and need guidance?** → See [Execution & Tracking](octoacme-execution-and-tracking.md)

**Preparing for release?** → Review [Release & Deployment Guide](octoacme-release-and-deployment.md)

**Completed a phase or project?** → Schedule a [Retrospective](octoacme-retrospective-and-continuous-improvement.md)

## Need Help?

For questions about OctoAcme project management processes, consult the appropriate process doc above or reach out to your Project Manager.
