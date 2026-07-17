# Sanity Testing

> **Difficulty:** Beginner
>
> **Estimated Reading Time:** 6 minutes
>
> **Prerequisites:**
>
> * Functional Testing
> * Smoke Testing
> * Test Execution

## Overview

Sanity Testing is a type of Functional Testing performed after minor changes, bug fixes, or feature updates to verify that the affected functionality works as expected.

Unlike Smoke Testing, which evaluates the stability of an entire software build, Sanity Testing focuses only on the specific functionality that was modified.

Sanity Testing helps determine whether the recent changes are working correctly before broader testing activities continue.

---

## Document Information

| Attribute         | Description                                                                                      |
| ----------------- | ------------------------------------------------------------------------------------------------ |
| Purpose           | Verifies that recent changes or bug fixes function correctly without introducing obvious issues. |
| Typically Used By | QA Engineers, Developers                                                                         |
| Updated When      | Application features, bug fixes, or maintenance processes change.                                |

---

## Objective

The objective of Sanity Testing is to quickly validate that recent changes have been implemented correctly and that the affected functionality is ready for further testing.

---

## Common Verification Areas

Sanity Testing commonly focuses on:

* Recently fixed defects
* Modified features
* Updated business rules
* New validations
* Configuration changes
* Small enhancements

---

## Key Deliverables

| Activity              | Deliverable          |
| --------------------- | -------------------- |
| Sanity Test Execution | Sanity Test Results  |
| Failed Verification   | Bug Reports          |
| Change Validation     | Verification Results |

---

## Benefits

* Confirms that bug fixes work as intended.
* Verifies recent changes without executing the full test suite.
* Reduces unnecessary testing effort.
* Provides quick feedback to developers.
* Supports efficient regression planning.

---

## Best Practices

#### Planning

* Focus only on the affected functionality.
* Understand the scope of the implemented changes.
* Review the related Bug Reports or change requests.

#### Execution

* Verify both the implemented fix and closely related functionality.
* Report unexpected behavior immediately.
* Proceed with broader testing only after Sanity Testing succeeds.

---

## In Practice

A developer fixes a validation issue that prevented users from resetting their passwords.

Before executing a full Regression Test, the QA engineer verifies that the password reset process now works correctly, confirmation emails are sent successfully, and related validation rules behave as expected.

Once the affected functionality passes Sanity Testing, the team continues with additional testing activities.

---

## Developer Tips

* Clearly communicate the scope of implemented changes.
* Include sufficient information for QA to reproduce the fix.
* Perform local verification before submitting changes for testing.
* Consider nearby functionality that may also be affected.

---

## Common Mistakes

* Treating Sanity Testing as a full Regression Test.
* Testing unrelated application features.
* Skipping verification of adjacent functionality.
* Assuming that one successful test confirms the entire application is stable.

---

## Summary

Sanity Testing is a focused validation activity performed after bug fixes or minor changes to confirm that the affected functionality behaves as expected.

By concentrating only on the modified areas, Sanity Testing provides rapid feedback and helps teams determine whether broader testing should continue.

---

## Related Guides

* Smoke Testing
* Regression Testing
* Functional Testing
* Test Execution
* Bug Report

---

**Next:** [Regression Testing →](regression-testing.md)
