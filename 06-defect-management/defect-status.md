# Defect Status

> **Difficulty:** Beginner
>
> **Estimated Reading Time:** 7 minutes
>
> **Prerequisites:**
>
> * Defect Management
> * Defect Life Cycle

## Overview

Defect Status represents the current state of a software defect as it progresses through the Defect Life Cycle.

Each status communicates the progress of investigation, resolution, verification, or closure, allowing development teams to track defects consistently throughout a project.

Although status names may vary between organizations and issue tracking systems, the concepts remain largely consistent.

---

## Document Information

| Attribute         | Description                                                                  |
| ----------------- | ---------------------------------------------------------------------------- |
| Purpose           | Defines the meaning of common defect statuses used during Defect Management. |
| Typically Used By | QA Engineers, Developers, Project Managers                                   |
| Updated When      | Defect workflow or status definitions change.                                |

---

## Objective

The objective of Defect Status is to provide a consistent and shared understanding of each stage in the defect management process.

---

## Common Defect Statuses

### New

The defect has been reported and is awaiting review or assignment.

---

### Assigned

The defect has been assigned to the appropriate developer or team for investigation.

---

### In Progress

The assigned developer is currently investigating or implementing a solution.

---

### Fixed

The developer has implemented a fix, and the defect is ready for QA retesting.

---

### Retest

The QA team is verifying whether the implemented fix resolves the reported issue.

---

### Verified

The defect has been successfully retested, and the reported issue no longer occurs.

---

### Closed

The defect has been resolved, verified, and formally completed.

---

### Reopened

The reported issue still exists after being marked as Fixed or Verified and requires additional investigation.

---

### Duplicate

The reported defect already exists in the issue tracking system and is linked to an existing record.

---

### Deferred

The defect is acknowledged but scheduled for resolution in a future release.

---

### Rejected

The reported issue is determined not to be a valid software defect.

Examples include expected system behavior or incorrect test expectations.

---

### Cannot Reproduce

The development or QA team cannot consistently reproduce the reported issue using the available information.

Additional details may be required before further investigation.

---

### Won't Fix

The team decides not to resolve the defect because the impact is acceptable, the implementation risk outweighs the benefit, or the affected functionality is scheduled for replacement.

---

## Status Summary

| Status           | Description                              |
| ---------------- | ---------------------------------------- |
| New              | Defect reported.                         |
| Assigned         | Assigned for investigation.              |
| In Progress      | Fix is being developed.                  |
| Fixed            | Fix completed and awaiting retest.       |
| Retest           | QA is validating the fix.                |
| Verified         | Fix confirmed successful.                |
| Closed           | Defect completed.                        |
| Reopened         | Issue still exists after a fix.          |
| Duplicate        | Already reported elsewhere.              |
| Deferred         | Resolution postponed.                    |
| Rejected         | Not considered a valid defect.           |
| Cannot Reproduce | Unable to reproduce the issue.           |
| Won't Fix        | Decision made not to resolve the defect. |

---

## Benefits

* Standardizes defect tracking.
* Improves communication across teams.
* Reduces confusion about workflow progress.
* Supports accurate project reporting.
* Maintains consistent defect documentation.

---

## Best Practices

#### Tracking

* Update defect statuses promptly.
* Use statuses consistently across the project.
* Avoid skipping workflow stages without justification.

#### Communication

* Explain status changes when necessary.
* Document reasons for non-standard statuses such as Deferred or Won't Fix.
* Ensure QA and development teams share the same status definitions.

---

## In Practice

A QA engineer reports a defect and marks it as **New**.

After review, the defect is **Assigned** to a developer, who investigates the issue and marks it as **In Progress**.

Once a fix is implemented, the status changes to **Fixed**.

The QA engineer performs **Retest**, confirms that the issue has been resolved, marks it as **Verified**, and finally closes the defect as **Closed**.

---

## Developer Tips

* Keep defect statuses accurate and up to date.
* Avoid marking defects as Fixed until implementation is complete.
* Communicate clearly when changing defect statuses.
* Provide investigation notes when appropriate.
* Reopen defects if issues persist after verification.

---

## Common Mistakes

* Using statuses inconsistently.
* Closing defects before verification.
* Leaving defects in outdated statuses.
* Marking defects as Fixed without completing implementation.
* Selecting Cannot Reproduce without sufficient investigation.

---

## Summary

Defect Status provides a standardized way to communicate the progress of software defects throughout their lifecycle.

Using consistent status definitions helps improve collaboration, project visibility, and the overall effectiveness of the defect management process.

---

## Related Guides

* Defect Management
* Defect Life Cycle
* Bug Report
* Severity vs Priority
* Test Execution

---

**Next:** [Test Metrics →](../07-test-metrics/test-metrics.md)
