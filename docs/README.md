# OctoAcme Project Management Docs

## Overview

OctoAcme uses a structured project management framework based on principles of **customer-first delivery**, **iterative development**, **clear ownership**, and **data-informed decisions**. These processes guide teams through every phase of project delivery—from initial concept through retrospectives and continuous improvement.

Whether you're kicking off a new initiative, managing day-to-day execution, preparing a release, or capturing learnings from a completed milestone, you'll find guidance, templates, and checklists in this documentation set.

## Quick Start

Use these guides based on your current project phase:

### 1. **Project Initiation**
   📄 [octoacme-project-initiation.md](./octoacme-project-initiation.md)
   
   Start here when you have a new project idea or feature proposal.
   - Validate business need and measurable outcomes
   - Identify stakeholders and champions
   - Create a Project One-pager
   - Make the go/no-go decision to move into planning

### 2. **Project Planning**
   📄 [octoacme-project-planning.md](./octoacme-project-planning.md)
   
   Turn your approved initiative into an actionable plan.
   - Break work into shippable increments
   - Create a prioritized backlog with acceptance criteria
   - Estimate scope and define Definition of Done
   - Identify dependencies and create a release plan

### 3. **Execution & Tracking**
   📄 [octoacme-execution-and-tracking.md](./octoacme-execution-and-tracking.md)
   
   Manage day-to-day delivery and track progress.
   - Run daily standups and weekly delivery syncs
   - Use project boards to track work (Backlog → Ready → In Progress → In Review → QA → Done)
   - Execute PR workflow with quality gates
   - Escalate blockers and manage dependencies

### 4. **Risk Management & Communication**
   📄 [octoacme-risks-and-communication.md](./octoacme-risks-and-communication.md)
   
   Identify, manage, and communicate risks proactively.
   - Maintain a Risk Register with ID, description, impact, likelihood, and mitigation
   - Follow escalation paths: Team → PM → Product Lead → Sponsor
   - Keep stakeholders informed with regular updates
   - Manage cross-team dependencies

### 5. **Release & Deployment**
   📄 [octoacme-release-and-deployment.md](./octoacme-release-and-deployment.md)
   
   Prepare and execute releases with minimal risk.
   - Complete pre-release requirements (acceptance criteria, CI passing, security scans)
   - Use deployment checklists and smoke tests
   - Plan rollback and incident response procedures
   - Document release notes and migration steps

### 6. **Retrospectives & Continuous Improvement**
   📄 [octoacme-retrospective-and-continuous-improvement.md](./octoacme-retrospective-and-continuous-improvement.md)
   
   Capture learnings and drive continuous improvement.
   - Conduct retrospectives after sprints, releases, or milestones
   - Identify what went well and what could improve
   - Create actionable improvement items with clear owners
   - Measure impact and iterate

## Core Concepts

### Roles & Personas
   📄 [octoacme-roles-and-personas.md](./octoacme-roles-and-personas.md)
   
   Understand the key roles in OctoAcme projects:
   - **Product Managers** (PdM): Define what should be built, prioritize backlog, measure success
   - **Project Managers** (PM): Coordinate delivery, manage schedules, risks, and communications
   - **Developers**: Implement features, collaborate on design, write tests and docs
   - **QA/Testing**: Validate quality and acceptance criteria
   - **Stakeholders**: Provide inputs and approvals

### Project Management Overview
   📄 [octoacme-project-management-overview.md](./octoacme-project-management-overview.md)
   
   High-level framework and reference guide:
   - Core principles and values
   - Key artifacts (Charter, Roadmap, Backlog, Risk Register, etc.)
   - Project lifecycle (5 phases)
   - Communication cadence and how to use these docs

## Key Principles

- **Customer-first**: Prioritize customer value and usability in every decision
- **Iterative delivery**: Deliver small, testable increments rather than waiting for a "big bang"
- **Clear ownership**: Each project has named PM and Product Lead responsible for outcomes
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback, learning, and blameless retrospectives

## Essential Artifacts

Every OctoAcme project maintains:

| Artifact | Purpose | Owner |
|----------|---------|-------|
| **Project Charter / One-pager** | Define problem, goals, success metrics, stakeholders, timeline | Product Lead + PM |
| **Roadmap & Release Plan** | High-level vision and milestone timeline | Product Lead |
| **Sprint/Iteration Backlog** | Prioritized work items with acceptance criteria | Product Lead |
| **Risk Register** | Track identified risks, impact, mitigation, and status | PM |
| **Project Board** | Visual tracking of work status (GitHub Projects or equivalent) | PM + Developers |
| **Release Notes** | Document changes, migration steps, known issues | PM + Developers |
| **Retrospective Notes** | Capture learnings and action items for improvement | PM |

## Communication Cadence

- **Daily**: 15-min team standup (progress, blockers, dependencies)
- **Weekly**: PM + Product Lead sync; Delivery team standup
- **Bi-weekly or end-of-sprint**: Demo/Review and Retrospective
- **Monthly**: Stakeholder updates
- **Ad-hoc**: Escalations and incident communications

## How to Use These Docs

1. **For Project Leads**: Start with [Project Initiation](./octoacme-project-initiation.md) to scope your work, then move through Planning, Execution, and Release phases.

2. **For Developers**: Review [Execution & Tracking](./octoacme-execution-and-tracking.md) for PR workflow and quality standards, and [Roles & Personas](./octoacme-roles-and-personas.md) for developer responsibilities.

3. **For New Team Members**: Read this README first, then explore the [Project Management Overview](./octoacme-project-management-overview.md) for a complete framework introduction.

4. **For Reference**: Use [Risk Management & Communication](./octoacme-risks-and-communication.md) and [Retrospectives](./octoacme-retrospective-and-continuous-improvement.md) as ongoing guides throughout your project.

5. **Keep docs updated**: Add project-specific artifacts (Charter, Release Plan, Risk Register) to your project repository. Update process docs via the issue template: `.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml`

---

**Last Updated**: September 2, 2026

For questions or to suggest improvements to these processes, please open an issue with the "Process Doc Update" template.
