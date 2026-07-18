# Acceptance Criteria

> **Difficulty:** Beginner
>
> **Estimated Reading Time:** 7 minutes
>
> **Prerequisites:**
>
> * Requirement Types
> * Test Cases

## Overview

Acceptance Criteria are a set of clearly defined conditions that a software feature or requirement must satisfy before it is considered complete and acceptable to stakeholders.

They establish a shared understanding between business stakeholders, developers, and QA engineers by defining the expected behavior of a feature.

Well-written Acceptance Criteria help reduce misunderstandings, improve software quality, and provide a clear basis for designing and executing Test Cases.

---

## Document Information

| Attribute             | Description                                                                          |
| --------------------- | ------------------------------------------------------------------------------------ |
| Purpose               | Defines the conditions that must be met for a requirement or feature to be accepted. |
| Typically Created By  | Product Owner, Business Analyst                                                      |
| Typically Reviewed By | Stakeholders, Development Team, QA Team                                              |
| Typically Used By     | Developers, QA Engineers, Product Owners                                             |
| Updated When          | Requirements or business rules change.                                               |

---

## Objective

The objective of Acceptance Criteria is to define measurable and testable conditions that determine whether a software requirement has been successfully implemented.

---

## Characteristics of Good Acceptance Criteria

Effective Acceptance Criteria should be:

* Clear
* Specific
* Testable
* Measurable
* Unambiguous
* Business-focused

Each criterion should describe an observable outcome that can be verified through testing.

---

## Common Formats

Acceptance Criteria can be written in different formats depending on the project.

### Bullet List

A simple list of expected conditions.

Example:

* Users can log in using a valid email address and password.
* Invalid credentials display an appropriate error message.
* Passwords are stored securely.

---

### Given-When-Then

A structured format commonly used in Behavior-Driven Development (BDD).

It describes:

* **Given** — the initial condition.
* **When** — the action performed.
* **Then** — the expected result.

This format helps define software behavior in a consistent and testable manner.

---

## Relationship with Testing

Acceptance Criteria serve as the primary reference when creating:

* Test Scenarios
* Test Cases
* User Acceptance Tests (UAT)

Every Acceptance Criterion should be validated during testing before the related feature is considered complete.

---

## Key Deliverables

| Activity               | Deliverable         |
| ---------------------- | ------------------- |
| Requirement Definition | Acceptance Criteria |
| Test Design            | Test Scenarios      |
| Test Preparation       | Test Cases          |

---

## Benefits

* Clarifies business expectations.
* Reduces requirement ambiguity.
* Improves Test Case quality.
* Supports User Acceptance Testing.
* Helps determine feature completion.

---

## Best Practices

#### Writing

* Write Acceptance Criteria before development begins.
* Keep each criterion simple and measurable.
* Focus on observable system behavior.

#### Collaboration

* Review Acceptance Criteria with stakeholders.
* Ensure developers and QA share the same understanding.
* Update Acceptance Criteria when requirements change.

#### Testing

* Create Test Cases directly from Acceptance Criteria.
* Verify every criterion during testing.
* Ensure no criterion is left untested.

---

## In Practice

A product owner defines Acceptance Criteria for a login feature.

The criteria specify that users can successfully log in with valid credentials, receive an error message for invalid credentials, and remain authenticated after signing in.

The QA team creates Test Cases based on these criteria and verifies each condition before approving the feature for release.

---

## Developer Tips

* Review Acceptance Criteria before implementation.
* Ask questions if any criterion is unclear.
* Treat Acceptance Criteria as the definition of feature completion.
* Keep implementation aligned with business expectations.
* Collaborate with QA when validating completed features.

---

## Common Mistakes

* Writing vague or ambiguous Acceptance Criteria.
* Including implementation details instead of expected behavior.
* Creating criteria that cannot be tested.
* Failing to update Acceptance Criteria when requirements change.
* Marking features as complete without verifying every criterion.

---

## Summary

Acceptance Criteria define the conditions that software features must satisfy before they are accepted by stakeholders.

By establishing clear, measurable, and testable expectations, they improve communication, support effective testing, and help ensure that delivered software meets business requirements.

---

## Related Guides

* Requirement Types
* Requirements Traceability Matrix (RTM)
* Test Scenarios
* Test Cases
* User Acceptance Testing (UAT)

---

**Next:** [User Stories vs Requirements →](user-stories-vs-requirements.md)
