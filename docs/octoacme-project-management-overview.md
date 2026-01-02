# OctoAcme Project Management Overview

## Purpose
Provide a concise, shareable introduction to how OctoAcme runs projects so new teammates can quickly understand our approach, roles, and key artifacts.

## Scope
Applies to all cross-functional projects that deliver product features, services, or integrations.

## Principles
- Customer-first: prioritize customer value and usability.
- Iterative delivery: deliver small, testable increments.
- Clear ownership: each project has a named Project Manager (PM) and Product Lead.
- Data-informed decisions: measure impact and iterate based on evidence.
- Psychological safety: encourage feedback and learning.

## Core Roles
- **Project Manager (PM)**: Coordinates delivery, schedules, risk, communications.
- **Product Manager (PdM)**: Defines outcomes, prioritizes backlog, and measures success.
- **Developers**: Implement features, collaborate on design and testability.
- **QA Lead**: Oversees test planning, execution, and quality assurance activities.
- **Release Manager**: Owns release planning, coordinates deployments, ensures release readiness.
- **DevOps Engineer**: Maintains CI/CD pipelines, infrastructure automation, and monitoring.
- **Stakeholder Manager**: Manages stakeholder communication, expectations, and feedback.
- **Agile Coach**: Guides agile practices, facilitates ceremonies, drives continuous improvement.

For detailed role descriptions and interactions, see [OctoAcme Roles and Personas](./octoacme-roles-and-personas.md).

## Key Artifacts
- Project Charter / One-pager
- Roadmap and Release Plan
- Sprint/Iteration Backlog
- Acceptance Criteria & Definition of Done
- Risk Register
- Retrospective notes and action items
- [Role Responsibility Matrix (RACI)](./templates-role-responsibility-matrix.md)
- [Role Handoff Checklists](./templates-role-handoff-checklist.md)

## Lifecycle (high-level)
1. Initiation: problem statement, stakeholders, high-level timeline.
2. Planning: scope, resources, milestones, dependencies.
3. Execution: build, test, review, iterate.
4. Release: deploy, verify, announce.
5. Close & Retrospective: capture learnings and next steps.

## Communication Cadence
- Weekly sync between PM + PdM
- Twice-weekly standups for delivery team (or as agreed)
- Monthly stakeholder updates
- Ad-hoc escalations as needed

## How to use these docs
- Keep the Project Charter updated in the project repo.
- Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context.
- Use the [Role Responsibility Matrix](./templates-role-responsibility-matrix.md) to clarify accountability.
- Follow [Role Handoff Checklists](./templates-role-handoff-checklist.md) for smooth transitions between project phases.

## Process Improvements (Issue #4)

The addition of Release Manager, QA Lead, Stakeholder Manager, DevOps Engineer, and Agile Coach roles addresses key gaps in project management:

- **Improved Clarity**: Explicit roles for release coordination, quality oversight, and stakeholder management eliminate ambiguity about who owns critical activities.
- **Enhanced Accountability**: The expanded role set with clear responsibilities ensures no important tasks fall through the cracks.
- **Better Outcomes**: Dedicated focus on quality (QA Lead), deployment (Release Manager, DevOps Engineer), stakeholder alignment (Stakeholder Manager), and continuous improvement (Agile Coach) leads to more successful project delivery.

These enhancements directly address feedback captured in [issue #4](https://github.com/kapil-chadha-ntt/skills-scale-institutional-knowledge-using-copilot-spaces/issues/4).
