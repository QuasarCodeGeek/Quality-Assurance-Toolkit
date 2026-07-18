# Test Scenario Template

> **Difficulty:** Beginner
>
> **Estimated Reading Time:** 4 minutes
>
> **Prerequisites:**
>
> * Test Scenario

## Overview

This template provides a standardized format for creating Test Scenarios.

A Test Scenario describes **what** should be tested from a user's perspective without specifying the detailed steps required to perform the test. It serves as a high-level testing document that helps ensure application features are adequately covered before detailed Test Cases are created.

This template can be customized to fit different projects, methodologies, and documentation standards.

---

## Document Information

| Attribute            | Description                                                  |
| -------------------- | ------------------------------------------------------------ |
| Purpose              | Provides a reusable template for documenting Test Scenarios. |
| Typically Created By | QA Engineer                                                  |
| Reviewed By          | QA Lead                                                      |
| Used By              | QA Engineers, Developers, Business Analysts                  |
| Updated When         | Requirements or application features change.                 |

---

## Objective

The objective of this template is to help teams consistently document high-level testing scenarios that provide complete functional coverage before creating detailed Test Cases.

---

## Template

```markdown id="iwtvhs"
# Test Scenario

## Project Information

| Attribute | Details |
|-----------|---------|
| Project Name | |
| Module | |
| Prepared By | |
| Date | |

---

| Scenario ID | TS-001 |
|--------------|--------|
| Scenario Name | |
| Feature / Module | |
| Requirement Reference | |
| Priority | High / Medium / Low |
| Preconditions | |
| Expected Outcome | |

---

## Description

Provide a brief description of the functionality being tested.

---

## Business Objective

Describe why this scenario is important from the user's or business perspective.

---

## Related Test Cases

- TC-001
- TC-002
- TC-003

---

## Notes

Include any assumptions, dependencies, or additional information.
```

---

## Best Practices

* Write scenarios from the user's perspective.
* Focus on **what** should be tested rather than **how** it will be tested.
* Keep scenarios concise and easy to understand.
* Link each scenario to one or more detailed Test Cases.
* Maintain traceability between requirements and Test Scenarios.

---

## In Practice

A QA engineer is assigned to test the login functionality of a web application.

Before writing detailed Test Cases, the engineer creates Test Scenarios such as **User Login**, **Forgot Password**, **Invalid Login**, and **Session Timeout**. These scenarios provide a high-level view of the functionality to be tested and serve as the basis for creating detailed Test Cases.

---

## Common Mistakes

* Including detailed test steps that belong in Test Cases.
* Creating scenarios that are too broad or too specific.
* Missing important user workflows.
* Failing to link scenarios to requirements.
* Treating Test Scenarios as executable test documents.

---

## Summary

A Test Scenario Template provides a reusable structure for documenting high-level testing scenarios.

By organizing testing around user workflows and business requirements, teams can improve test coverage, simplify planning, and create more effective Test Cases.

---

## Related Guides

* Test Scenario
* Test Cases
* Test Plan
* Requirements Traceability Matrix
* Test Case Template

---

**Next:** [Test Case Template →](test-case-template.md)
