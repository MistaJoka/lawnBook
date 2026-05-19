# Data Model

## Core Entities

List the main objects in the app.

| Entity | Description | Example |
|---|---|---|
| User | Person using the app | Solo landscaper |
| Client | Customer or account | Homeowner |
| Job | Work to complete | Lawn service visit |

## Entity Questions

For each entity, answer:

- What is it?
- Who creates it?
- Who can view it?
- Who can edit it?
- Can it be deleted?
- Does it need timestamps?
- Does it sync offline?

## Field Template

| Field | Type | Required | Notes |
|---|---|---|---|
| id | string/uuid | yes | Primary key |
| created_at | datetime | yes | Created timestamp |
| updated_at | datetime | yes | Updated timestamp |

## Relationship Questions

- What belongs to a user?
- What belongs to a client?
- What belongs to a job/project/order?
- What can have photos/files?
- What can have status changes?
- What needs audit history?

## Sensitive Data Questions

- What data is private?
- What data should not be stored?
- What data needs encryption?
- What data should be exportable?
- What data should be deleted on request?
