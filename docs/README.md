# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management documentation. This folder contains comprehensive guides for managing projects from initiation through closure.

## Overview

OctoAcme operates using a structured, lifecycle-based approach to project management that prioritizes customer value, iterative delivery, and clear ownership. Our methodology is organized around five core phases: **Initiation, Planning, Execution, Release, and Retrospective**. Each phase is supported by dedicated process documentation, role definitions, and communication templates to ensure consistency, reduce onboarding friction, and enable teams to deliver reliably while maintaining psychological safety.

### Key Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Quick Navigation

**Getting Started with a New Project?**
- Start with [Project Initiation Guide](./octoacme-project-initiation.md)

**Planning Your Delivery?**
- Review [Project Planning](./octoacme-project-planning.md)

**Currently Executing?**
- Reference [Execution & Tracking](./octoacme-execution-and-tracking.md)

**Ready to Release?**
- Follow [Release & Deployment Guide](./octoacme-release-and-deployment.md)

**Improving Your Process?**
- Learn from [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)

**Need to Understand Roles?**
- Review [OctoAcme Personas](./octoacme-roles-and-personas.md)

**Managing Risks & Communication?**
- Reference [Risk Management & Communication](./octoacme-risks-and-communication.md)

## All Documentation

### Core Guides

1. **[OctoAcme Project Management Overview](./octoacme-project-management-overview.md)**
   - High-level introduction to OctoAcme's approach, core roles, and lifecycle
   - Best for: New team members, executives seeking process context

2. **[Project Initiation Guide](./octoacme-project-initiation.md)**
   - Steps to validate, authorize, and align stakeholders on new work
   - Key deliverables: Project One-pager, stakeholder list, timeline, risk list
   - Best for: PMs and PdMs proposing new initiatives

3. **[Project Planning](./octoacme-project-planning.md)**
   - How to break work into shippable increments and create actionable plans
   - Key activities: Kickoff, backlog prioritization, risk & dependency mapping
   - Best for: Delivery teams preparing for execution

4. **[Execution & Tracking](./octoacme-execution-and-tracking.md)**
   - Day-to-day execution, team rhythm, quality standards, and blocker escalation
   - Key rhythms: Daily standups, weekly delivery syncs, demos/reviews
   - Best for: Development teams, QA, and PMs during active delivery

5. **[Release & Deployment Guide](./octoacme-release-and-deployment.md)**
   - Standardized process for releasing features to production
   - Key activities: Pre-release verification, deployment checklists, rollback planning
   - Best for: Release managers, DevOps, and deployment teams

6. **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)**
   - Capturing learnings and converting them into actionable improvements
   - Key activities: Sprint retrospectives, action item tracking
   - Best for: All team members, especially leads and PMs

### Supporting Documentation

7. **[OctoAcme Personas](./octoacme-roles-and-personas.md)**
   - Detailed role definitions and responsibilities for Project Managers, Product Managers, Developers, and QA specialists
   - Best for: Understanding role boundaries and communication expectations

8. **[Risk Management & Communication](./octoacme-risks-and-communication.md)**
   - Managing risks, dependencies, and stakeholder communication
   - Key artifacts: Risk register, communication templates, escalation paths
   - Best for: Project leads, product managers, and stakeholder coordinators

## How OctoAcme Manages Projects: End-to-End

### Phase 1: Initiation
During initiation, teams validate business needs and create a lightweight one-pager that captures the problem statement, success metrics, stakeholders, and timeline. This decision gate ensures that only well-aligned work moves forward into the planning phase, reducing rework and setting the stage for efficient execution.

### Phase 2: Planning
In the planning phase, scope is broken into shippable increments with clear acceptance criteria, dependencies are mapped, and a prioritized backlog is established. Teams define their Definition of Done, conduct a project kickoff with stakeholders, and create a release plan with key milestones.

### Phase 3: Execution
Execution and delivery are guided by a team rhythm that includes daily standups (15 minutes), weekly delivery syncs, and sprint-based iterations. Teams use a project board (Backlog → Ready → In Progress → In Review → QA → Done) and enforce code quality through pull request workflows, CI/CD checks, unit tests, integration tests, and security scanning. Progress is tracked through velocity, burndown, and success metrics.

### Phase 4: Release
Releases follow standardized checklists that include acceptance criteria verification, passing CI/CD and security scans, smoke tests, and rollback planning to minimize production risk. Post-deployment verifications and stakeholder announcements ensure visibility and confidence in the release.

### Phase 5: Retrospective & Continuous Improvement
After each sprint, release, or milestone, teams conduct retrospectives (45–75 minutes) to capture what went well, identify improvements, and assign 2–3 prioritized action items with clear owners and due dates. Action items are tracked in the backlog and reviewed in weekly PM syncs, ensuring that learnings are converted into organizational knowledge and process improvements are measured and celebrated.

## Roles & Communication

OctoAcme defines clear role ownership across **Project Managers, Product Managers, Developers, and QA specialists**, each with distinct responsibilities that enable accountability and coordination:

- **Project Managers** coordinate delivery, manage risks and timelines, and facilitate cross-team communication
- **Product Managers** define the "what" and "why" through customer insights and prioritization
- **Developers** implement features and collaborate on design and testability
- **QA specialists** validate acceptance criteria and quality standards

Communication is structured through:
- Weekly PM/PdM syncs
- Twice-weekly standups
- Monthly stakeholder updates
- Single source of truth (project README or release documentation)
- Three-level escalation path for blockers (team → PM → Product Lead → Sponsor)

## Contributing & Updating This Documentation

To propose updates or new content to these process documents:

1. **Create an issue** using the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template
2. **Include:**
   - Which document you're updating (or if it's new)
   - Summary of your proposed content
   - Rationale for the change
   - Suggested content (optional)
   - Acceptance criteria checkboxes
3. **Submit a pull request** that references the issue
4. **Request review** from the Product Lead and relevant team members

All updates should align with OctoAcme's core principles and improve clarity, reduce process overhead, or incorporate validated best practices.

---

**Last Updated:** July 14, 2026  
**Maintained by:** Project Management Community
