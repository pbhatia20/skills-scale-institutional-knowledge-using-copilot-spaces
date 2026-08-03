README: OctoAcme project management processes summary and links to docs

### Which process document do you want to update? (If this is a new document, select '<new document>')


octoacme-project-management-overview.md

### Summary of New Content

Add a new README in the docs/ folder that indexes all OctoAcme project management process documents and provides a concise summary of the program management processes used by OctoAcme.

### Why is this update needed?

A single README will make the collection of process docs easier to find and consume for new teammates, reduce onboarding friction, and provide a canonical entry point for process updates. It closes the discoverability gap and ensures a consistent summary of practices across the project.

### Suggested Content (optional)

# OctoAcme Project Management Processes (README)

This README indexes the OctoAcme project management process documents and provides a short summary of our approach. Additions or clarifications to any process doc should be done via the "Add Content to Project Management Process Docs" issue template.

Project management processes summary
- Purpose: Centralize playbooks and templates for project initiation, planning, execution, release, and continuous improvement.
- Rhythm: Regular standups, weekly delivery syncs, sprint demos, and retrospective cycles.
- Workflows: Use a project board (Backlog → Ready → In Progress → In Review → QA → Done) and small PRs with acceptance criteria.
- Quality: Unit/integration tests, CI security scanning, and manual QA as needed.
- Communication: Weekly PM+PdM syncs, stakeholder updates, and a clear escalation path for blockers and incidents.

Links to process documents (docs/):
- [Project Management Overview](docs/octoacme-project-management-overview.md) — concise intro to OctoAcme roles, principles, lifecycle, and key artifacts.
- [Project Initiation Guide](docs/octoacme-project-initiation.md) — how to validate, authorize, and create an initial one-pager and decision gate.
- [Project Planning](docs/octoacme-project-planning.md) — turning an approved initiative into a backlog, release plan, and risk register.
- [Execution \u0026 Tracking](docs/octoacme-execution-and-tracking.md) — day-to-day execution, team rhythm, PR workflow, and reporting.
- [Release \u0026 Deployment](docs/octoacme-release-and-deployment.md) — release types, pre-release checklist, deployment checklist, and rollback playbook.
- [Retrospective \u0026 Continuous Improvement](docs/octoacme-retrospective-and-continuous-improvement.md) — running retrospectives, tracking action items, and measuring improvements.
- [Risk Management \u0026 Communication](docs/octoacme-risks-and-communication.md) — maintaining a risk register, communication templates, and escalation paths.
- [Roles \u0026 Personas](docs/octoacme-roles-and-personas.md) — role summaries and responsibilities for Developers, Product Managers, and Project Managers.

How to contribute
- Use the repository issue template "Add Content to Project Management Process Docs" to propose new content or updates.
- Keep entries actionable, evidence-backed, and linked to related artifacts (roadmaps, release notes, PRs).

Suggested README metadata (frontmatter) can be added if you want it surfaced by doc tooling.

### Acceptance Criteria

- [x] Content aligns with existing process docs
- [x] Update improves clarity or closes a documented gap
- [ ] Proposed content has been reviewed with stakeholders (if needed)