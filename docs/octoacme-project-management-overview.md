# OctoAcme Project Management Overview

## Purpose
Provide a concise, shareable introduction to how OctoAcme runs projects so new teammates can quickly understand our approach, roles, key artifacts, and decision-making model.

## Scope
Applies to all cross-functional projects that deliver product features, services, or integrations.

## Principles
- Customer-first: prioritize customer value and usability.
- Iterative delivery: deliver small, testable increments.
- Clear ownership: each project has named roles with explicit accountability for outcomes, handoffs, and escalation paths.
- Data-informed decisions: measure impact and iterate based on evidence.
- Psychological safety: encourage feedback and learning.

## Core Roles
- Project Manager (PM): coordinates delivery, schedules, risk, communications, and dependencies across the team.
- Product Manager (PdM): defines outcomes, prioritizes backlog, validates user value, and measures success.
- Developers: implement features, collaborate on design and testability, and own technical quality for their work.
- QA / Test Lead: validates quality, acceptance criteria, and release readiness across unit, integration, and smoke test layers.
- UX / Research Partner: ensures user needs, usability, and accessibility remain central to delivery decisions.
- Security / Compliance Lead: reviews security, privacy, and regulatory risks and advises on controls and mitigations.
- Release Manager / Enablement Lead: coordinates rollout readiness, stakeholder communication, and operational support for launch.
- Customer Success / Support Liaison: surfaces customer feedback, escalation trends, and support impacts that should influence backlog and release decisions.
- Data / Analytics Lead: defines metrics, instrumentation, and reporting needed to measure outcomes and monitor success after release.
- Stakeholders: provide input, approval, and sponsorship needed to maintain alignment and priorities.

## Accountability Model
Clear ownership reduces ambiguity and prevents handoff gaps. In OctoAcme, ownership is split by work type instead of being assumed to be the same for every project activity.

- Product Manager owns the problem definition, roadmap priority, and success metrics.
- Project Manager owns the plan, timeline, risk register, meeting cadence, and communication flow.
- Developers own implementation quality, technical estimates, testing for changed code, and issue triage within the sprint.
- QA owns validation strategy, regression risk, and release-readiness decisions.
- Security and Compliance own risk review, controls, and policy alignment for sensitive work.
- UX / Research owns user experience quality and evidence-based product decisions.
- Release Manager owns rollout coordination, operational readiness, and post-release support handoff.
- Customer Success / Support owns real-world feedback and service impact signals.
- Data / Analytics owns measurement and reporting so decisions remain evidence-based.

## Key Artifacts
- Project Charter / One-pager
- Roadmap and Release Plan
- Sprint/Iteration Backlog
- Acceptance Criteria & Definition of Done
- Risk Register
- Retrospective notes and action items
- Role ownership and dependency map

## Lifecycle (high-level)
1. Initiation: problem statement, stakeholders, high-level timeline.
2. Planning: scope, resources, milestones, dependencies, and role ownership.
3. Execution: build, test, review, iterate, and escalate blockers early.
4. Release: deploy, verify, announce, and monitor readiness.
5. Close & Retrospective: capture learnings and next steps.

## Communication Cadence
- Weekly sync between PM + PdM
- Twice-weekly standups for delivery team (or as agreed)
- Monthly stakeholder updates
- Ad-hoc escalations as needed
- Cross-functional review checkpoints for QA, security, UX, and release readiness when relevant

## Escalation and Handoffs
- Team-level issues are triaged in standups or working sessions.
- PM coordinates cross-team communication and escalation when dependencies block progress.
- Product and leadership are engaged for scope, priority, or customer-impact decisions.
- Security, QA, or release concerns are raised before a milestone or deployment to reduce last-minute risk.

## How to use these docs
- Keep the Project Charter updated in the project repo.
- Define clear owners for each milestone, dependency, and release gate.
- Use the role guide and accountability checklist to clarify who is responsible for decisions and follow-through.
- Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context.
