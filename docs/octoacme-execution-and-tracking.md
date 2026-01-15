# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies
- Weekly delivery sync — show progress, updates, and flagged risks
- Demo/Review at the end of each sprint or milestone

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)
  - Link to relevant design specs or documentation

### Handoff Procedures
Clear handoffs between roles reduce delays and ensure quality:

**Developer → QA Handoff:**
- Feature complete with passing tests
- Test environment ready and accessible
- Acceptance criteria documented in PR
- Demo or walkthrough provided to QA
- Known limitations communicated
- See [Templates & Checklists](octoacme-templates-and-checklists.md#developer-to-qa-handoff-checklist) for full checklist

**QA → Release Manager Handoff:**
- All test cases executed with results documented
- Critical defects resolved or documented with workarounds
- Quality sign-off provided (Go/No-Go recommendation)
- Release notes reviewed for accuracy
- See [Templates & Checklists](octoacme-templates-and-checklists.md#qa-to-release-manager-handoff-checklist) for full checklist

**Developer → Technical Writer Handoff:**
- Feature overview and use cases explained
- API documentation provided (if applicable)
- Demo environment access granted
- Error scenarios and troubleshooting documented
- See [Templates & Checklists](octoacme-templates-and-checklists.md#developer-to-technical-writer-handoff-checklist) for full checklist

## Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

### Stakeholder Communication
**Weekly Status Updates:**
- Share progress, risks, and blockers using the [Weekly Status Update Template](octoacme-templates-and-checklists.md#weekly-status-update-template)
- Highlight decisions needed and timeline impacts
- Keep updates concise and action-oriented

**Demo/Review Sessions:**
- Show working features, not just slide decks
- Invite stakeholders to provide feedback early
- Document feedback and decisions in meeting notes
- Follow up on action items promptly

**Ad-hoc Updates:**
- For significant blockers or scope changes, don't wait for weekly updates
- Use appropriate channels (email, Slack, direct message) based on urgency
- Be transparent about challenges and proposed solutions

## Blocker Escalation
- Level 1: Team-level triage in daily standup
- Level 2: PM escalates to Product Lead and dependent teams
- Level 3: Sponsor-level escalation for business-impacting issues

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly
