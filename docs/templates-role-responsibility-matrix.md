# Role Responsibility Matrix (RACI)

## Purpose
This template helps teams clarify accountability and decision-making authority across project activities. Use this matrix to identify who is Responsible, Accountable, Consulted, and Informed for each key activity.

## RACI Definitions
- **Responsible (R)**: Person(s) who perform the work to complete the task
- **Accountable (A)**: Person who is ultimately answerable for the correct completion (only one per activity)
- **Consulted (C)**: People whose opinions are sought; two-way communication
- **Informed (I)**: People who are kept up-to-date; one-way communication

---

## Sample RACI Matrix for OctoAcme Projects

| Activity / Deliverable | Project Manager | Product Manager | Developer | QA Lead | Release Manager | DevOps Engineer | Stakeholder Manager | Agile Coach |
|------------------------|----------------|-----------------|-----------|---------|----------------|----------------|-----------------------|-------------|
| **Project Initiation** |
| Define problem statement | C | A/R | C | - | - | - | I | C |
| Identify stakeholders | R | C | - | - | - | - | A | C |
| Create project charter | A/R | C | C | - | - | - | C | I |
| **Planning** |
| Create project timeline | A/R | C | C | C | C | C | I | C |
| Define acceptance criteria | C | A/R | C | C | - | - | I | - |
| Estimate work effort | C | I | A/R | C | - | C | - | C |
| Identify dependencies | A/R | C | C | C | C | C | I | I |
| **Execution** |
| Implement features | I | I | A/R | C | - | C | - | I |
| Write tests | C | I | R | A | - | C | - | I |
| Code review | I | I | A/R | C | - | C | - | I |
| Bug triage | I | C | R | A | - | - | - | I |
| Daily standups | R | I | R | R | I | R | - | A |
| **Quality Assurance** |
| Test planning | C | C | C | A/R | C | - | - | I |
| Test execution | I | I | C | A/R | - | C | - | - |
| Quality sign-off | I | I | I | R | A | - | I | - |
| **Release** |
| Release planning | C | C | C | C | A/R | C | I | I |
| Deployment execution | I | I | I | I | R | A/R | - | - |
| Smoke testing | I | I | C | R | R | C | - | - |
| Release communication | I | I | - | - | R | - | A | - |
| Production monitoring | I | I | I | I | R | A/R | - | - |
| **Communication** |
| Status reporting | A/R | C | I | I | I | I | C | C |
| Stakeholder updates | C | C | - | - | C | - | A/R | I |
| Risk escalation | A/R | C | I | I | C | I | C | C |
| **Continuous Improvement** |
| Facilitate retrospectives | C | I | R | R | R | R | I | A |
| Track action items | A/R | I | I | I | I | I | I | C |
| Process improvements | C | C | C | C | C | C | I | A/R |

---

## How to Use This Template

1. **Customize for your project**: Copy this matrix and adjust activities based on your specific project needs
2. **Review with the team**: Walk through the matrix in kickoff or planning meetings to ensure clarity
3. **Identify gaps**: Look for activities with:
   - No Accountable person (must have exactly one)
   - Too many Responsible parties (consider splitting the activity)
   - Missing Consulted/Informed parties (ensure proper communication)
4. **Update as needed**: Revisit the matrix when roles change or new activities emerge
5. **Use in onboarding**: Share with new team members to quickly clarify responsibilities

## Benefits of Clear Role Assignment

- **Eliminates ambiguity**: Everyone knows who owns what
- **Prevents duplication**: Clear Responsible parties avoid redundant effort
- **Improves accountability**: Single Accountable person for each deliverable
- **Enhances communication**: Explicit Consulted/Informed parties ensure proper information flow
- **Speeds up decisions**: Clear authority enables faster resolution
- **Supports scaling**: New team members can quickly understand their role

## Tips for Success

- Keep the Accountable role singular - one person is ultimately answerable
- Don't over-consult - too many "C"s slow down work
- Be specific about activities - vague descriptions lead to confusion
- Review quarterly - roles and responsibilities evolve with the team
- Link to persona descriptions in [octoacme-roles-and-personas.md](./octoacme-roles-and-personas.md)

---

**Related Documents:**
- [OctoAcme Roles and Personas](./octoacme-roles-and-personas.md)
- [OctoAcme Project Management Overview](./octoacme-project-management-overview.md)
- [Role Handoff Checklist](./templates-role-handoff-checklist.md)
