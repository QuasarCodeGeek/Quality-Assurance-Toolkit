# System Testing

> **Difficulty:** Intermediate
>
> **Estimated Reading Time:** 7 minutes
>
> **Prerequisites:**
>
> * Functional Testing
> * Integration Testing
> * Test Execution

## Overview

System Testing is a type of Functional Testing that evaluates the complete and integrated software system against its specified functional and non-functional requirements.

Unlike Integration Testing, which focuses on interactions between components, System Testing validates the application as a whole to ensure that all features work together correctly in a production-like environment.

System Testing is typically performed after Integration Testing and before User Acceptance Testing (UAT).

---

## Document Information

| Attribute             | Description                                                                      |
| --------------------- | -------------------------------------------------------------------------------- |
| Purpose               | Verifies that the complete software system satisfies its specified requirements. |
| Typically Used By     | QA Engineers                                                                     |
| Typically Reviewed By | QA Lead, Project Manager                                                         |
| Typically Used By     | QA Team, Project Managers, Stakeholders                                          |
| Updated When          | System requirements, environments, or major application functionality change.    |

---

## Objective

The objective of System Testing is to validate that the fully integrated application functions correctly and satisfies its documented requirements before it is presented for user acceptance.

---

## Common Verification Areas

System Testing commonly verifies:

* Complete business workflows
* Functional requirements
* System configuration
* User permissions
* Error handling
* Data processing
* External integrations
* Basic non-functional requirements

---

## Key Deliverables

| Activity              | Deliverable                |
| --------------------- | -------------------------- |
| System Test Execution | System Test Results        |
| Failed Verification   | Bug Reports                |
| Test Completion       | System Test Summary Report |

---

## Benefits

* Validates the application as a complete system.
* Detects defects that may not appear during Integration Testing.
* Confirms that business requirements are satisfied.
* Improves confidence before User Acceptance Testing.
* Reduces release risks.

---

## Best Practices

#### Planning

* Prepare end-to-end business scenarios.
* Use a production-like testing environment.
* Ensure all integrated components are available.

#### Execution

* Validate complete user workflows.
* Verify expected and unexpected user behavior.
* Document all observed defects and inconsistencies.

---

## In Practice

A team completes development of an online reservation system.

During System Testing, the QA engineer verifies that users can register, authenticate, browse available schedules, complete reservations, receive notifications, and generate reports while ensuring that the entire application functions correctly as an integrated system.

After successful System Testing, the application is prepared for User Acceptance Testing (UAT).

---

## Developer Tips

* Test features within the context of the complete application.
* Consider interactions between multiple modules.
* Review production configuration differences.
* Verify application behavior using realistic data.
* Resolve system-level defects before UAT.

---

## Common Mistakes

* Assuming successful Integration Testing guarantees successful System Testing.
* Testing only individual features instead of complete workflows.
* Using unrealistic environments or configuration.
* Ignoring system-wide error handling.
* Skipping verification of business requirements.

---

## Summary

System Testing validates the complete software application by verifying that all integrated components work together according to the specified requirements.

By evaluating the application as a whole, System Testing provides confidence that the software is ready for user acceptance and eventual production deployment.

---

## Related Guides

* Integration Testing
* End-to-End (E2E) Testing
* User Acceptance Testing (UAT)
* Functional Testing
* Test Execution

---

**Next:** [End-to-End (E2E) Testing →](end-to-end-testing.md)
