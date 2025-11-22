# OctoAcme Project Management Docs

## Summary

OctoAcme runs projects with a disciplined, iterative delivery model focused on small, measurable increments and clear artifacts. Work begins at initiation with a lightweight Project One-pager to capture the problem, goals, success metrics, stakeholders and timeline. Planning converts the one-pager into a prioritized backlog, release plan, and Definition of Done. Execution uses a visible project board and explicit states (Backlog → Ready → In Progress → In Review → QA → Done) to make handoffs and progress explicit. Releases follow a standard checklist with smoke tests and rollback plans, and retrospectives capture improvements after sprints, releases, or incidents.

Day-to-day workflows emphasize small, reviewable changes and automated gates. Pull requests are kept small when possible, must reference issues and acceptance criteria, and run linting, tests and security scans in CI before review. Sprint planning pulls only backlog items that meet the Definition of Done and have clear acceptance criteria. The release guide and deployment checklist standardize pre-release requirements, post-deploy verifications, and incident/rollback procedures to reduce production risk.

Roles and communication are explicit: a Project Manager owns delivery, schedule, risks and communication; a Product Manager defines outcomes and prioritization; developers implement and test; QA validates acceptance. Cadence includes short daily standups to surface blockers, regular delivery syncs and demos, PM+PdM weekly alignment, and monthly stakeholder updates. Escalation paths and communication templates (weekly status, incident triage) ensure predictable handling of issues.

Quality practices include unit and integration tests, end-to-end smoke tests for critical flows, automated security scanning in CI, and manual QA where necessary. Retrospectives are timeboxed and focus on creating 2–3 actionable improvements that become backlog items. A maintained risk register (ID, impact, likelihood, owner, mitigation, status) ensures risks are tracked and reviewed. Overall, the docs prioritize repeatability, observability and clear ownership so teams can deliver reliably and iterate on improvements.

## Index of process documents

- [octoacme-project-management-overview.md](octoacme-project-management-overview.md)
- [octoacme-project-initiation.md](octoacme-project-initiation.md)
- [octoacme-project-planning.md](octoacme-project-planning.md)
- [octoacme-execution-and-tracking.md](octoacme-execution-and-tracking.md)
- [octoacme-risks-and-communication.md](octoacme-risks-and-communication.md)
- [octoacme-release-and-deployment.md](octoacme-release-and-deployment.md)
- [octoacme-retrospective-and-continuous-improvement.md](octoacme-retrospective-and-continuous-improvement.md)
- [octoacme-roles-and-personas.md](octoacme-roles-and-personas.md)

## How to use these docs

- Keep the Project One-pager updated in your project repository to ensure alignment with current goals and success metrics.
- Add process-specific docs to `.copilot/` for Copilot Spaces context to help AI assistants understand your team's workflows and conventions.
- To request changes or additions to these process documents, use the [issue template](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) or reference [issue #2](https://github.com/abaddona74-glitch/skills-scale-institutional-knowledge-using-copilot-spaces/issues/2).
- Review these docs during onboarding and refer back to them when establishing new projects or refining existing processes.
