# Role Handoff Checklist

## Purpose
This checklist ensures smooth transitions between project phases and clear handoffs between roles. Use it to minimize information loss, reduce delays, and maintain accountability during critical project transitions.

---

## Developer → QA Lead Handoff

**Context**: Feature implementation is complete and ready for testing

### Developer Responsibilities
- [ ] All acceptance criteria implemented and documented in PR
- [ ] Unit tests written and passing
- [ ] Code reviewed and approved by peers
- [ ] Feature deployed to test environment
- [ ] Known limitations or edge cases documented
- [ ] Test data or setup instructions provided
- [ ] Notify QA Lead that feature is ready for testing

### QA Lead Responsibilities  
- [ ] Review acceptance criteria and clarify any ambiguities with Product Manager
- [ ] Confirm test environment is accessible and stable
- [ ] Acknowledge handoff and provide testing timeline
- [ ] Document any blocking issues discovered during initial review

**Success Criteria**: QA Lead can begin testing without waiting for additional information or access

---

## QA Lead → Release Manager Handoff

**Context**: Testing is complete and quality gates are met

### QA Lead Responsibilities
- [ ] All test cases executed and results documented
- [ ] Critical and high-priority bugs resolved
- [ ] Regression testing completed
- [ ] Test summary report prepared (pass/fail rates, coverage, risks)
- [ ] Quality sign-off provided or blockers clearly documented
- [ ] Known issues documented in release notes
- [ ] Notify Release Manager of test completion status

### Release Manager Responsibilities
- [ ] Review test summary and quality metrics
- [ ] Confirm all release criteria are met
- [ ] Acknowledge any known issues and assess risk
- [ ] Update release plan with final go/no-go decision
- [ ] Notify stakeholders of release readiness

**Success Criteria**: Release Manager has complete quality visibility to make informed release decisions

---

## Release Manager → DevOps Engineer Handoff

**Context**: Release is approved and ready for deployment

### Release Manager Responsibilities
- [ ] Release approved by stakeholders and quality gates met
- [ ] Deployment window scheduled and communicated
- [ ] Release notes finalized and reviewed
- [ ] Rollback plan documented and reviewed
- [ ] Notify DevOps Engineer to begin deployment
- [ ] Confirm availability for monitoring during deployment

### DevOps Engineer Responsibilities
- [ ] Verify deployment pipeline is ready and tested
- [ ] Confirm backup/snapshot procedures completed (if applicable)
- [ ] Execute deployment according to release plan
- [ ] Run post-deployment smoke tests
- [ ] Monitor system health and performance metrics
- [ ] Notify Release Manager of deployment status (success/failure)
- [ ] Document any deployment issues or deviations

**Success Criteria**: Deployment executes smoothly with minimal surprises and clear status communication

---

## Project Manager → Stakeholder Manager Handoff

**Context**: Project status or major milestone requires stakeholder communication

### Project Manager Responsibilities
- [ ] Project status summary prepared (progress, risks, timeline)
- [ ] Key decisions or changes documented
- [ ] Stakeholder impact assessment completed
- [ ] Supporting materials ready (dashboards, demos, metrics)
- [ ] Provide Stakeholder Manager with communication timing needs
- [ ] Brief Stakeholder Manager on sensitive topics or concerns

### Stakeholder Manager Responsibilities
- [ ] Review project status and clarify any questions
- [ ] Identify target stakeholder audience and communication channels
- [ ] Draft stakeholder communication (email, presentation, demo)
- [ ] Coordinate timing with Project Manager
- [ ] Deliver communication and gather feedback
- [ ] Report stakeholder feedback and concerns back to Project Manager

**Success Criteria**: Stakeholders receive timely, accurate information and Project Manager gets actionable feedback

---

## Agile Coach → Project Manager Handoff

**Context**: Sprint/iteration completion and planning for next cycle

### Agile Coach Responsibilities
- [ ] Facilitate retrospective and document outcomes
- [ ] Identify process improvement actions with owners
- [ ] Calculate team velocity and performance metrics
- [ ] Highlight team impediments requiring PM attention
- [ ] Share team health and morale observations
- [ ] Recommend any changes to project structure or cadence

### Project Manager Responsibilities
- [ ] Review retrospective outcomes and improvement actions
- [ ] Integrate velocity data into project timeline updates
- [ ] Address escalated impediments or resource needs
- [ ] Adjust project plan based on team feedback
- [ ] Support implementation of process improvements
- [ ] Provide update on external dependencies or project changes

**Success Criteria**: Project plans reflect team reality and process improvements are actioned

---

## Product Manager → Developers Handoff

**Context**: New feature or story ready for implementation

### Product Manager Responsibilities
- [ ] User story written with clear problem statement
- [ ] Acceptance criteria defined and unambiguous
- [ ] User flows or mockups provided (if applicable)
- [ ] Success metrics identified
- [ ] Dependencies and constraints documented
- [ ] Available for questions during implementation
- [ ] Prioritization and deadline communicated clearly

### Developer Responsibilities
- [ ] Review story and acceptance criteria
- [ ] Ask clarifying questions before starting work
- [ ] Confirm technical feasibility and flag concerns early
- [ ] Provide effort estimate with confidence level
- [ ] Agree on definition of done
- [ ] Notify PM of any scope changes or blockers during development

**Success Criteria**: Developers have clear requirements and can start work without delays or rework

---

## Stakeholder Manager → Product Manager Handoff

**Context**: Stakeholder feedback or new requirements gathered

### Stakeholder Manager Responsibilities
- [ ] Stakeholder feedback organized by theme or priority
- [ ] Context provided (which stakeholders, when, why)
- [ ] Urgency and business impact assessed
- [ ] Conflicting feedback or trade-offs highlighted
- [ ] Schedule meeting with Product Manager to review
- [ ] Follow up on any stakeholder commitments or questions

### Product Manager Responsibilities
- [ ] Review feedback and ask clarifying questions
- [ ] Analyze feedback against product vision and roadmap
- [ ] Make prioritization decisions and communicate rationale
- [ ] Update roadmap or backlog as needed
- [ ] Provide response for Stakeholder Manager to share back
- [ ] Thank Stakeholder Manager and set expectations for next touchpoint

**Success Criteria**: Stakeholder input is incorporated into product decisions with clear communication loop

---

## General Handoff Best Practices

### Before the Handoff
1. **Prepare materials**: Ensure all documentation, artifacts, and context are ready
2. **Schedule time**: Don't rush critical handoffs - allow time for questions
3. **Notify early**: Give the recipient advance notice to prepare
4. **Check dependencies**: Ensure upstream work is actually complete

### During the Handoff
1. **Use a checklist**: Work through items systematically
2. **Confirm understanding**: Ask recipient to summarize key points
3. **Document decisions**: Capture any changes or agreements made
4. **Identify risks**: Explicitly call out uncertainties or concerns

### After the Handoff
1. **Follow up**: Check in after a reasonable time to ensure progress
2. **Stay available**: Be responsive to questions during the transition
3. **Track completion**: Monitor that handoff items are acted upon
4. **Learn and improve**: Update checklist based on what worked/didn't work

---

## Handoff Red Flags

Watch for these warning signs that indicate handoff problems:

- **Repeated questions**: Same information requested multiple times
- **Rework**: Work redone because requirements weren't clear
- **Delays**: Work stalls waiting for information or access
- **Blame**: Finger-pointing about who should have done what
- **Surprises**: Issues discovered that should have been flagged earlier

If you see these patterns, revisit the handoff process and clarify responsibilities using the [Role Responsibility Matrix](./templates-role-responsibility-matrix.md).

---

## Benefits of Effective Handoffs

- **Reduced delays**: Work continues smoothly without waiting
- **Better quality**: Complete information leads to better execution
- **Clear accountability**: No confusion about who owns what
- **Knowledge retention**: Critical context isn't lost in transitions
- **Team trust**: Reliable handoffs build confidence between roles
- **Faster onboarding**: New team members learn the collaboration flow

---

**Related Documents:**
- [OctoAcme Roles and Personas](./octoacme-roles-and-personas.md)
- [Role Responsibility Matrix](./templates-role-responsibility-matrix.md)
- [OctoAcme Project Management Overview](./octoacme-project-management-overview.md)
- [OctoAcme Execution and Tracking](./octoacme-execution-and-tracking.md)
