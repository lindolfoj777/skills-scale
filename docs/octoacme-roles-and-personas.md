# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## QA/Testing Specialists

### Role Summary
QA/Testing Specialists ensure quality standards are met throughout the development lifecycle. They design test strategies, execute test plans, and validate that features meet acceptance criteria before release.

### Responsibilities
- Design comprehensive test plans and test cases
- Execute manual and automated testing across different environments
- Validate features against acceptance criteria
- Report defects with clear reproduction steps and severity assessment
- Collaborate with developers on testability and quality improvements
- Maintain test automation frameworks and scripts
- Perform regression testing before releases

### Goals
- Ensure high product quality and reliability
- Catch defects early in the development cycle
- Reduce production incidents through thorough testing
- Improve test coverage and automation efficiency

### Typical Communication
- Daily standup updates on testing progress and blockers
- Test result reports and defect tracking updates
- Pre-release sign-off and quality gate reviews
- Test plan reviews with Product and Engineering teams
- Handoff meetings with developers for feature testing

### Key Handoff Points
- **From Product Manager**: Receive feature specs and acceptance criteria during planning
- **From Developers**: Get feature implementation details and test environments during development
- **To Release Manager**: Provide test results and quality sign-off before deployment
- **To Support Teams**: Share known issues and workarounds post-release

---

## UX Designers

### Role Summary
UX Designers create intuitive, user-centered experiences by conducting research, designing interfaces, and validating solutions with users. They ensure products are accessible, usable, and aligned with user needs.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, prototypes, and high-fidelity designs
- Develop and maintain design systems and style guides
- Collaborate with Product Managers on feature requirements
- Work with Developers to ensure design implementation fidelity
- Validate designs through user feedback and analytics
- Ensure accessibility standards (WCAG) are met

### Goals
- Deliver delightful, intuitive user experiences
- Reduce user friction and support requests
- Maintain design consistency across products
- Validate designs with real user data

### Typical Communication
- Design reviews with Product and Engineering teams
- User research readouts and usability testing reports
- Design specs and component documentation
- Collaboration sessions during feature planning
- Implementation review during development sprints

### Key Handoff Points
- **From Product Manager**: Receive problem statements and user stories during initiation
- **To Developers**: Deliver design specs, assets, and interaction patterns
- **To Technical Writers**: Share UI flows and terminology for documentation
- **From QA**: Receive feedback on UI/UX bugs and accessibility issues
- **To Stakeholders**: Present design concepts and user research insights

---

## Technical Writers

### Role Summary
Technical Writers create clear, accurate documentation that helps users and developers understand and use products effectively. They collaborate across teams to ensure documentation stays current and accessible.

### Responsibilities
- Write and maintain user documentation, API references, and guides
- Create tutorials, how-to articles, and troubleshooting content
- Collaborate with Product and Engineering to understand features
- Review and edit technical content for clarity and accuracy
- Maintain documentation style guides and standards
- Ensure documentation is versioned and synchronized with releases
- Gather user feedback to improve documentation quality

### Goals
- Enable users to self-serve through clear documentation
- Reduce support burden by anticipating common questions
- Maintain documentation accuracy and consistency
- Improve documentation discoverability and usability

### Typical Communication
- Feature review meetings with Product and Engineering
- Documentation planning during sprint planning
- Content reviews with subject matter experts
- Release coordination meetings for documentation updates
- User feedback analysis and content improvement plans

### Key Handoff Points
- **From Product Manager**: Receive feature descriptions and user personas during planning
- **From UX Designer**: Get UI flows, terminology, and user journey maps
- **From Developers**: Obtain technical details, API specs, and code examples
- **To QA**: Provide documentation for testing and validation
- **To Release Manager**: Deliver release notes and updated documentation
- **To Support Teams**: Share documentation updates and known limitations

---

## Release/Deployment Managers

### Role Summary
Release/Deployment Managers orchestrate the safe and efficient delivery of software to production environments. They coordinate release activities, manage deployment risks, and ensure rollback procedures are in place.

### Responsibilities
- Plan and schedule release windows and deployment activities
- Coordinate cross-team dependencies for releases
- Manage release checklists and deployment runbooks
- Monitor deployments and validate post-deployment health
- Execute rollback procedures when necessary
- Maintain release calendars and version tracking
- Communicate release status to stakeholders
- Conduct release retrospectives to improve processes

### Goals
- Achieve zero-downtime deployments
- Minimize production incidents related to releases
- Reduce time from code-complete to production
- Maintain clear release visibility for all stakeholders

### Typical Communication
- Pre-release coordination meetings with Engineering and QA
- Deployment status updates during release windows
- Post-deployment reports to stakeholders
- Release planning sessions with Product and Project Managers
- Incident response communication during deployment issues

### Key Handoff Points
- **From QA**: Receive test results and quality sign-off before release
- **From Developers**: Get deployment scripts, configuration changes, and migration plans
- **From Technical Writers**: Ensure release notes and documentation are ready
- **From Product Manager**: Confirm feature flags and rollout strategy
- **To Support Teams**: Provide release notes, known issues, and escalation contacts
- **To Operations**: Coordinate infrastructure changes and monitoring setup

---

---

## Cross-Role Collaboration Matrix

Understanding how roles interact is crucial for smooth project execution. This matrix outlines key collaboration points:

### Project Initiation Phase
| From → To | Communication Need | Frequency |
|-----------|-------------------|-----------|
| Product Manager → All Roles | Project vision, goals, success metrics | Kickoff meeting |
| Project Manager → All Roles | Timeline, milestones, team structure | Kickoff meeting |
| UX Designer → Product Manager | User research insights, design constraints | Initial planning |
| Developers → Project Manager | Technical feasibility, effort estimates | Planning sessions |

### Planning Phase
| From → To | Communication Need | Frequency |
|-----------|-------------------|-----------|
| Product Manager → UX Designer | User stories, acceptance criteria | Sprint planning |
| UX Designer → Developers | Design specs, prototypes, assets | Sprint planning |
| Project Manager → QA | Test planning requirements, timeline | Sprint planning |
| Technical Writer → Product Manager | Documentation scope and priorities | Sprint planning |

### Execution Phase
| From → To | Communication Need | Frequency |
|-----------|-------------------|-----------|
| Developers → QA | Feature readiness, test environments | Daily/As needed |
| UX Designer → Developers | Design clarifications, implementation review | Daily/As needed |
| Developers → Technical Writer | Feature details, API changes, technical specs | Per feature |
| All → Project Manager | Progress updates, blockers, risks | Daily standup |
| QA → Developers | Bug reports, test results | Continuous |

### Release Phase
| From → To | Communication Need | Frequency |
|-----------|-------------------|-----------|
| QA → Release Manager | Test completion status, quality sign-off | Pre-release |
| Developers → Release Manager | Deployment procedures, rollback plans | Pre-release |
| Technical Writer → Release Manager | Release notes, documentation updates | Pre-release |
| Release Manager → All Stakeholders | Release status, deployment schedule | Release window |
| Release Manager → Support Teams | Release notes, known issues, contacts | Post-release |

### Retrospective Phase
| From → To | Communication Need | Frequency |
|-----------|-------------------|-----------|
| All Roles → Project Manager | Learnings, improvement suggestions | Post-sprint/release |
| Project Manager → All Roles | Action items, process improvements | Post-retrospective |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the Cross-Role Collaboration Matrix to understand communication patterns and handoff points.

