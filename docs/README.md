# OctoAcme Project Management Docs

## Welcome to OctoAcme's Project Management Framework

This directory contains the complete set of project management processes, workflows, and guidance used across OctoAcme. Whether you're launching a new initiative, managing execution, or closing out a project, you'll find standardized approaches and templates here to support consistent, repeatable project delivery.

---

## Quick Overview: How OctoAcme Manages Projects

### Core Approach
OctoAcme operates on a **structured, iterative project lifecycle** that prioritizes customer value, clear ownership, and data-informed decisions. Every project flows through five key phases:

1. **Initiation** — Validate business need, align stakeholders, and define success criteria
2. **Planning** — Break work into shippable increments, identify dependencies and risks
3. **Execution** — Build, test, review, and iterate in tight feedback loops
4. **Release** — Deploy to production and verify outcomes
5. **Close & Retrospective** — Capture learnings and drive continuous improvement

### Key Principles
- **Customer-first:** Prioritize customer value and usability
- **Iterative delivery:** Deliver small, testable increments
- **Clear ownership:** Each project has a named Project Manager (PM) and Product Manager (PdM)
- **Data-informed decisions:** Measure impact and iterate based on evidence
- **Psychological safety:** Encourage feedback and learning

### Who Does What?
Three primary roles anchor every project:

- **Project Manager (PM)** — Coordinates delivery schedules, manages risks, and owns communications
- **Product Manager (PdM)** — Defines outcomes, prioritizes the backlog, and measures success
- **Developers** — Implement features while collaborating on design and quality
- **QA/Testing** — Validate quality and acceptance criteria

For detailed role definitions, see [Roles and Personas](octoacme-roles-and-personas.md).

### Quality & Execution Standards

OctoAcme maintains disciplined execution practices:
- **Small pull requests** (≤400 lines when possible) with peer review before merge
- **Automated CI/CD** with unit tests, integration tests, and security scanning
- **Quality gates:** End-to-end smoke tests before release, security validation
- **Regular communication:** Daily standups (15 min), weekly delivery syncs, monthly stakeholder updates
- **Risk management:** Continuous risk register updates and three-level escalation paths

### Continuous Improvement Culture

After each sprint, release, or milestone, OctoAcme conducts blameless retrospectives to surface what went well, what could improve, and actionable next steps. These improvements are tracked and reviewed in weekly PM syncs, ensuring learning compounds over time and reduces single-person dependencies.

---

## Process Documentation by Phase

### 📋 Getting Started
- **[Project Management Overview](octoacme-project-management-overview.md)** — High-level introduction to OctoAcme's approach, roles, key artifacts, and communication cadence

### 🚀 Initiation Phase
- **[Project Initiation Guide](octoacme-project-initiation.md)** — Steps to validate business need, align stakeholders, create a lightweight one-pager, and decide go/no-go for planning

### 📅 Planning Phase
- **[Project Planning Guide](octoacme-project-planning.md)** — Turn an approved initiative into an actionable plan, create prioritized backlog, define Definition of Done, and identify dependencies

### ⚙️ Execution Phase
- **[Execution & Tracking Guide](octoacme-execution-and-tracking.md)** — Manage day-to-day delivery using project boards, pull request workflows, quality practices, and blocker escalation

### ⚠️ Cross-Cutting: Risk & Communication
- **[Risk Management & Communication Guide](octoacme-risks-and-communication.md)** — Maintain a risk register, escalate dependencies, and standardize stakeholder communication throughout the project lifecycle

### 🎉 Release Phase
- **[Release & Deployment Guide](octoacme-release-and-deployment.md)** — Standardize releases by type (patch, minor, major), enforce pre-release checklists, and manage rollback scenarios

### 🔄 Close & Improvement
- **[Retrospective & Continuous Improvement Guide](octoacme-retrospective-and-continuous-improvement.md)** — Run blameless retrospectives, convert learnings into action items, and measure impact of improvements

### 👥 Reference
- **[Roles and Personas](octoacme-roles-and-personas.md)** — Detailed role definitions, responsibilities, and communication patterns for developers, product managers, and project managers

---

## How to Use These Docs

### As a Team Member Starting a New Project
1. Read the **Project Management Overview** to understand the framework
2. Work with your PM/PdM to complete the **Project Initiation** guide
3. Move to **Planning** once initiation is approved
4. Follow the **Execution** workflow during delivery
5. Use **Risk Management & Communication** continuously
6. Prepare for **Release** as you approach go-live
7. Conduct a **Retrospective** to capture improvements

### As a Copilot Space User
These docs are centralized in this repository and can be added to your Copilot Space context for AI-assisted guidance. Reference specific process docs when asking Copilot for help with planning, execution, or process improvements.

### For Process Improvements
Found a gap or improvement opportunity? Use the [Add Content to Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template to propose updates. All changes are reviewed to maintain consistency across the framework.

---

## Key Artifacts at a Glance

| Artifact | Purpose | Created During |
|----------|---------|-----------------|
| **Project One-pager** | Single source of truth defining problem, goal, metrics, timeline | Initiation |
| **Project Backlog** | Prioritized list of work with acceptance criteria | Planning |
| **Risk Register** | Tracked risks with impact, likelihood, owner, mitigation | Planning & Ongoing |
| **Project Board** | Visual workflow tracking (Backlog → In Progress → Done) | Planning & Execution |
| **Release Notes** | Stakeholder-facing summary of changes and migration steps | Release |
| **Retrospective Notes** | Learnings, action items, and owners for improvements | Close |

---

## Communication Cadence

OctoAcme standardizes communication to ensure alignment without overwhelming the team:

- **Daily:** 15-minute standups (team focus on progress, blockers, dependencies)
- **Weekly:** PM-PdM alignment, delivery sync, risk register review
- **Monthly:** Stakeholder updates and roadmap reviews
- **Ad-hoc:** Escalation when blockers or decisions are needed

---

## Questions or Feedback?

These docs are living artifacts. If you have questions, find inconsistencies, or want to propose improvements:
- Ask in the team Slack channel
- Open an issue using the [Add Content to Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template
- Propose a pull request with your suggestions

Together, we scale institutional knowledge and improve how we execute projects. 🚀

---

*Last updated: 2026-03-10*
