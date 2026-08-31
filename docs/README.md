# OctoAcme Project Management Documentation

Welcome to the OctoAcme Project Management guide. This documentation outlines how we run projects, coordinate teams, and deliver customer value.

## 📋 What is OctoAcme?

OctoAcme is a project management approach built on principles of **customer-first delivery**, **iterative development**, **clear ownership**, and **data-informed decisions**. Our methodology enables teams to deliver features and services reliably while maintaining psychological safety and continuous improvement.

## 🌟 Project Management Overview

OctoAcme follows a structured five-phase project lifecycle with clear decision gates at each stage. During **Initiation**, we validate business need and align stakeholders using a lightweight One-pager that captures the problem statement, success metrics, and key stakeholders. The **Planning** phase breaks work into shippable increments with prioritized backlogs, acceptance criteria, and risk registers. **Execution** uses GitHub Projects for workflow management with small pull requests (≤400 lines), automated CI, code reviews, and regular demos. The **Release** phase standardizes deployment through pre-flight checklists, smoke testing, and documented rollback plans. Finally, **Close & Retrospective** captures learnings and converts them into actionable improvements.

Throughout all phases, OctoAcme maintains a Risk Register that tracks likelihood, impact, mitigation strategies, and owners—reviewed weekly to catch blockers early. Quality is embedded at every stage through unit tests, integration tests, end-to-end smoke tests, automated security scanning, and manual QA when needed.

### Core Roles & Communication

OctoAcme defines clear roles with explicit responsibilities:

- **Developers** design, build, test, and maintain code while identifying technical risks
- **Product Managers** define vision, prioritize backlogs, and measure outcomes
- **Project Managers** coordinate schedules, manage risks, facilitate meetings, and report status
- **Stakeholders** provide input, feedback, and approvals

Communication is consistent and structured: daily 15-minute standups focus on progress and blockers; weekly syncs between PM and Product Manager discuss delivery metrics and risks; twice-weekly standups for delivery teams; and monthly stakeholder updates. Escalation follows a formal path (team-level → PM → Product Lead → Sponsor) to ensure visibility and rapid resolution of blockers.

### Continuous Improvement Culture

Teams track velocity, burndown, and success metrics identified in the Project One-pager using dashboards for key signals (errors, latency, usage). After each sprint, release, or milestone, teams conduct 45–75 minute retrospectives to capture what went well, what could improve, and prioritize 2–3 actionable items with clear owners and due dates. This feedback loop—measuring impact of action items and making iterative changes—builds a culture of continuous improvement.

## 🔄 Project Lifecycle

All OctoAcme projects follow these phases:

1. **Initiation** - Validate need, align stakeholders, define success criteria
2. **Planning** - Break work into shippable increments, identify dependencies, estimate scope
3. **Execution** - Build, test, review, iterate with daily standup rhythm
4. **Release** - Deploy to production with safety gates, smoke tests, and observability
5. **Close & Retrospective** - Capture learnings and drive continuous improvements

## 📚 Documentation Guide

### Getting Started

- **[Project Management Overview](octoacme-project-management-overview.md)** - Start here for a high-level introduction to OctoAcme's approach, core roles, and key artifacts
- **[Roles & Personas](octoacme-roles-and-personas.md)** - Understand the responsibilities and communication patterns for Developers, Product Managers, and Project Managers

### For Each Project Phase

- **[Project Initiation](octoacme-project-initiation.md)** - Define business need, stakeholders, and decision gates for moving to planning
- **[Project Planning](octoacme-project-planning.md)** - Create actionable backlog, estimate scope, identify dependencies, and define Definition of Done
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** - Manage day-to-day delivery, quality gates, team rhythm, and blocker escalation
- **[Release & Deployment](octoacme-release-and-deployment.md)** - Standardize release process, pre-release checks, deployment procedures, and rollback
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** - Capture learnings, prioritize improvements, and track action items

### Cross-Cutting Concerns

- **[Risk Management & Communication](octoacme-risks-and-communication.md)** - Manage risks, escalation paths, stakeholder communication templates, and incident protocols

## 🎯 How to Use These Docs

**New Team Members**: Start with [Project Management Overview](octoacme-project-management-overview.md) and your role's section in [Roles & Personas](octoacme-roles-and-personas.md)

**Starting a New Project**: Follow the [Project Initiation](octoacme-project-initiation.md) checklist to validate need and create your One-pager

**During Execution**: Reference [Execution & Tracking](octoacme-execution-and-tracking.md) and [Risk Management & Communication](octoacme-risks-and-communication.md) for day-to-day guidance

**Planning a Release**: Use [Release & Deployment](octoacme-release-and-deployment.md) checklist to ensure all pre-flight requirements are met

**Improving Processes**: Found a gap or have feedback? Use the [Add Content to Project Management Process Docs](.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template to propose updates

**After Milestones**: Run a retrospective using the guidance in [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) and add improvements to your backlog

## 🔗 Quick Reference

| Phase | Purpose | Key Artifact | Success Criteria |
|-------|---------|--------------|------------------|
| Initiation | Validate need & align stakeholders | One-pager | Clear metrics, sponsor approval |
| Planning | Create actionable plan | Prioritized backlog | Dependencies identified, DoD defined |
| Execution | Deliver incrementally | Sprint backlog, PRs | Quality gates met, risks tracked |
| Release | Deploy to production | Release notes | Pre-flight checks passed, rollback ready |
| Retrospective | Capture learnings | Action items | Improvements identified & tracked |

## 📖 Key Principles

- **Customer-first**: Prioritize customer value and usability in all decisions
- **Iterative delivery**: Deliver small, testable increments regularly
- **Clear ownership**: Each project has a named PM and Product Lead
- **Data-informed**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback, learning, and blameless retrospectives

## 📞 Need Help?

- Not sure where to start? Check [Getting Started](#-how-to-use-these-docs)
- Have a question about a specific role? See [Roles & Personas](octoacme-roles-and-personas.md)
- Encountered a blocker? Follow escalation guidance in [Risk Management & Communication](octoacme-risks-and-communication.md)
- Want to improve these docs? Create an issue using the [Add Content to Project Management Process Docs](.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template
