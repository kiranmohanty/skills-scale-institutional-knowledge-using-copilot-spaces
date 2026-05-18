# OctoAcme Project Management Documentation

## Overview

OctoAcme uses a structured, iterative project management framework grounded in customer-first principles and clear ownership. The organization operates through a well-defined lifecycle spanning five phases: **Initiation** (validating business need and stakeholder alignment), **Planning** (breaking work into shippable increments with acceptance criteria), **Execution** (day-to-day delivery with frequent feedback loops), **Release** (standardized deployment with risk mitigation), and **Close & Retrospective** (capturing learnings and continuous improvement). This approach emphasizes delivering small, testable increments rather than large, monolithic releases, enabling rapid iteration and risk reduction.

The framework relies on clear role definition and cross-functional collaboration. Three core personas drive delivery: **Project Managers** coordinate schedules, manage risks, and facilitate communication; **Product Managers** define outcomes, prioritize the backlog, and measure success; and **Developers** (supported by QA teams) implement features while ensuring quality and testability. Communication is structured through regular cadences—daily standups (15 minutes), weekly PM-PdM syncs, twice-weekly delivery team standups, and monthly stakeholder updates—creating transparency and enabling early escalation of blockers. The organization uses GitHub Projects for work visualization (columns: Backlog, Ready, In Progress, In Review, QA, Done) and maintains a Risk Register to track dependencies and mitigation strategies.

Quality and delivery reliability are embedded throughout the process via a comprehensive **Definition of Done**, automated CI/CD pipelines (tests, linting, security scans), small pull requests (≤400 lines), mandatory code review approvals, and multi-stage testing (unit, integration, end-to-end smoke tests). Release management is risk-aware, requiring acceptance criteria validation, passing security scans, drafted release notes, and a documented rollback plan before deployment. Post-deployment verification and stakeholder announcement ensure observability. If issues arise, the organization triggers incident response and conducts blameless retrospectives to prevent recurrence.

Finally, OctoAcme institutionalizes continuous improvement through regular retrospectives (after each sprint, release, or milestone), structured feedback collection, and disciplined tracking of action items with clear owners and due dates. Success metrics are defined upfront in the Project One-pager and monitored via dashboards for key signals (errors, latency, usage). This systematic approach—combining lightweight documentation, frequent collaboration, quality guardrails, and a learning culture—enables OctoAcme teams to deliver reliable increments while maintaining psychological safety and reducing single-person dependency risks.

## Table of Contents

1. [Project Lifecycle](#project-lifecycle)
2. [Core Roles](#core-roles)
3. [Documentation Index](#documentation-index)
4. [Communication Cadence](#communication-cadence)

## Project Lifecycle

OctoAcme projects follow a structured five-phase lifecycle:

| Phase | Purpose | Key Artifacts |
|-------|---------|---------------|
| **Initiation** | Validate business need, align stakeholders, confirm feasibility | Project One-pager, Stakeholder list, Risk list |
| **Planning** | Break work into shippable increments, define DoD, identify dependencies | Backlog, Release plan, Risk Register, Test plan |
| **Execution** | Build, test, review, iterate with frequent feedback loops | PRs, Project board, Daily standups |
| **Release** | Deploy to production with risk mitigation and observability | Release notes, Deployment checklist, Rollback plan |
| **Close & Retrospective** | Capture learnings and convert to actionable improvements | Retrospective notes, Action items |

## Core Roles

- **Project Manager (PM)**: Coordinates delivery, manages schedules, risks, and communications. Ensures transparency and alignment across stakeholders.
- **Product Manager (PdM)**: Defines outcomes, prioritizes the backlog, and measures success. Owns the product vision and makes data-driven decisions.
- **Developers**: Design, build, test, and deliver software components. Collaborate on design and ensure quality standards are met.
- **QA/Testing**: Validate quality and acceptance criteria. Conduct manual QA when needed.
- **Stakeholders**: Provide inputs, approvals, and strategic guidance aligned with business objectives.

## Documentation Index

The following documents provide detailed guidance for each phase and aspect of OctoAcme project management:

### Phase-Specific Guides

- **[OctoAcme Project Management Overview](octoacme-project-management-overview.md)**  
  Framework, principles, core roles, key artifacts, and the project lifecycle at a glance.

- **[Project Initiation Guide](octoacme-project-initiation.md)**  
  Steps to validate a new project idea, align stakeholders, and create a lightweight plan. Use this when exploring a new feature proposal or initiative.

- **[Project Planning](octoacme-project-planning.md)**  
  Turn an approved initiative into an actionable plan and backlog. Covers kickoff, backlog creation, estimation, and dependency management.

- **[Execution & Tracking](octoacme-execution-and-tracking.md)**  
  Guidance for managing day-to-day execution and tracking progress. Includes team rhythm, workflows, quality standards, and escalation procedures.

- **[Release & Deployment Guide](octoacme-release-and-deployment.md)**  
  Standardized process for releasing features to production. Covers pre-release requirements, deployment checklist, and rollback procedures.

- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)**  
  How to capture learnings and convert them into actionable improvements. Includes retrospective structure and action item tracking.

### Supporting Guides

- **[Risk Management & Communication](octoacme-risks-and-communication.md)**  
  How to identify, manage, and communicate risks and dependencies. Includes Risk Register template, escalation paths, and communication templates.

- **[Roles and Personas](octoacme-roles-and-personas.md)**  
  Detailed definitions of typical roles and responsibilities used across OctoAcme project docs.

## Communication Cadence

OctoAcme maintains a structured communication rhythm to ensure alignment and enable rapid escalation:

| Frequency | Forum | Purpose | Participants |
|-----------|-------|---------|--------------|
| Daily | Standup (15 min) | Progress updates, blockers, dependencies | Delivery team |
| Weekly | PM-PdM Sync | Strategic alignment, prioritization, metrics | PM, PdM |
| Twice-weekly | Delivery Standup | Progress, QA, and technical blockers | Delivery team |
| Monthly | Stakeholder Update | High-level progress, risks, decisions | Stakeholders, PM, PdM |
| Ad-hoc | Escalation | Critical blockers and incident response | Relevant escalation path |

## Quick Start

**New to OctoAcme?** Start here:
1. Read the [Project Management Overview](octoacme-project-management-overview.md) to understand the framework.
2. Review the [Roles and Personas](octoacme-roles-and-personas.md) to understand your role and how teams interact.
3. For your current project phase, consult the phase-specific guide (Initiation, Planning, Execution, Release, Retrospective).

**Scaling institutional knowledge?** This documentation is version-controlled in the repository and can be updated through the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template.
