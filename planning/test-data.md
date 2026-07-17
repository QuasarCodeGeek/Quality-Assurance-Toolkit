# Test Data

> **Difficulty:** Intermediate
>
> **Estimated Reading Time:** 8 minutes
>
> **Prerequisites:**
>
> * Test Cases
> * Software Testing Life Cycle (STLC)

## Overview

Test Data is the collection of input values, records, files, or datasets used to execute Test Cases and verify that a software application behaves as expected.

Well-prepared Test Data helps ensure that software is tested under realistic conditions, allowing testers to validate both expected and unexpected system behavior.

---

## Document Information

| Attribute             | Description                                                |
| --------------------- | ---------------------------------------------------------- |
| Purpose               | Provides the input data required to execute Test Cases.    |
| Typically Created By  | QA Engineer                                                |
| Typically Reviewed By | QA Lead, Development Team                                  |
| Typically Used By     | QA Team, Automation Engineers                              |
| Updated When          | Test Cases, business rules, or system requirements change. |

---

## Objective

The objective of Test Data is to provide accurate and representative inputs that enable consistent, repeatable, and reliable software testing.

---

## Types of Test Data

### Valid Data

Input values that satisfy all business rules and are expected to produce successful results.

### Invalid Data

Input values that intentionally violate validation rules to verify that the system handles errors correctly.

### Boundary Data

Input values that test the minimum, maximum, and edge limits accepted by the application.

### Positive Data

Data used to confirm that the application behaves correctly under normal conditions.

### Negative Data

Data designed to verify that the application handles invalid or unexpected inputs gracefully.

### Production-like Data

Anonymized or generated data that closely resembles real-world information without exposing sensitive or confidential data.

---

## Key Deliverables

| Component        | Deliverable        |
| ---------------- | ------------------ |
| Test Case Review | Required Test Data |
| Data Preparation | Test Dataset       |
| Data Validation  | Verified Test Data |
| Test Execution   | Test Results       |

---

## Benefits

* Improves testing accuracy.
* Increases confidence in test results.
* Supports repeatable testing.
* Helps identify edge cases.
* Reduces defects caused by insufficient test coverage.

---

## Best Practices

#### Preparation

* Create Test Data early in the testing process.
* Cover positive, negative, and boundary conditions.
* Keep datasets organized and reusable.

#### Security

* Never use sensitive production data without proper protection.
* Mask or anonymize confidential information.
* Follow organizational data privacy policies.

#### Maintenance

* Keep Test Data synchronized with Test Cases.
* Remove obsolete datasets.
* Review datasets when business rules change.

---

## In Practice

A QA engineer is testing an online registration system.

To validate the registration feature, the engineer prepares multiple datasets, including valid user information, duplicate email addresses, weak passwords, invalid email formats, empty required fields, and boundary-length usernames.

These datasets are used across multiple Test Cases to verify that the application correctly accepts valid input and appropriately rejects invalid input.

---

## Developer Tips

* Design validation rules that are easy to test.
* Avoid hardcoding test values whenever possible.
* Consider edge cases during development.
* Generate reusable datasets for automated testing.
* Ensure test environments contain realistic data.

---

## Common Mistakes

* Testing only with valid input.
* Reusing outdated Test Data.
* Using sensitive production data without anonymization.
* Ignoring boundary value testing.
* Creating Test Cases without preparing the required Test Data.

---

## Summary

Test Data provides the inputs necessary to execute Test Cases and verify software behavior under different conditions.

Well-designed Test Data improves testing quality by ensuring that applications are validated using realistic, comprehensive, and repeatable datasets.

---

## Related Guides

* Test Cases
* Test Execution
* Boundary Value Analysis
* Equivalence Partitioning
* Data Privacy in Testing

---

**Next:** [Test Execution →](../execution/test-execution.md)
