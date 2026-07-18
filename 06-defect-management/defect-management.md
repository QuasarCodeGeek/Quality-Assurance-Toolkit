# Defect Management

> **Difficulty:** Beginner
>
> **Estimated Reading Time:** 8 minutes
>
> **Prerequisites:**
>
> * Test Execution
> * Software Testing Life Cycle (STLC)

## Overview

Defect Management is the structured process of identifying, documenting, tracking, resolving, verifying, and closing defects discovered during software development and testing.

Its primary purpose is to ensure that defects are handled consistently, prioritized appropriately, and resolved before software is released to end users.

An effective Defect Management process improves software quality, enhances collaboration between development and testing teams, and provides visibility into the overall health of a project.

---

## Document Information

| Attribute         | Description                                                                             |
| ----------------- | --------------------------------------------------------------------------------------- |
| Purpose           | Provides a structured process for managing software defects throughout their lifecycle. |
| Typically Used By | QA Engineers, Developers, Project Managers                                              |
| Updated When      | Defect management processes or project workflows change.                                |

---

## Objective

The objective of Defect Management is to ensure that every identified defect is properly documented, prioritized, tracked, resolved, verified, and closed in a consistent and transparent manner.

---

## Defect Management Process

A typical Defect Management process includes the following stages:

1. Identify a defect.
2. Document the defect.
3. Assign severity and priority.
4. Assign the defect to the appropriate developer.
5. Investigate and resolve the defect.
6. Retest the implemented fix.
7. Verify the resolution.
8. Close the defect.

Depending on project needs, additional statuses such as **Deferred**, **Rejected**, or **Duplicate** may also be used.

---

## Roles and Responsibilities

### QA Engineers

* Identify and document defects.
* Assign initial severity and priority.
* Verify implemented fixes.
* Close verified defects.

### Developers

* Investigate reported defects.
* Implement appropriate fixes.
* Update defect status during development.

### Project Managers

* Monitor defect trends.
* Prioritize defect resolution.
* Coordinate releases based on defect status.

---

## Key Deliverables

| Activity              | Deliverable                       |
| --------------------- | --------------------------------- |
| Defect Reporting      | Bug Report                        |
| Defect Prioritization | Severity and Priority Assessment  |
| Defect Resolution     | Updated Defect Status             |
| Defect Verification   | Verification Results              |
| Project Completion    | Closed Defects and Defect Metrics |

---

## Benefits

* Standardizes defect handling across the team.
* Improves communication between QA and development.
* Provides visibility into project quality.
* Supports informed release decisions.
* Helps reduce recurring defects.

---

## Best Practices

#### Reporting

* Report defects as soon as they are discovered.
* Provide complete and accurate defect information.
* Include supporting evidence whenever possible.

#### Tracking

* Keep defect statuses up to date.
* Prioritize defects based on business impact.
* Verify fixes before closing defects.

#### Collaboration

* Encourage clear communication between QA and developers.
* Discuss unclear defects before implementation.
* Review defect trends during project retrospectives.

---

## In Practice

During system testing, a QA engineer discovers that users cannot reset their passwords.

The issue is documented in a Bug Report with reproduction steps, expected and actual results, screenshots, and an initial severity and priority assessment.

A developer investigates and implements a fix. The QA engineer then retests the feature, verifies that the issue has been resolved, and closes the defect after successful validation.

---

## Developer Tips

* Reproduce reported defects before implementing fixes.
* Review attached evidence carefully.
* Update defect status promptly.
* Include sufficient implementation notes when appropriate.
* Verify that fixes do not introduce regression issues.

---

## Common Mistakes

* Reporting duplicate defects without verification.
* Submitting incomplete Bug Reports.
* Assigning incorrect severity or priority.
* Closing defects without proper verification.
* Ignoring recurring defect patterns.

---

## Summary

Defect Management provides a structured approach for handling software defects from discovery through resolution and closure.

By following a consistent process, development teams can improve collaboration, maintain visibility into software quality, and ensure that reported issues are resolved efficiently before release.

---

## Related Guides

* Test Execution
* Bug Report
* Severity vs Priority
* Defect Life Cycle
* Defect Status

---

**Next:** [Bug Report →](bug-report.md)
