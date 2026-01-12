# OctoAcme Roles & Responsibilities Matrix

## Purpose
This matrix clarifies accountability and collaboration patterns across OctoAcme project roles. Use it during project initiation to ensure clear ownership and avoid gaps in responsibilities.

## How to Read This Matrix
- **R** = Responsible (does the work)
- **A** = Accountable (final decision-maker, only one per activity)
- **C** = Consulted (provides input, two-way communication)
- **I** = Informed (kept in the loop, one-way communication)

---

## Project Lifecycle Activities

| Activity | Project Manager | Product Manager | Delivery Manager | Developer | QA Lead | Change Champion | Communications Liaison |
|----------|----------------|-----------------|------------------|-----------|---------|-----------------|----------------------|
| **Initiation & Planning** |
| Define problem statement | C | A | I | I | I | I | I |
| Create project charter | A | C | C | I | I | I | C |
| Identify stakeholders | C | C | I | I | I | C | A |
| Develop communication plan | C | I | I | I | I | C | A |
| Resource allocation | A | C | C | I | I | I | I |
| Risk identification | R | C | C | C | C | I | I |
| **Execution** |
| Sprint/iteration planning | C | C | C | A | C | I | I |
| Feature implementation | I | I | I | A | C | I | I |
| Code review | I | I | C | A | C | I | I |
| Test strategy definition | C | C | C | C | A | I | I |
| Test execution | I | I | I | C | A | I | I |
| Quality sign-off | I | C | I | C | A | I | I |
| Daily standups | C | I | A | R | R | I | I |
| Remove blockers | R | C | A | C | C | I | I |
| **Communication** |
| Stakeholder updates | R | C | C | I | I | I | A |
| Status reporting | A | C | C | I | C | I | C |
| Risk escalation | A | C | C | C | C | I | C |
| Team announcements | C | I | C | I | I | C | A |
| **Quality & Process** |
| Define acceptance criteria | C | A | I | C | C | I | I |
| Test automation strategy | C | I | C | C | A | I | I |
| Quality metrics tracking | C | I | C | C | A | I | I |
| Process improvements | C | C | A | C | C | C | I |
| Retrospective facilitation | C | C | R | C | C | I | I |
| **Release & Deployment** |
| Release planning | A | C | C | C | C | I | C |
| Deployment execution | C | I | C | A | C | I | I |
| Release communication | C | C | I | I | I | C | A |
| Production validation | C | C | C | C | A | I | I |
| Release retrospective | R | C | C | C | C | C | I |
| **Change Management** |
| Change impact assessment | C | C | C | I | I | A | C |
| Training material development | I | I | C | C | I | A | C |
| Adoption tracking | I | C | C | I | I | A | C |
| User support during transition | C | C | C | C | I | R | C |

---

## Key Collaboration Patterns

### Project Manager ↔ Product Manager
- **Frequency**: Weekly 1:1 + planning sessions
- **Focus**: Scope, priorities, trade-offs, stakeholder alignment
- **Artifacts**: Project plans, roadmaps, status reports

### Project Manager ↔ Delivery Manager
- **Frequency**: Weekly syncs + ad-hoc for blockers
- **Focus**: Team capacity, process improvements, cross-team dependencies
- **Artifacts**: Velocity metrics, blocker logs, resource plans

### Delivery Manager ↔ QA Lead
- **Frequency**: Bi-weekly + sprint planning
- **Focus**: Quality processes, test automation, continuous improvement
- **Artifacts**: Test strategies, quality metrics, process improvements

### Change Champion ↔ Communications Liaison
- **Frequency**: Weekly + during change initiatives
- **Focus**: Change messaging, stakeholder engagement, adoption campaigns
- **Artifacts**: Communication plans, training materials, FAQs

### QA Lead ↔ Developers
- **Frequency**: Daily during active development
- **Focus**: Test coverage, defect triage, quality standards
- **Artifacts**: Test plans, defect reports, code review feedback

---

## Using This Matrix

### During Project Initiation
1. Review the matrix with the project team
2. Identify which roles are needed for your specific project
3. Assign named individuals to each role
4. Clarify any custom responsibilities or variations

### During Project Execution
- Reference when unclear about who should make a decision
- Use in retrospectives to identify collaboration gaps
- Update if responsibilities shift during the project

### For Onboarding
- Share with new team members to clarify their role and interactions
- Use as a reference for understanding who to contact for what

---

## Customization Guidelines

This matrix provides a baseline. Adjust based on:
- **Project size**: Smaller projects may combine roles
- **Organizational structure**: Different reporting lines may shift accountability
- **Project type**: Infrastructure vs. product projects may need different patterns
- **Team maturity**: More experienced teams may need less oversight

Document any variations in your project charter or README.
