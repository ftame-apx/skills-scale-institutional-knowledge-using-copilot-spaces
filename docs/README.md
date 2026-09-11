# OctoAcme Project Management Documentation

Welcome to the OctoAcme Project Management Docs. This is the central hub for understanding how OctoAcme runs projects and delivers value.

## What is OctoAcme?

OctoAcme is a customer-first, iterative project delivery framework built on principles of clear ownership, data-driven decisions, and psychological safety. Our approach spans five key lifecycle phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Retrospective & Continuous Improvement**.

## OctoAcme Project Management Approach

### Overview

OctoAcme follows a structured, lifecycle-based project management approach designed to balance customer-first delivery with organizational accountability. The framework progresses through five core phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Retrospective & Continuous Improvement**. The Initiation phase validates business need and stakeholder alignment through a lightweight Project One-pager and decision gate, ensuring only viable initiatives move forward. Planning breaks approved work into shippable increments with clear acceptance criteria, estimated scope, and documented dependencies. This progression creates clarity early and reduces rework downstream, while maintaining flexibility through iterative delivery of small, testable increments.

### Execution & Quality

Execution and day-to-day tracking happen through a well-defined team rhythm and structured workflows. Teams use GitHub Projects with standard columns (Backlog, Ready, In Progress, In Review, QA, Done) and conduct daily standups (15 minutes), weekly delivery syncs, and sprint-based planning cycles. Pull requests are kept small (≤400 lines), include issue links and acceptance criteria, and require at least one approval before merging. Quality is embedded throughout: unit tests, integration tests, end-to-end smoke tests, and security scanning run in CI before review. This emphasis on automated validation and clear PR discipline reduces defects and accelerates feedback cycles.

### Communication & Risk Management

Communication and risk management are centralized with clearly defined escalation paths. Weekly syncs between the Project Manager (PM) and Product Manager connect delivery progress to business outcomes, while stakeholder updates maintain transparency at the organizational level. Risk registers are maintained with ID, description, impact, likelihood, owner, and mitigation plan, reviewed at weekly syncs. When blockers emerge, they are triaged in daily standups (Level 1), escalated to the Product Lead and dependent teams by the PM (Level 2), or escalated to sponsors for business-impacting issues (Level 3). This tiered approach ensures rapid unblocking without unnecessary delay.

### Continuous Improvement

OctoAcme embeds learning and continuous improvement into its culture through structured retrospectives held after sprints, releases, or milestones. Retrospectives use a simple framework (what went well, what could improve, action items with owners and due dates) and prioritize 2–3 top improvements to avoid overload. Action items are added to the project backlog with clear success criteria and tracked in weekly PM syncs, creating a feedback loop that continuously refines processes. Paired with role clarity and a single source of truth for artifacts, this approach reduces single-person dependency, accelerates onboarding, and enables consistent, repeatable project execution.

## Quick Navigation

### Core Concepts
- **[Project Management Overview](./octoacme-project-management-overview.md)** — Introduction to OctoAcme principles, roles, artifacts, and lifecycle
- **[Roles & Personas](./octoacme-roles-and-personas.md)** — Detailed descriptions of Developers, Product Managers, and Project Managers

### Lifecycle Guides
1. **[Project Initiation](./octoacme-project-initiation.md)** — Validate ideas, align stakeholders, create a lightweight plan
2. **[Project Planning](./octoacme-project-planning.md)** — Break work into shippable increments, estimate, and define dependencies
3. **[Execution & Tracking](./octoacme-execution-and-tracking.md)** — Manage day-to-day delivery, track progress, and escalate blockers
4. **[Release & Deployment](./octoacme-release-and-deployment.md)** — Standardize releases, reduce risk, and ensure smooth production deployments
5. **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and drive iterative improvements

### Cross-Cutting Concerns
- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** — Identify, assess, and communicate risks and dependencies

## Getting Started

**New to OctoAcme?** Start with the [Project Management Overview](./octoacme-project-management-overview.md) to understand our core principles and roles.

**Starting a new project?** Follow the [Project Initiation Guide](./octoacme-project-initiation.md) to validate the idea and get stakeholder alignment.

**Need to manage day-to-day delivery?** See [Execution & Tracking](./octoacme-execution-and-tracking.md) for guidance on standups, velocity, and blocker escalation.

**Wrapping up a project?** Review [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) to capture learnings and drive improvements.

## Issue Templates

Submit process documentation updates and improvements using our [Process Documentation Update Template](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml).
