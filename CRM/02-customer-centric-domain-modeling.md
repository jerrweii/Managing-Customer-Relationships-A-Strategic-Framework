# Skill 02: Customer-Centric Domain Modeling

## Purpose

Model the customer as the central domain entity instead of centering the CRM around products, campaigns, tickets, or transactions.

## When To Use

- Designing CRM schemas.
- Refactoring fragmented customer records.
- Building account, contact, lead, household, or organization models.

## Inputs

- Existing data model.
- Customer identity sources.
- Relationship types.
- Touchpoint history.
- Consent and preference requirements.

## Repeatable Steps

1. Define the customer entity and its variants: person, account, household, organization.
2. Model relationships among customers, accounts, contacts, employees, and channels.
3. Separate identity, profile, behavior, value, consent, and interaction data.
4. Represent relationship history as a timeline, not only as current fields.
5. Make the model extensible for future needs, preferences, and value signals.

## Software Artifacts

- Customer domain model.
- Entity relationship diagram.
- Customer profile schema.
- Relationship graph model.
- Customer timeline events.

## Acceptance Checks

- A complete customer view can be reconstructed from the model.
- Product and campaign data attach to the customer, not the reverse.
- The model supports identity merge and history preservation.
- Privacy and consent are first-class fields.

