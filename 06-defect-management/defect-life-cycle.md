# Defect Life Cycle

> **Difficulty:** Beginner
>
> **Estimated Reading Time:** 8 minutes
>
> **Prerequisites:**
>
> * Defect Management
> * Bug Report
> * Severity vs Priority

## Overview

The Defect Life Cycle is the sequence of statuses that a software defect passes through from the time it is discovered until it is resolved and closed.

It provides a standardized workflow for managing defects, improving communication among team members, and ensuring that every reported issue is tracked to completion.

Although the exact workflow varies between organizations and issue tracking systems, the core lifecycle remains largely consistent across software projects.

---

## Document Information

| Attribute         | Description                                                                                |
| ----------------- | ------------------------------------------------------------------------------------------ |
| Purpose           | Defines the workflow for tracking and managing software defects from discovery to closure. |
| Typically Used By | QA Engineers, Developers, Project Managers                                                 |
| Updated When      | Defect management workflows or project processes change.                                   |

---

## Objective

The objective of the Defect Life Cycle is to provide a consistent and traceable process for managing software defects throughout their resolution.

---

## Typical Defect Life Cycle

A typical defect progresses through the following stages:

```text
New
↓
Assigned
↓
In Progress
↓
Fixed
↓
Retest
↓
Verified
↓
Closed
```

Depending on project needs, a defect may also follow alternative paths such as **Rejected**, **Duplicate**, **Deferred**, **Cannot Reproduce**, or **Won't Fix**.

---

## Common Defect Statuses

| Status      | Description                                              |
| ----------- | -------------------------------------------------------- |
| New         | The defect has been reported and awaits review.          |
| Assigned    | The defect has been assigned to a developer.             |
| In Progress | Investigation or implementation of a fix is underway.    |
| Fixed       | A fix has been implemented and is ready for retesting.   |
| Retest      | QA verifies the implemented fix.                         |
| Verified    | The fix has been confirmed to resolve the defect.        |
| Closed      | The defect has been successfully resolved and completed. |

---

## Alternative Statuses

Some projects also use additional statuses:

| Status           | Description                                                      |
| ---------------- | ---------------------------------------------------------------- |
| Reopened         | The defect still exists after being marked as fixed or verified. |
| Duplicate        | The defect has already been reported elsewhere.                  |
| Deferred         | The fix is postponed to a future release.                        |
| Rejected         | The reported issue is not considered a valid defect.             |
| Cannot Reproduce | The reported issue cannot be reproduced.                         |
| Won't Fix        | The team decides not to resolve the defect.                      |

---

## Key Deliverables

| Activity          | Deliverable           |
| ----------------- | --------------------- |
| Defect Tracking   | Updated Defect Status |
| Defect Resolution | Verified Fix          |
| Defect Closure    | Closed Defect Record  |

---

## Benefits

* Standardizes defect tracking.
* Improves communication across teams.
* Provides visibility into defect progress.
* Supports release planning.
* Maintains a complete history of defect resolution.

---

## Best Practices

#### Tracking

* Update defect status promptly.
* Keep investigation notes accurate and complete.
* Track defects until final closure.

#### Verification

* Retest every implemented fix.
* Perform regression testing when necessary.
* Reopen defects if issues persist.

#### Collaboration

* Communicate status changes clearly.
* Resolve blockers early.
* Review recurring defect patterns during retrospectives.

---

## In Practice

A QA engineer reports a defect after discovering that users cannot submit an online registration form.

The defect is reviewed, assigned to a developer, investigated, and marked as **Fixed** after implementation.

The QA engineer performs retesting, confirms that the issue no longer occurs, and marks the defect as **Verified** before it is finally **Closed**.

---

## Developer Tips

* Update defect statuses consistently.
* Document investigation findings when appropriate.
* Notify QA when fixes are ready for retesting.
* Verify that changes do not introduce regressions.
* Reproduce reported defects before implementing fixes.

---

## Common Mistakes

* Skipping the retesting phase.
* Closing defects without verification.
* Leaving defects in outdated statuses.
* Marking defects as fixed without sufficient validation.
* Using inconsistent defect workflows across projects.

---

## Summary

The Defect Life Cycle defines the sequence of statuses a software defect follows from discovery through resolution and closure.

By following a consistent defect workflow, development teams can improve collaboration, maintain traceability, and ensure that reported issues are managed effectively.

---

## Related Guides

* Defect Management
* Bug Report
* Severity vs Priority
* Defect Status
* Test Execution

---

**Next:** [Defect Status →](defect-status.md)
