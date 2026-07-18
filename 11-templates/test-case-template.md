# Test Case Template

> **Difficulty:** Beginner
>
> **Estimated Reading Time:** 5 minutes
>
> **Prerequisites:**
>
> * Test Cases
> * Test Scenarios

## Overview

This template provides a standardized format for creating Test Cases.

A Test Case is a detailed document that describes the specific steps, test data, expected results, and execution conditions required to verify a particular software requirement or functionality.

Using a consistent Test Case template helps improve testing quality, maintainability, and collaboration across software teams.

---

## Document Information

| Attribute            | Description                                                   |
| -------------------- | ------------------------------------------------------------- |
| Purpose              | Provides a reusable template for documenting Test Cases.      |
| Typically Created By | QA Engineer                                                   |
| Reviewed By          | QA Lead                                                       |
| Used By              | QA Engineers, Developers, Testers                             |
| Updated When         | Requirements, business rules, or application behavior change. |

---

## Objective

The objective of this template is to help teams create consistent, repeatable, and easy-to-understand Test Cases that verify software requirements accurately.

---

## Template

```markdown id="lps8fh"
# Test Case

## Project Information

| Attribute | Details |
|-----------|---------|
| Project Name | |
| Module | |
| Prepared By | |
| Reviewed By | |
| Date | |

---

| Attribute | Value |
|-----------|-------|
| Test Case ID | TC-001 |
| Test Scenario ID | TS-001 |
| Requirement ID | REQ-001 |
| Title | |
| Priority | High / Medium / Low |
| Severity | Critical / High / Medium / Low |
| Preconditions | |
| Test Data | |
| Expected Result | |
| Actual Result | *(Completed during Test Execution)* |
| Status | Pass / Fail / Blocked / Not Executed / Skipped |

---

## Test Steps

| Step | Action | Expected Result |
|------|--------|-----------------|
| 1 | | |
| 2 | | |
| 3 | | |

---

## Postconditions

Describe the expected state of the application after executing the Test Case.

---

## Notes

Include any assumptions, dependencies, or additional observations.
```

---

## Best Practices

* Assign a unique Test Case ID for traceability.
* Keep each Test Case focused on a single objective.
* Write clear, repeatable, and unambiguous test steps.
* Use realistic and well-defined Test Data.
* Update Test Cases whenever requirements change.

---

## In Practice

A QA engineer needs to verify the login functionality of a web application.

Using this template, the engineer creates individual Test Cases for successful login, invalid credentials, locked accounts, password reset, and session timeout. Each Test Case contains the required test data, execution steps, expected results, and execution status, making testing consistent and repeatable.

---

## Common Mistakes

* Combining multiple objectives into a single Test Case.
* Writing vague or incomplete test steps.
* Omitting required Test Data.
* Leaving expected results unclear.
* Failing to update Test Cases after requirement changes.

---

## Summary

A Test Case Template provides a reusable structure for documenting detailed software tests.

By standardizing Test Case documentation, teams can improve consistency, simplify execution, enhance traceability, and support more reliable software testing throughout the development lifecycle.

---

## Related Guides

* Test Cases
* Test Scenarios
* Test Execution
* Test Data
* Bug Report Template

---

**Next:** [Bug Report Template →](bug-report-template.md)
