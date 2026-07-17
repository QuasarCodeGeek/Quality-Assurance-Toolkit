# Test Cases

> **Difficulty:** Intermediate
>
> **Estimated Reading Time:** 10 minutes
>
> **Prerequisites:**
>
> * Test Scenarios
> * Test Plan

## Overview

A Test Case is a detailed document that defines the steps, conditions, inputs, and expected results used to verify a specific software requirement or functionality.

Unlike a Test Scenario, which identifies what should be tested, a Test Case provides detailed instructions on how testing should be performed to validate the expected behavior of the system.

Well-written Test Cases improve testing consistency, increase coverage, and make testing repeatable across different testers and project releases.

---

## Document Information

| Attribute             | Description                                                                |
| --------------------- | -------------------------------------------------------------------------- |
| Purpose               | Verifies that a specific requirement or functionality behaves as expected. |
| Typically Created By  | QA Engineer                                                                |
| Typically Reviewed By | QA Lead, Senior QA Engineer                                                |
| Typically Used By     | QA Team                                                                    |
| Updated When          | Requirements, functionality, or expected behavior change.                  |

---

## Objective

The objective of a Test Case is to provide a clear and repeatable procedure for validating software functionality while ensuring consistent testing across different environments and testers.

---

## Typical Components

A Test Case commonly includes the following information:

| Component             | Description                               |
| --------------------- | ----------------------------------------- |
| Test Case ID          | Unique identifier.                        |
| Title                 | Short description of the test.            |
| Requirement Reference | Related requirement or user story.        |
| Preconditions         | Conditions before execution.              |
| Test Steps            | Actions to perform.                       |
| Test Data             | Required input values.                    |
| Expected Result       | Expected system behavior.                 |
| Actual Result         | Observed system behavior after execution. |
| Status                | Pass, Fail, Blocked, or Not Executed.     |

---

## Example Test Case

| Field           | Value                                                                     |
| --------------- | ------------------------------------------------------------------------- |
| Test Case ID    | TC-001                                                                    |
| Title           | Verify successful login with valid credentials                            |
| Preconditions   | User account exists                                                       |
| Test Data       | Valid email and password                                                  |
| Test Steps      | 1. Open Login page.<br>2. Enter valid credentials.<br>3. Click **Login**. |
| Expected Result | User is redirected to the dashboard.                                      |

---

## Test Scenario vs Test Case

| Aspect           | Test Scenario        | Test Case           |
| ---------------- | -------------------- | ------------------- |
| Purpose          | Defines what to test | Defines how to test |
| Detail Level     | High-level           | Detailed            |
| Test Steps       | No                   | Yes                 |
| Expected Results | No                   | Yes                 |
| Execution Ready  | No                   | Yes                 |

---

## Key Deliverables

| Component             | Deliverable         |
| --------------------- | ------------------- |
| Requirement Review    | Test Case Coverage  |
| Test Design           | Test Cases          |
| Test Data Preparation | Test Data           |
| Test Case Review      | Approved Test Cases |

---

## Benefits

* Provides repeatable testing procedures.
* Improves testing consistency.
* Increases testing coverage.
* Simplifies regression testing.
* Supports collaboration among QA team members.

---

## Best Practices

#### Design

* Write one objective per Test Case.
* Use clear, concise, and sequential test steps.
* Define measurable expected results.

#### Coverage

* Include positive, negative, boundary, and validation test cases where appropriate.
* Link Test Cases to requirements or user stories.
* Ensure important business rules are covered.

#### Maintenance

* Keep Test Cases up to date.
* Remove duplicate or obsolete Test Cases.
* Review Test Cases before execution.

---

## In Practice

A QA engineer is testing a user registration feature.

After identifying the required Test Scenarios, the engineer creates individual Test Cases for successful registration, duplicate email validation, password strength requirements, required field validation, and invalid email formats.

Each Test Case includes the necessary preconditions, test steps, input data, and expected results, allowing any tester to execute the tests consistently.

---

## Developer Tips

* Review Test Cases before implementing complex features.
* Keep application behavior consistent with documented requirements.
* Design features that are easy to validate.
* Communicate requirement changes that may affect existing Test Cases.
* Consider edge cases during implementation, not only during testing.

---

## Common Mistakes

* Combining multiple objectives into one Test Case.
* Writing vague or incomplete expected results.
* Skipping preconditions or required test data.
* Creating duplicate Test Cases.
* Failing to update Test Cases after requirement changes.

---

## Summary

Test Cases provide detailed, repeatable instructions for verifying software functionality.

Well-designed Test Cases improve software quality by ensuring that requirements are consistently validated and that testing can be repeated accurately throughout the software development lifecycle.

---

## Related Guides

* Test Scenarios
* Test Data
* Test Execution
* Requirements Traceability Matrix
* Software Testing Life Cycle (STLC)

---

**Next:** [Test Data →](test-data.md)
