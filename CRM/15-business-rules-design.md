# Skill 15: Business Rules Design

## Purpose

Encode customer treatment decisions explicitly so they can be tested, audited, and improved.

## When To Use

- Designing routing, eligibility, offers, escalation, service levels, or automation.
- Replacing hard-coded CRM logic.

## Inputs

- Policy decisions.
- Customer segments.
- Value and needs data.
- Compliance constraints.
- Workflow outcomes.

## Repeatable Steps

1. Separate decision logic from workflow plumbing.
2. Name each rule and its business owner.
3. Define inputs, outputs, priority, and conflict handling.
4. Version rules and log decisions.
5. Test rules with representative customer scenarios.

## Software Artifacts

- Decision tables.
- Rules engine.
- Eligibility API.
- Rule version history.
- Scenario test suite.

## Acceptance Checks

- Rules are inspectable by product or operations owners.
- Rule changes can be tested before release.
- Decisions are logged with rule version and inputs.
- Conflicting rules have deterministic resolution.

