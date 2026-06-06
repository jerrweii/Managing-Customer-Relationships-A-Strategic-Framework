# Skill 04: Customer Identification

## Purpose

Design reliable customer recognition across records, channels, accounts, and devices.

## When To Use

- Building customer profiles.
- Solving duplicate records.
- Unifying online and offline interactions.
- Integrating CRM with support, marketing, billing, or product systems.

## Inputs

- Identity sources.
- Matching keys.
- Duplicate examples.
- Merge policies.
- Channel identifiers.

## Repeatable Steps

1. Inventory all identifiers used for a customer.
2. Classify identifiers as strong, weak, persistent, or temporary.
3. Define deterministic and probabilistic matching rules.
4. Create merge, split, and conflict resolution workflows.
5. Preserve source evidence and audit history for identity decisions.

## Software Artifacts

- Identity resolution service.
- Customer master record.
- Duplicate detection workflow.
- Merge audit log.
- Identity confidence score.

## Acceptance Checks

- The system can explain why records were linked.
- Merge actions are reversible or auditable.
- Channel-specific identifiers map to a durable customer identity.
- Identity errors do not silently corrupt customer history.

