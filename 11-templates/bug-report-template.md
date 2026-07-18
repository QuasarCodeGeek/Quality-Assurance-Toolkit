# Bug Report Template

> **Difficulty:** Beginner
>
> **Estimated Reading Time:** 5 minutes
>
> **Prerequisites:**
>
> * Bug Report
> * Defect Management
> * Test Execution

## Overview

This template provides a standardized format for documenting software defects.

A Bug Report records the details of a defect discovered during testing, allowing developers to reproduce, investigate, and resolve the issue efficiently. A well-written Bug Report reduces misunderstandings, improves communication, and speeds up the defect resolution process.

This template can be customized to meet the reporting standards of different organizations and bug tracking systems.

---

## Document Information

| Attribute            | Description                                                             |
| -------------------- | ----------------------------------------------------------------------- |
| Purpose              | Provides a reusable template for documenting software defects.          |
| Typically Created By | QA Engineer                                                             |
| Reviewed By          | QA Lead                                                                 |
| Used By              | QA Engineers, Developers, Project Managers                              |
| Updated When         | A new defect is identified or additional information becomes available. |

---

## Objective

The objective of this template is to help teams create clear, complete, and reproducible Bug Reports that support efficient defect investigation and resolution.

---

## Template

```markdown id="r7j2mv"
# Bug Report

## Project Information

| Attribute | Details |
|-----------|---------|
| Project Name | |
| Module | |
| Reported By | |
| Assigned To | |
| Date Reported | |

---

| Attribute | Value |
|-----------|-------|
| Bug ID | BUG-001 |
| Title | |
| Severity | Critical / High / Medium / Low |
| Priority | Critical / High / Medium / Low |
| Status | New / Assigned / In Progress / Fixed / Retest / Closed |
| Environment | Development / Testing / Staging / Production |
| Application Version | |
| Related Test Case | TC-001 |
| Related Requirement | REQ-001 |

---

## Description

Provide a clear and concise description of the observed issue.

---

## Preconditions

Describe any conditions required before reproducing the defect.

---

## Steps to Reproduce

1.
2.
3.
4.

---

## Expected Result

Describe the expected system behavior.

---

## Actual Result

Describe the actual behavior observed during testing.

---

## Frequency

- Always
- Sometimes
- Rarely
- Unable to Reproduce

---

## Attachments

Include supporting evidence when available.

Examples:

- Screenshots
- Screen recordings
- Error messages
- Log files
- Console output

---

## Notes

Include any additional observations, assumptions, or related information.
```

---

## Best Practices

* Write concise and descriptive bug titles.
* Provide complete and repeatable reproduction steps.
* Include expected and actual results.
* Attach screenshots, videos, or logs whenever possible.
* Verify the issue before submitting the Bug Report.

---

## In Practice

While testing a registration feature, a QA engineer discovers that users can submit the registration form without entering a required email address.

Using this template, the engineer documents the issue, records the reproduction steps, compares the expected and actual results, assigns the appropriate severity and priority, and attaches screenshots to help the developer reproduce and resolve the defect.

---

## Common Mistakes

* Writing vague bug titles.
* Omitting reproduction steps.
* Confusing Severity with Priority.
* Failing to include supporting evidence.
* Reporting duplicate defects without verification.

---

## Summary

A Bug Report Template provides a reusable structure for documenting software defects.

Using a standardized template improves communication between QA engineers and developers, simplifies defect tracking, and helps teams resolve issues more efficiently.

---

## Related Guides

* Bug Report
* Defect Management
* Defect Life Cycle
* Severity vs Priority
* Test Summary Report Template

---

**Next:** [Requirements Traceability Matrix Template →](requirements-traceability-matrix-template.md)
