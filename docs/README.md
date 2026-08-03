# OctoAcme Project Management Processes (README)

This README indexes the OctoAcme project management process documents and provides a short summary of our approach. Additions or clarifications to any process doc should be proposed using the "Add Content to Project Management Process Docs" issue template in .github/ISSUE_TEMPLATE/.

Overview
OctoAcme organizes work around a lightweight, stage-driven lifecycle: Initiation, Planning, Execution, Release, and Retrospective. Initiatives begin with a concise Project One-pager that captures the problem statement, measurable goals, stakeholders, and a high-level timeline. A decision gate ensures success metrics and stakeholder alignment before moving to planning. Planning turns approved initiatives into prioritized backlog items with clear acceptance criteria, estimates, and a release/milestone map.

Project Summary
During execution, teams use a project board (Backlog → Ready → In Progress → In Review → QA → Done) to visualize flow and prioritize work. The pull request workflow encourages small, focused changes, includes linked issues and acceptance criteria, and requires CI checks and at least one approval before merging. Quality practices include unit and integration tests, security scanning in CI, and targeted end-to-end smoke tests and manual QA for critical flows.

Roles & Communication
Roles and responsibilities are explicit: Product Managers define outcomes and success metrics, Project Managers coordinate delivery and risks, Developers implement and test, and QA validates acceptance criteria. Communication cadence includes daily standups, weekly delivery syncs, sprint demos, and regular PM+PdM touchpoints. Stakeholder updates use standardized templates and follow an escalation path (team → PM → Product Lead → Sponsor) for unresolved or high-impact blockers.

Links to process documents (docs/)
- Project Management Overview — docs/octoacme-project-management-overview.md
- Project Initiation Guide — docs/octoacme-project-initiation.md
- Project Planning — docs/octoacme-project-planning.md
- Execution & Tracking — docs/octoacme-execution-and-tracking.md
- Release & Deployment — docs/octoacme-release-and-deployment.md
- Retrospective & Continuous Improvement — docs/octoacme-retrospective-and-continuous-improvement.md
- Risk Management & Communication — docs/octoacme-risks-and-communication.md
- Roles & Personas — docs/octoacme-roles-and-personas.md

How to contribute
- Use the repository issue template "Add Content to Project Management Process Docs" to propose new content or updates.
- Keep entries actionable, evidence-backed, and linked to related artifacts (roadmaps, release notes, PRs).
