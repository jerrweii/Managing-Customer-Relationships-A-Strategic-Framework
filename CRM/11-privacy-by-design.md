# Skill 11: Privacy-by-Design

## Purpose

Embed privacy into CRM architecture from the start.

## When To Use

- Designing customer data flows.
- Building consent, export, deletion, or access features.
- Integrating third-party systems.

## Inputs

- Personal data fields.
- Legal requirements.
- Consent sources.
- Processing purposes.
- Data processors and destinations.

## Repeatable Steps

1. Classify personal and sensitive data.
2. Attach purpose, consent, and retention metadata.
3. Gate data use by purpose and permission.
4. Implement access, correction, export, and deletion workflows.
5. Test privacy behavior across integrations.

## Software Artifacts

- Privacy data model.
- Consent gates.
- Data subject request workflows.
- Deletion and retention jobs.
- Privacy test cases.

## Acceptance Checks

- Privacy rules are enforced in code, not only in policy.
- Data exports and deletions are traceable.
- Integrations honor consent and retention.
- The design minimizes unnecessary data collection.

