# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — facilitated by Scrum Master, focus on progress, blockers, dependencies
- Weekly delivery sync — show progress, updates, and flagged risks; Data Analyst shares key metrics
- Demo/Review at the end of each sprint or milestone — include UX Designer for usability validation
- Sprint retrospectives — facilitated by Scrum Master to capture improvements

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Scrum Master ensures board is updated and facilitates flow
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests (unit, integration, e2e) and linting in CI before requesting review
  - QA Automation Engineer reviews test coverage and automated test results
  - Require at least one approval before merging (or team-defined policy)
  - UX Designer reviews for design compliance when UI changes are involved

## Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- Automated end-to-end tests for critical user flows (maintained by QA Automation Engineer)
- Automated regression suite runs on every PR
- Performance and load tests for significant features
- Security scanning in CI
- Manual QA for feature acceptance when needed
- UX Designer validates usability for user-facing changes

## Reporting & Metrics
- Track velocity and burndown (maintained by Scrum Master)
- Monitor success metrics identified in the Project One-pager (tracked by Data Analyst)
- Use dashboards for key signals (errors, latency, usage, user behavior)
- Data Analyst provides weekly insights on feature adoption and usage patterns
- QA Automation Engineer reports on test coverage and automation health

## Blocker Escalation
- Level 1: Team-level triage in daily standup, Scrum Master tracks and follows up
- Level 2: Scrum Master escalates to PM, who coordinates with Product Lead and dependent teams
- Level 3: Sponsor-level escalation for business-impacting issues

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests, lint, and security scans
- [ ] Automated test suite configured (unit, integration, e2e)
- [ ] QA Automation Engineer has access to test infrastructure
- [ ] Regular demos scheduled with UX Designer participation
- [ ] Risk register updated weekly
- [ ] Data Analyst has analytics instrumentation in place
- [ ] Scrum Master has established sprint cadence and ceremonies
