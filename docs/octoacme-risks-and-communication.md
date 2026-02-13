# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies. Use the [Risk Review and Escalation Protocol Checklist](templates/risk-review-escalation-checklist.md) for structured risk management.

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
- Identify: during planning and ongoing execution (involve all team members)
- Assess: estimate impact and likelihood (use [Risk Review and Escalation Protocol](templates/risk-review-escalation-checklist.md))
- Mitigate: reduced via actions, contingency plans (assign clear owners)
- Monitor: review at weekly syncs and update status
- Escalate: follow escalation protocol when thresholds are met

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support)
- Use [Stakeholder Communication Planning Checklist](templates/stakeholder-communication-checklist.md) to develop communication plan
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status
- Engage Stakeholder (Customer Advocate) representatives for feedback

## Communication Templates
Weekly Status Template:
- Progress this week:
- Next steps:
- Risks & blockers:
- Ask / decisions needed:

Incident Communication
- Triage summary
- Actions being taken
- Expected timeline
- Post-incident blameless retrospective scheduled

## Escalation Paths
- Team-level -> PM -> Product Lead -> Sponsor
- For security incidents, follow the security incident runbook and notify Security on-call
- For detailed escalation criteria and procedures, see [Risk Review and Escalation Protocol](templates/risk-review-escalation-checklist.md)
- DevOps Engineer should be involved in infrastructure or deployment-related escalations
