# OctoAcme Project Management Documentation

## Overview

OctoAcme follows a structured, iterative approach to project management that prioritizes customer value, clear ownership, and data-informed decisions. Our processes are designed to be lightweight yet comprehensive, enabling cross-functional teams to deliver reliably and maintain psychological safety throughout the project lifecycle.

## Core Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## OctoAcme Project Management Approach

OctoAcme operates on a customer-first, iterative delivery model with clear ownership and data-driven decision-making. The organization structures all cross-functional projects through five defined phases: Initiation (problem statement and stakeholder alignment), Planning (scope and resource definition), Execution (build and test), Release (deployment and verification), and Close & Retrospective (learning capture). This end-to-end approach ensures that projects begin with validated business needs and success metrics, move through disciplined planning with prioritized backlogs and defined milestones, and conclude with structured retrospectives that feed continuous improvement.

The OctoAcme model defines three primary roles—Project Manager (PM), Product Manager (PdM), and Developers—supported by QA/Testing specialists and stakeholders. The PM coordinates delivery, schedules, risk, and communications; the PdM defines outcomes and prioritizes the backlog; and developers implement features collaboratively with design and quality focus. Communication occurs through weekly PM-PdM syncs, twice-weekly delivery standups, monthly stakeholder updates, and a three-level escalation path (team → PM → Product Lead → Sponsor) for blocker resolution.

During execution, teams work from project boards organized into columns (Backlog, Ready, In Progress, In Review, QA, Done) with daily standups tracking progress and blockers. Quality standards include unit and integration tests for new logic, end-to-end smoke tests for critical flows, security scanning in CI, and manual QA for feature acceptance. Pull requests follow strict discipline: small PRs (≤400 lines), issue links and acceptance criteria in descriptions, automated testing and linting before review, and at least one approval before merge. OctoAcme standardizes releases through pre-release requirements, automated deployment pipelines, and post-deploy verification. When releases cause issues, the organization triggers incident response and conducts blameless retrospectives to capture learning and drive continuous improvement.

## Project Management Process Lifecycle

OctoAcme projects follow five key phases:

1. **Initiation** → **Planning** → **Execution** → **Release** → **Close & Retrospective**

## Process Documentation

### Getting Started

- **[Project Management Overview](octoacme-project-management-overview.md)** — Start here for a concise introduction to OctoAcme roles, artifacts, and high-level lifecycle

### By Project Phase

- **[Project Initiation Guide](octoacme-project-initiation.md)** — Define business need, align stakeholders, and prepare to move into planning
- **[Project Planning](octoacme-project-planning.md)** — Break work into shippable increments, define dependencies, and create your backlog
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Manage day-to-day delivery, track progress, and escalate blockers
- **[Release & Deployment Guide](octoacme-release-and-deployment.md)** — Standardize release processes and reduce deployment risk
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and drive improvements

### Cross-cutting Concerns

- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — Identify, manage, and communicate risks throughout the project
- **[Roles & Personas](octoacme-roles-and-personas.md)** — Understand key roles (PMs, developers, stakeholders) and responsibilities

## Quick Start by Role

### Project Managers
Start with [Project Initiation Guide](octoacme-project-initiation.md), then [Project Planning](octoacme-project-planning.md). Reference [Execution & Tracking](octoacme-execution-and-tracking.md) for day-to-day management and [Risk Management & Communication](octoacme-risks-and-communication.md) for escalation paths.

### Developers
Review [Execution & Tracking](octoacme-execution-and-tracking.md) for workflow and quality standards, and [Roles & Personas](octoacme-roles-and-personas.md) to understand responsibilities and communication expectations.

### Product Managers
See [Project Management Overview](octoacme-project-management-overview.md) and [Project Initiation Guide](octoacme-project-initiation.md) for setting up projects, then reference [Risk Management & Communication](octoacme-risks-and-communication.md) for stakeholder engagement.

### Stakeholders
Check [Risk Management & Communication](octoacme-risks-and-communication.md) for status update templates and escalation paths, and [Release & Deployment Guide](octoacme-release-and-deployment.md) for release communication expectations.

## Key Artifacts

- Project Charter / One-pager
- Roadmap and Release Plan
- Sprint/Iteration Backlog
- Acceptance Criteria & Definition of Done
- Risk Register
- Retrospective notes and action items

## Communication Cadence

- Weekly sync between PM + PdM
- Twice-weekly standups for delivery team (or as agreed)
- Monthly stakeholder updates
- Ad-hoc escalations as needed

## How to Use These Docs

- Keep the Project Charter updated in the project repo
- Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context
- Refer to the issue template [Add Content to Project Management Process Docs](.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) when proposing updates or new content
