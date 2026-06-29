# OctoAcme Project Management Docs

## Summary of Project Management Processes
OctoAcme runs projects with an outcome-oriented, iterative model that emphasizes clear ownership, measurable success criteria, and repeatable artifacts. Projects begin with a lightweight initiation (a Project One‑pager, stakeholder list, and success metrics) and move into planning that breaks approved initiatives into shippable increments with acceptance criteria and a Definition of Done. The approach balances speed with risk management: small, testable deliveries are prioritized and validated with automated and manual quality checks.

Day-to-day delivery uses a disciplined workflow centered on a project board (Backlog → Ready → In Progress → In Review → QA → Done) and a strict pull request process. PRs should be small and focused (target ≤400 lines where possible), include an issue link and acceptance criteria, and pass CI (tests, linting, security scans) before review. Releases follow a checklist-driven process with staging verification, smoke tests, rollback planning, and post-deploy verification to reduce production risk.

Roles and communication are explicit: Product Managers define outcomes and measure impact; Project Managers coordinate schedules, risks, and communications; Developers build and test; QA validates acceptance. The team cadence includes daily standups for progress and blockers, weekly delivery syncs for updates and risks, demos at sprint/milestone ends, and monthly stakeholder updates. Clear escalation paths (team → PM → Product Lead → Sponsor) and incident communication templates ensure rapid, consistent responses to production or program-impacting issues.

Quality and continuous improvement are embedded throughout the lifecycle. QA practices include unit and integration tests, end‑to‑end smoke tests for critical flows, CI security scanning, and manual QA as needed. Retrospectives after sprints, releases, or incidents convert learnings into prioritized action items tracked in the backlog. A simple risk register (ID, impact, likelihood, owner, mitigation, status) is maintained and reviewed regularly to keep stakeholders informed and to drive mitigations.

---

## Documents (index)
- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Roles & Personas](octoacme-roles-and-personas.md)

## Project Lifecycle & Which Doc to Use
- Initiation
  - Use: [Project Initiation Guide](octoacme-project-initiation.md)
  - When: Starting a new project or feature proposal; create the one‑pager and confirm stakeholders and success metrics.
- Planning
  - Use: [Project Planning](octoacme-project-planning.md)
  - When: Turning an approved initiative into a backlog, estimates, release plan, and DoD.
- Execution & Tracking
  - Use: [Execution & Tracking](octoacme-execution-and-tracking.md)
  - When: Running sprints, daily standups, tracking velocity, and managing PR workflow.
- Release & Deployment
  - Use: [Release & Deployment Guide](octoacme-release-and-deployment.md)
  - When: Preparing to ship to staging/production—follow checklists and smoke tests.
- Retrospective & Improvement
  - Use: [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
  - When: After sprints, releases, or incidents to capture learnings and action items.

## Cross-Cutting Guidance
- For a quick high-level overview or onboarding, see [Project Management Overview](octoacme-project-management-overview.md).
- For risk capture, stakeholder comms, and escalation paths, see [Risk Management & Communication](octoacme-risks-and-communication.md).
- For role definitions and responsibilities, see [Roles & Personas](octoacme-roles-and-personas.md).

## Quick Start
- New to OctoAcme? Start with the [Project Management Overview](octoacme-project-management-overview.md).
- Starting a new project? Complete the Project One‑pager in the [Project Initiation Guide](octoacme-project-initiation.md).
- In execution? Use [Execution & Tracking](octoacme-execution-and-tracking.md) daily and review [Risk Management & Communication](octoacme-risks-and-communication.md) weekly.

## Contribution / Updates
If you want to add or update content in these process docs, use the issue template: .github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml and link your changes to the relevant doc. Proposed updates should include a summary, rationale, and suggested content for easier review.
