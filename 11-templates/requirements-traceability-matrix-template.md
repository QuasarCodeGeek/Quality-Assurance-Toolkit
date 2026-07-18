# Requirements Traceability Matrix (RTM) Template

> **Difficulty:** Beginner
>
> **Estimated Reading Time:** 5 minutes
>
> **Prerequisites:**
>
> * Requirements Traceability Matrix (RTM)
> * Requirement Types
> * Test Cases

## Overview

This template provides a standardized format for creating a Requirements Traceability Matrix (RTM).

An RTM is a document that maps software requirements to their corresponding Test Scenarios, Test Cases, and testing results. It helps ensure that every requirement is verified during testing and provides complete traceability throughout the software development lifecycle.

This template can be customized to accommodate different project sizes, development methodologies, and organizational standards.

---

## Document Information

| Attribute            | Description                                                            |
| -------------------- | ---------------------------------------------------------------------- |
| Purpose              | Provides a reusable template for documenting requirement traceability. |
| Typically Created By | QA Engineer / Business Analyst                                         |
| Reviewed By          | QA Lead, Project Manager                                               |
| Used By              | QA Engineers, Developers, Business Analysts, Project Managers          |
| Updated When         | Requirements, Test Cases, or testing results change.                   |

---

## Objective

The objective of this template is to help teams maintain complete traceability between software requirements and testing activities, ensuring that all requirements are properly verified before release.

---

## Template

```markdown id="0sy5pb"
# Requirements Traceability Matrix (RTM)

## Project Information

| Attribute | Details |
|-----------|---------|
| Project Name | |
| Version | |
| Prepared By | |
| Reviewed By | |
| Date | |

---

| Requirement ID | Requirement Description | Priority | Test Scenario ID | Test Case ID | Test Status | Bug ID | Remarks |
|----------------|-------------------------|----------|------------------|--------------|-------------|--------|---------|
| REQ-001 | | High | TS-001 | TC-001 | Pass | - | |
| REQ-002 | | Medium | TS-002 | TC-002 | Fail | BUG-001 | |
| REQ-003 | | Low | TS-003 | TC-003 | Not Executed | - | |

---

## Summary

| Metric | Value |
|--------|------:|
| Total Requirements | |
| Covered Requirements | |
| Uncovered Requirements | |
| Passed Requirements | |
| Failed Requirements | |
| Blocked Requirements | |

---

## Notes

Include assumptions, dependencies, excluded requirements, or additional project-specific information.
```

---

## Best Practices

* Assign a unique identifier to every requirement.
* Keep the RTM updated throughout the project lifecycle.
* Ensure every requirement maps to at least one Test Scenario and Test Case.
* Update testing results after Test Execution.
* Link related Bug IDs for failed requirements whenever applicable.

---

## In Practice

A QA engineer is preparing for User Acceptance Testing (UAT) before a production release.

Using this template, the engineer maps every approved requirement to its corresponding Test Scenario and Test Case. As testing progresses, execution results and related Bug IDs are recorded, allowing stakeholders to quickly identify which requirements have been verified and which still require attention.

---

## Common Mistakes

* Leaving requirements without corresponding Test Cases.
* Failing to update testing status after execution.
* Using inconsistent requirement identifiers.
* Not linking related Bug Reports.
* Treating the RTM as a one-time document instead of maintaining it throughout the project.

---

## Summary

A Requirements Traceability Matrix (RTM) Template provides a reusable structure for tracking software requirements throughout the testing process.

By maintaining clear traceability between requirements, Test Scenarios, Test Cases, execution results, and defects, teams can improve coverage, simplify reporting, and reduce the risk of releasing unverified functionality.

---

## Related Guides

* Requirements Traceability Matrix
* Requirement Types
* Test Scenarios
* Test Cases
* Test Summary Report Template

---

**Next:** [Test Summary Report Template →](test-summary-report-template.md)
