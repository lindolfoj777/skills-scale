# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies.

## Risk Register
Maintain a simple table with:
- ID
- Description
- Impact (High/Med/Low)
- Likelihood (High/Med/Low)
- Owner
- Mitigation plan
- Status

## Risk Lifecycle
- Identify: during planning and ongoing execution
- Assess: estimate impact and likelihood
- Mitigate: reduced via actions, contingency plans
- Monitor: review at weekly syncs and update status

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support)
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status

## Communication Templates

### Weekly Status Template
Use this for regular project updates to stakeholders:

```markdown
## Weekly Status Report — [Project Name]
**Week of:** [Date]
**Project Manager:** [Name]

### Progress This Week
- ✅ [Completed item 1]
- ✅ [Completed item 2]
- ✅ [Completed item 3]

### Next Week's Focus
- 🎯 [Planned item 1]
- 🎯 [Planned item 2]

### Risks & Blockers
| Risk | Impact | Status | Owner | Mitigation |
|------|--------|--------|-------|------------|
| [Risk 1] | High/Med/Low | Open/Mitigated | [Name] | [Plan] |

### Decisions Needed
- ❓ [Decision 1] - needed by [date]

### Asks / Actions Required
- [ ] [Action 1] - [Stakeholder] by [date]
```

For full template details, see [Templates & Checklists](octoacme-templates-and-checklists.md#weekly-status-update-template).

---

### Incident Communication

**Initial Alert:**
```
Subject: [INCIDENT] [Severity] - [Brief Description]

Status: INVESTIGATING
Affected: [Systems/Users impacted]
Actions: [Current mitigation steps]
Next Update: [Time]
```

**Resolution Message:**
```
Subject: [RESOLVED] - [Brief Description]

Status: RESOLVED
Duration: [Total time]
Summary: [What happened and resolution]
Next Steps: [Post-incident review scheduled]
```

For full incident communication templates, see [Templates & Checklists](octoacme-templates-and-checklists.md#incident-communication-template).

---

### Decision Log Template
Track important decisions to maintain organizational memory:

```markdown
## Decision Log — [Project Name]

| Date | Decision | Context | Alternatives Considered | Decision Maker | Status |
|------|----------|---------|------------------------|----------------|--------|
| [Date] | [What was decided] | [Why it mattered] | [Other options] | [Who decided] | Active/Superseded |
```

Benefits:
- New team members understand historical context
- Avoid relitigating past decisions
- Support future retrospectives and process improvements

## Escalation Paths

Clear escalation procedures ensure issues are addressed at the appropriate level with minimal delay.

### Tiered Escalation Model

**Level 1: Team-Level Resolution (Target: Same day)**
- **When:** Day-to-day blockers, technical questions, minor risks
- **Who:** Team members, tech leads, scrum master
- **Action:** Triage in daily standup, pair programming, quick team sync
- **Examples:** Code review delays, environment issues, clarification needed

**Level 2: Project Manager / Product Lead (Target: 1-2 days)**
- **When:** Cross-team dependencies, scope clarifications, resource constraints
- **Who:** Project Manager escalates to Product Lead or dependent team leads
- **Action:** Schedule alignment meeting, update risk register, adjust timeline
- **Examples:** Dependency delays, unclear requirements, capacity issues

**Level 3: Executive Sponsor / Leadership (Target: 3-5 days)**
- **When:** Business-impacting issues, budget needs, organizational blockers
- **Who:** Product Lead or Project Manager escalates to executive sponsor
- **Action:** Executive decision, resource reallocation, strategic pivot
- **Examples:** Major timeline slips, budget overruns, strategic conflicts

### Security and Compliance Escalation
**Special Handling:** Security incidents and compliance issues follow dedicated runbooks
- **Immediate:** Notify Security on-call via [defined channel]
- **Follow:** Organization-specific security incident response procedures
- **Document:** All actions taken for audit and compliance purposes

### Escalation Communication Template
```
Subject: ESCALATION: [Brief Issue Description]

Priority: High / Medium / Low
Escalation Level: 1 / 2 / 3

Issue Summary:
[Clear description of the problem]

Business Impact:
[What's at stake - timeline, budget, customer impact]

Attempted Resolutions:
[What we've tried so far]

Decision Needed:
[Specific ask or question]

Timeline:
[When decision is needed and why]

Raised By: [Name]
Escalated To: [Name/Role]
Date: [Date]
```

---

## Stakeholder Communication

Effective stakeholder communication builds trust and ensures alignment.

### Stakeholder Mapping
Identify stakeholders and their communication needs:

| Stakeholder Group | Interest | Communication Frequency | Preferred Channel | Key Info Needed |
|-------------------|----------|------------------------|-------------------|-----------------|
| Executive Sponsors | Strategic outcomes, ROI | Monthly or milestone-based | Executive summary email | High-level progress, risks, decisions |
| Product Leadership | Feature delivery, roadmap | Weekly | Status report, sync meeting | Progress, blockers, scope changes |
| Engineering Teams | Technical details, dependencies | Daily/Weekly | Standup, Slack, project board | Technical blockers, integration points |
| Sales/Marketing | Feature availability, messaging | Milestone-based | Email, demo sessions | Release dates, capabilities, positioning |
| Support/Success | User impact, troubleshooting | Release-based | Release notes, training | Changes, known issues, documentation |
| End Users | Feature availability, experience | Release-based | Release notes, in-app notifications | New capabilities, how to use, benefits |

### Communication Cadence Best Practices
- **Consistency:** Send updates on the same day/time each week
- **Brevity:** Keep updates concise; link to details for those who want more
- **Actionability:** Clearly state what you need from stakeholders
- **Transparency:** Share both good news and challenges honestly
- **Follow-through:** Track commitments and report on them in next update


