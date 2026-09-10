# OctoAcme Project Management Docs

Welcome to OctoAcme's project management knowledge base. This folder contains standardized processes and guidance for running cross-functional projects that deliver product features, services, and integrations.

## Quick Start

New to OctoAcme projects? Start with [OctoAcme Project Management Overview](octoacme-project-management-overview.md) for a high-level introduction to our approach, roles, and key artifacts.

## OctoAcme Project Management Approach

**Core Principles:**
- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager (PM) and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Project Lifecycle

Our projects follow five core phases:

### 1. **Initiation** - Validate & Authorize
Confirm business need, identify stakeholders, define success criteria, and decide go/no-go for planning.
- Key output: Project One-pager

### 2. **Planning** - Build the Plan
Break work into shippable increments, estimate scope, identify dependencies, and create a release plan.
- Key outputs: Prioritized backlog, Definition of Done, Risk Register

### 3. **Execution** - Deliver the Work
Build, test, review, and iterate with daily standups and weekly syncs. Track progress and manage blockers.
- Key activities: Daily standups, PR reviews, automated testing, risk monitoring

### 4. **Release** - Deploy to Production
Prepare release notes, deploy to staging, run smoke tests, and deploy to production with rollback plans ready.
- Key outputs: Release notes, deployment verification, incident playbook

### 5. **Close & Retrospective** - Learn & Improve
Capture learnings, convert them into action items, and feed improvements back into processes.
- Key activities: Retrospective meeting, action item tracking, continuous improvement

## Core Documents

Browse the complete process library:

- [**Project Management Overview**](octoacme-project-management-overview.md)
  Concise introduction to OctoAcme's approach, roles, artifacts, and high-level lifecycle.

- [**Project Initiation Guide**](octoacme-project-initiation.md)
  Guidance for validating and authorizing new projects. Includes the Project One-pager template.

- [**Project Planning**](octoacme-project-planning.md)
  How to break work into shippable increments, estimate, define Definition of Done, and manage dependencies.

- [**Execution & Tracking**](octoacme-execution-and-tracking.md)
  Day-to-day execution guidance: standups, PR workflows, quality standards, and blocker escalation.

- [**Risk Management & Communication**](octoacme-risks-and-communication.md)
  How to identify, assess, and monitor risks. Stakeholder communication templates and escalation paths.

- [**Release & Deployment Guide**](octoacme-release-and-deployment.md)
  Release types, pre-release requirements, deployment checklists, and rollback procedures.

- [**Retrospective & Continuous Improvement**](octoacme-retrospective-and-continuous-improvement.md)
  How to run retrospectives, track action items, and drive continuous improvement.

- [**Roles & Personas**](octoacme-roles-and-personas.md)
  Detailed descriptions of typical roles: Developers, Product Managers, Project Managers, and QA/Testing.

## Key Roles

| Role | Responsibilities |
|------|-----------------|
| **Project Manager (PM)** | Coordinates delivery, manages schedules, risks, and communications; ensures projects stay on track |
| **Product Manager (PdM)** | Defines outcomes, prioritizes backlog, measures success; owns product vision |
| **Developers** | Implement features, write tests and documentation, participate in design reviews |
| **QA/Testing** | Validate quality, verify acceptance criteria, run smoke tests |
| **Stakeholders** | Provide inputs, approvals, and strategic guidance |

## Communication Cadence

- **Daily**: 15-minute standup (team-focused: progress, blockers, dependencies)
- **Weekly**: PM + PdM sync to align on priorities and risks
- **Twice-weekly** (or as agreed): Delivery team standup for execution updates
- **Monthly**: Stakeholder updates and roadmap reviews
- **Ad-hoc**: Escalations for blockers and critical issues

## How to Use These Docs

1. **For new projects**: Start with [Initiation Guide](octoacme-project-initiation.md), then move through each phase in order.

2. **For specific tasks**: Jump to the phase-specific document that matches your current activity:
   - Starting a project? → Initiation
   - Planning work? → Planning
   - Tracking daily work? → Execution & Tracking
   - Getting ready to ship? → Release & Deployment
   - Wrapping up? → Retrospective

3. **Keep it current**: Update your project charter in the project repository. Add role-specific guidance to `.copilot/` for [Copilot Spaces](https://docs.github.com/en/copilot/copilot-spaces/about-copilot-spaces) integration.

4. **Contribute improvements**: Found a gap or improvement? Open a pull request or file an issue using the [Add Content to Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template.

---

**Last updated**: September 2026  
**Maintained by**: OctoAcme Project Management Community
