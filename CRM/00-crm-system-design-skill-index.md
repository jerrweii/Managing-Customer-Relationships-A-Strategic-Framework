# CRM System Design Skill Index

## Purpose

Use this index to choose the right CRM design skill for a software development problem.

## System Backbone

The reusable CRM architecture pattern is:

```text
Customer Strategy
-> IDIC: Identify, Differentiate, Interact, Customize
-> Trust and Data Stewardship
-> Learning Relationship
-> Customer Value Metrics
-> Enterprise Governance
```

## Feature Classification Checklist

For any CRM feature, ask whether it supports one or more of these capabilities:

- Identifies the customer accurately.
- Differentiates customers by value.
- Differentiates customers by need.
- Improves customer interaction.
- Customizes treatment or service.
- Strengthens trust and consent.
- Measures customer value over time.
- Helps employees make better customer decisions.
- Governs customer-level decisions across teams.

If a feature supports none of these, it is probably adjacent tooling rather than core CRM.

## Recommended Module Map

- Identity Service: recognition, deduplication, profile merge.
- Customer Profile: unified customer memory.
- Consent and Trust Layer: privacy, permissions, auditability.
- Interaction Timeline: dialogue, touchpoints, feedback.
- Customer Value Engine: LTV, potential value, referral value, cost-to-serve.
- Needs and Preferences Model: goals, jobs, preferences, intent.
- Decision Engine: next best action, routing, offer, treatment.
- Analytics Layer: customer equity, churn, retention, portfolio movement.
- Employee Workspace: actionable context and workflows.
- Governance Layer: ownership, rules, approvals, accountability.

## Review Question

Does the design help the company build enterprise value by building customer value?

