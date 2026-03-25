# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management Documentation! This README provides a central entry point to all project management practices, processes, templates, and workflows used by OctoAcme. Whether you're starting a new project, onboarding to a team, or looking for guidance on a specific phase of delivery, you'll find the resources you need here.

## Quick Links to All Process Docs

- **[Project Management Overview](octoacme-project-management-overview.md)** — High-level introduction to OctoAcme's approach, core roles, key artifacts, and lifecycle phases.
- **[Project Initiation Guide](octoacme-project-initiation.md)** — Steps to validate business need, align stakeholders, and authorize work with a lightweight One-pager.
- **[Project Planning](octoacme-project-planning.md)** — How to break work into shippable increments, manage dependencies, and create a release plan.
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Day-to-day execution guidance including team rhythm, PR workflows, quality practices, and blocker escalation.
- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — How to identify, track, and communicate risks; manage dependencies; and keep stakeholders informed.
- **[Release & Deployment Guide](octoacme-release-and-deployment.md)** — Standardized approach to releasing features to production, including checklists, rollback procedures, and release notes.
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Process for capturing learnings after sprints, releases, and incidents; converting insights into actionable improvements.
- **[OctoAcme Personas](octoacme-roles-and-personas.md)** — Role definitions and responsibilities for Developers, Product Managers, and Project Managers.

---

## OctoAcme Project Management Overview

### Core Principles

OctoAcme runs projects around five foundational principles:

1. **Customer-First** — Prioritize customer value and usability in every decision.
2. **Iterative Delivery** — Deliver small, testable increments rather than large monolithic releases.
3. **Clear Ownership** — Each project has a named Project Manager and Product Lead accountable for outcomes.
4. **Data-Informed Decisions** — Measure impact and iterate based on evidence, not assumptions.
5. **Psychological Safety** — Encourage feedback, learning, and continuous improvement without fear of blame.

### Project Lifecycle

OctoAcme projects follow a five-phase lifecycle designed to deliver value consistently:

1. **Initiation** — Validate business need, define success metrics, align stakeholders, and decide go/no-go for planning.
2. **Planning** — Break work into shippable increments with clear acceptance criteria, identify dependencies, and establish release timelines.
3. **Execution & Tracking** — Build, test, and review code in short cycles; hold daily standups and weekly syncs; monitor progress against metrics.
4. **Release & Deployment** — Gate production releases on checklists, quality gates, and rollback plans; announce to stakeholders; monitor for issues.
5. **Retrospective & Continuous Improvement** — Capture learnings after each sprint, release, or milestone; convert insights into actionable improvements; track impact.

### Key Roles & Responsibilities

OctoAcme defines clear, complementary roles to ensure accountability and collaboration:

- **Product Manager (PdM)** — Owns the product vision, prioritizes the backlog, defines success metrics, and measures customer impact.
- **Project Manager (PM)** — Coordinates delivery, manages schedules and timelines, owns risk and dependency management, facilitates communication.
- **Developers** — Implement features, write tests, collaborate on design reviews, help identify technical risks, and maintain code quality.
- **QA/Testing** — Validate quality, verify acceptance criteria, run smoke tests before release, and report on test coverage and defects.
- **Stakeholders** — Provide business context, approve prioritization, and receive regular updates on progress and risks.

### Communication Cadence

Consistent, structured communication is essential to OctoAcme's success:

- **Daily Standups** (15 min) — Delivery team syncs on progress, blockers, and dependencies.
- **Twice-Weekly Standups** — Extended team check-ins as needed.
- **Weekly PM + PdM Sync** — Alignment on priorities, metrics, risks, and upcoming milestones.
- **Weekly Delivery Sync** — Show progress on the board, flag risks, and escalate blockers.
- **Monthly Stakeholder Updates** — High-level status, wins, and upcoming milestones for sponsors and business stakeholders.
- **Ad-Hoc Escalations** — Blocker escalation path: Team → PM → Product Lead → Sponsor.

### Quality & Testing Strategy

Quality is embedded throughout the OctoAcme execution phase:

- **Unit Tests** — Required for all new logic.
- **Integration Tests** — Included where applicable to verify component interactions.
- **End-to-End Smoke Tests** — Run before release to validate critical user flows.
- **Security Scanning** — Automated in CI to catch vulnerabilities early.
- **Manual QA** — Feature acceptance testing when needed for complex scenarios.
- **PR Workflow** — Small PRs (≤ 400 lines), automated CI checks, and at least one approval before merging.

### Risk Management & Escalation

OctoAcme proactively identifies and manages risks to prevent surprises:

- **Risk Register** — Maintained throughout the project with ID, description, impact, likelihood, owner, and mitigation plan.
- **Weekly Risk Review** — Risks assessed and updated in weekly PM syncs; new risks flagged immediately.
- **Dependency Tracking** — Cross-team dependencies marked on project board and escalated during weekly alignment meetings.
- **Blocker Escalation** — Three-level model: Level 1 (team triage in standups), Level 2 (PM escalates to Product Lead), Level 3 (sponsor-level escalation for business impact).

### Key Artifacts

Every OctoAcme project maintains these core artifacts as the single source of truth:

- **Project Charter / One-Pager** — Problem statement, goal, success metrics, stakeholders, timeline, risks, and team.
- **Roadmap & Release Plan** — High-level features, milestones, and delivery dates.
- **Sprint/Iteration Backlog** — Prioritized items with clear acceptance criteria and Definition of Done.
- **Risk Register** — Active tracking of identified risks with mitigation plans.
- **Weekly Status Reports** — Progress, next steps, risks/blockers, and decisions needed.
- **Retrospective Notes & Action Items** — Learnings and improvement actions with owners and due dates.

---

## Getting Started

### For New Team Members
Start with [Project Management Overview](octoacme-project-management-overview.md) to understand OctoAcme's approach, then review [OctoAcme Personas](octoacme-roles-and-personas.md) to understand your role and responsibilities.

### For Project Managers
Review the full lifecycle starting with [Project Initiation Guide](octoacme-project-initiation.md) and [Project Planning](octoacme-project-planning.md). Keep [Risk Management & Communication](octoacme-risks-and-communication.md) and [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) close at hand.

### For Product Managers
Start with [Project Management Overview](octoacme-project-management-overview.md) and [Project Initiation Guide](octoacme-project-initiation.md) to understand how to define success metrics and validate business need. Reference [Risk Management & Communication](octoacme-risks-and-communication.md) for stakeholder updates.

### For Developers
Focus on [Execution & Tracking](octoacme-execution-and-tracking.md) for PR workflow, testing standards, and quality practices. Review [OctoAcme Personas](octoacme-roles-and-personas.md) for developer responsibilities and [Release & Deployment Guide](octoacme-release-and-deployment.md) before your first production deploy.

### For QA/Testing
Review [Execution & Tracking](octoacme-execution-and-tracking.md) for quality and testing standards, and [Release & Deployment Guide](octoacme-release-and-deployment.md) for pre-release and post-release verification procedures.

---

## Using These Docs with Copilot Spaces

These process documents are versioned and maintained in this repository to enable Copilot Spaces to provide context-aware guidance. When you attach this repository to a Copilot Space, you can ask questions like:

- "What's the OctoAcme process for managing project risks?"
- "How should I structure a weekly status update?"
- "What are the acceptance criteria for a release?"

Copilot will reference these documents to provide consistent, organizational guidance grounded in your actual practices.

---

## Contributing to These Docs

To propose updates or additions to the OctoAcme project management process documentation, use the **[Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)** issue template.

When you identify a gap, see an opportunity for improvement, or want to capture a new best practice, please create an issue. Include:
- Which document you want to update (or if it's a new document)
- Summary of the new content or change
- Why the update is needed
- Suggested content (if you have it)

Your contributions help make OctoAcme's processes clearer, more effective, and easier to follow.

---

## Questions?

If you have questions about any process, reach out to your Project Manager or Product Lead, or create an issue using the **Add Content to Project Management Process Docs** template to start a conversation with the team.

Happy shipping! 🚀
