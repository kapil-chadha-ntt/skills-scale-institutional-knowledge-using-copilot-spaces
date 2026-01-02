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

## Release Manager

### Role Summary
Release Manager owns the release planning and execution process, ensuring all release criteria are met, coordinating cross-functional teams, and communicating release status to stakeholders.

### Responsibilities
- Own the end-to-end release planning and execution process
- Ensure all release criteria (testing, documentation, approvals) are met before deployment
- Coordinate with Engineering, QA Lead, DevOps Engineer, and stakeholders to confirm readiness
- Communicate release status, timelines, and risks to Project Manager and stakeholders
- Manage release schedules and coordinate release windows
- Maintain release documentation and post-release reports
- Address release blockers and escalate critical issues

### Goals
- Deliver high-quality releases on schedule with minimal disruption
- Ensure smooth coordination between development, QA, and operations
- Maintain clear visibility into release readiness and risks
- Minimize production incidents related to releases

### Typical Communication
- Daily sync with QA Lead and DevOps Engineer during release cycles
- Weekly release planning meetings with Project Manager
- Release readiness reviews with stakeholders
- Post-release retrospectives and incident reports

### Key Interactions
- **Project Manager**: Aligns on release timelines, communicates risks and dependencies
- **QA Lead**: Confirms test completion and quality gates
- **DevOps Engineer**: Coordinates deployment execution and monitors production health
- **Stakeholder Manager**: Provides release updates and manages external communications
- **Developers**: Reviews feature readiness and addresses release blockers

---

## QA Lead

### Role Summary
QA Lead oversees all testing and quality assurance activities, ensuring products meet quality standards before release. They coordinate test planning, execution, and defect management across the team.

### Responsibilities
- Define test strategy and quality gates for projects
- Coordinate test planning and test case development
- Oversee test execution across functional, integration, and regression testing
- Track and prioritize bug resolution with Development team
- Maintain test documentation and test automation frameworks
- Report quality metrics and testing progress
- Identify quality risks early and recommend mitigation strategies

### Goals
- Ensure product quality meets defined standards before release
- Maximize test coverage while optimizing testing efficiency
- Reduce defect escape rate to production
- Foster a quality-first culture within the team

### Typical Communication
- Daily standups with Development team
- Weekly quality reviews with Release Manager and Project Manager
- Bug triage meetings with Developers
- Test status updates in sprint reviews

### Key Interactions
- **Developers**: Collaborates on test design, reports bugs, verifies fixes
- **Release Manager**: Provides test completion status and quality sign-off for releases
- **Product Manager**: Validates acceptance criteria and clarifies requirements
- **DevOps Engineer**: Coordinates test environment setup and test automation integration
- **Project Manager**: Reports testing progress and quality risks

---

## Stakeholder Manager

### Role Summary
Stakeholder Manager serves as the primary interface between the project team and external/internal stakeholders. They manage expectations, gather feedback, communicate project status, and escalate concerns to ensure stakeholder alignment.

### Responsibilities
- Identify and engage key stakeholders throughout the project lifecycle
- Manage stakeholder expectations and communication plans
- Gather requirements, feedback, and concerns from stakeholders
- Communicate project status, milestones, and risks to stakeholders
- Facilitate stakeholder reviews and approval processes
- Escalate critical stakeholder concerns to Project Manager
- Maintain stakeholder relationship and satisfaction

### Goals
- Ensure stakeholder alignment and satisfaction throughout the project
- Minimize surprises and manage expectations proactively
- Gather timely feedback to inform project decisions
- Build strong stakeholder relationships and trust

### Typical Communication
- Weekly stakeholder updates and newsletters
- Monthly steering committee meetings
- Ad-hoc stakeholder briefings and demos
- Feedback collection surveys and interviews

### Key Interactions
- **Project Manager**: Coordinates on project status, timelines, and escalations
- **Product Manager**: Aligns on product vision and gathers user requirements
- **Release Manager**: Communicates release schedules and impacts to stakeholders
- **Agile Coach**: Collaborates on stakeholder engagement strategies
- **Developers**: Facilitates technical discussions with technical stakeholders

---

## DevOps Engineer

### Role Summary
DevOps Engineer maintains and improves the CI/CD pipelines, infrastructure automation, and deployment systems. They enable rapid, reliable software delivery through automation and monitoring.

### Responsibilities
- Design, implement, and maintain CI/CD pipelines
- Automate infrastructure provisioning and configuration management
- Monitor application and infrastructure health
- Implement security best practices in deployment processes
- Troubleshoot deployment and infrastructure issues
- Optimize build and deployment performance
- Support Release Manager with deployment execution

### Goals
- Enable fast, reliable, and automated software delivery
- Minimize deployment failures and rollback incidents
- Improve infrastructure reliability and observability
- Reduce manual deployment effort through automation

### Typical Communication
- Daily coordination with Developers on pipeline issues
- Weekly infrastructure planning with Project Manager
- Release planning sessions with Release Manager
- Post-incident reviews and retrospectives

### Key Interactions
- **Developers**: Supports with CI/CD pipeline usage, troubleshoots build issues
- **Release Manager**: Executes deployments and provides production readiness assessment
- **QA Lead**: Maintains test environments and integrates automated testing
- **Project Manager**: Reports infrastructure capacity and deployment risks
- **Agile Coach**: Participates in process improvement for delivery automation

---

## Agile Coach

### Role Summary
Agile Coach guides the team in adopting and improving agile practices. They facilitate key ceremonies, remove impediments, and foster a culture of continuous improvement and collaboration.

### Responsibilities
- Coach team members on agile principles and practices
- Facilitate agile ceremonies (standups, retrospectives, planning)
- Identify and help remove team impediments and blockers
- Foster continuous improvement and learning culture
- Mentor Project Manager and team leads on agile leadership
- Track and visualize team metrics (velocity, cycle time, etc.)
- Facilitate cross-team collaboration and alignment

### Goals
- Improve team effectiveness and delivery predictability
- Build self-organizing, high-performing teams
- Increase transparency and collaboration across roles
- Drive continuous process improvement

### Typical Communication
- Daily standup facilitation
- Bi-weekly retrospectives and iteration planning
- Weekly coaching sessions with team members
- Monthly agile maturity assessments

### Key Interactions
- **Project Manager**: Partners on project planning and risk management approaches
- **All Team Members**: Provides coaching, facilitates ceremonies, removes impediments
- **Developers**: Coaches on technical practices (TDD, pair programming, code review)
- **Stakeholder Manager**: Collaborates on stakeholder engagement in agile ceremonies
- **Product Manager**: Supports backlog refinement and prioritization processes

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- The expanded set of roles provides clearer accountability and better coverage of project management activities.
- Cross-role interactions defined above help identify handoff points and collaboration needs.

