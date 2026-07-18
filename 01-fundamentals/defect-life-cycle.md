# Defect Life Cycle

> **Difficulty:** Beginner
>
> **Estimated Reading Time:** 8 minutes
>
> **Prerequisites:**
>
> * Quality Assurance (QA) vs Quality Control (QC)
> * Software Testing Life Cycle (STLC)

## Overview

The Defect Life Cycle describes the stages a software defect goes through from the time it is identified until it is resolved and closed. It provides a structured workflow for reporting, tracking, fixing, verifying, and managing defects throughout the software development process.

While the exact workflow may vary depending on an organization's processes and the tools it uses, the core stages remain generally consistent across software projects.

---

## Defect Life Cycle Stages

### 1. New

A tester or stakeholder identifies a defect and submits a bug report containing sufficient information for investigation.

#### Key Activities

* Report the defect.
* Record the expected and actual results.
* Provide reproduction steps.
* Attach supporting evidence such as screenshots or logs.

---

### 2. Assigned

The reported defect is reviewed and assigned to the appropriate developer or team for investigation.

#### Key Activities

* Review the defect report.
* Confirm ownership.
* Prioritize the defect.
* Begin investigation.

---

### 3. Open

The assigned developer analyzes the defect, identifies the root cause, and begins implementing a fix.

#### Key Activities

* Reproduce the defect.
* Investigate the root cause.
* Implement the fix.
* Prepare the updated build.

---

### 4. Fixed

The developer completes the implementation and marks the defect as fixed, making it available for verification.

#### Key Activities

* Complete the code changes.
* Perform initial validation.
* Submit the fix for QA verification.

---

### 5. Retest

The QA team verifies that the implemented fix resolves the reported defect without introducing new issues.

#### Key Activities

* Execute relevant test cases.
* Verify the reported issue.
* Perform regression testing when necessary.

---

### 6. Verified

The defect fix is confirmed to be successful and behaves according to the expected requirements.

#### Key Activities

* Confirm expected behavior.
* Validate related functionality.
* Update defect status.

---

### 7. Closed

The defect is officially closed after successful verification.

#### Key Activities

* Close the defect record.
* Archive supporting information.
* Update project documentation if required.

---

## Common Defect Statuses

Some projects include additional defect statuses depending on their workflow.

| Status           | Description                                               |
| ---------------- | --------------------------------------------------------- |
| Rejected         | The reported issue is not considered a valid defect.      |
| Duplicate        | The defect has already been reported.                     |
| Deferred         | The fix is postponed to a future release.                 |
| Cannot Reproduce | The reported issue cannot be reproduced consistently.     |
| Not a Bug        | The reported behavior matches the intended system design. |

---

## Key Deliverables

| Stage    | Key Deliverable      |
| -------- | -------------------- |
| New      | Bug Report           |
| Assigned | Assigned Defect      |
| Open     | Root Cause Analysis  |
| Fixed    | Updated Build        |
| Retest   | Retest Results       |
| Verified | Verified Defect      |
| Closed   | Closed Defect Record |

---

## Benefits

* Provides a structured defect management workflow.
* Improves communication between QA and development teams.
* Helps prioritize defect resolution.
* Ensures defects are properly verified before release.
* Maintains complete defect history for future reference.

---

## Best Practices

#### Reporting

* Write clear and reproducible bug reports.
* Include screenshots, logs, and supporting evidence.
* Provide expected and actual results.

#### Verification

* Retest every reported fix.
* Perform regression testing when necessary.
* Verify related functionality before closing defects.

#### Collaboration

* Communicate defect status clearly.
* Prioritize defects based on business impact.
* Keep defect records updated throughout the lifecycle.

---

## In Practice

Consider a tester discovering that users cannot log in after resetting their password.

The tester documents the issue, provides reproduction steps, and submits a bug report.

The defect is assigned to a developer, who reproduces the issue, identifies the root cause, and implements a fix.

After receiving an updated build, the QA team retests the feature and performs regression testing to ensure no related functionality has been affected.

Once the issue is verified as resolved, the defect is marked as closed.

---

## Developer Tips

* Always reproduce a defect before attempting a fix.
* Keep bug reports concise but complete.
* Fix the root cause instead of only addressing the visible symptom.
* Communicate clearly with QA when additional information is needed.
* Retest fixes before marking defects as resolved.

---

## Common Mistakes

* Closing defects without verification.
* Reporting defects with incomplete reproduction steps.
* Assigning incorrect severity or priority.
* Fixing symptoms instead of root causes.
* Ignoring regression testing after implementing fixes.

---

## Summary

The Defect Life Cycle provides a structured approach for managing software defects from identification through resolution and closure.

Following a consistent defect workflow improves communication, increases software quality, and ensures that reported issues are resolved effectively before software is released.

---

## Related Guides

* Software Testing Life Cycle (STLC)
* Severity vs Priority
* Bug Report
* Regression Testing
* Test Cases

---

**Next:** [Severity vs Priority →](severity-vs-priority.md)
