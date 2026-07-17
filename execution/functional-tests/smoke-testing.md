# Smoke Testing

> **Difficulty:** Beginner
>
> **Estimated Reading Time:** 6 minutes
>
> **Prerequisites:**
>
> * Functional Testing
> * Test Execution

## Overview

Smoke Testing is a preliminary type of Functional Testing performed to verify that the most critical features of an application work correctly after a new build, deployment, or major update.

Its primary purpose is to determine whether the software is stable enough for more detailed testing. If critical functionality fails during Smoke Testing, further testing is typically postponed until the issues are resolved.

Smoke Testing is often referred to as a **Build Verification Test (BVT)** because it confirms that a software build is suitable for further testing.

---

## Document Information

| Attribute         | Description                                                                                      |
| ----------------- | ------------------------------------------------------------------------------------------------ |
| Purpose           | Verifies that the most critical application functionality works after a new build or deployment. |
| Typically Used By | QA Engineers, Developers                                                                         |
| Updated When      | Core application workflows or release processes change.                                          |

---

## Objective

The objective of Smoke Testing is to quickly determine whether a software build is stable enough to proceed with more comprehensive testing.

---

## Common Verification Areas

Smoke Testing typically verifies the application's most critical functionality, such as:

* Application startup
* User authentication
* Navigation between key pages
* Database connectivity
* Core business workflows
* Basic API communication (if applicable)

---

## Key Deliverables

| Activity             | Deliverable                |
| -------------------- | -------------------------- |
| Smoke Test Execution | Smoke Test Results         |
| Failed Verification  | Bug Reports                |
| Build Assessment     | Build Status (Pass / Fail) |

---

## Benefits

* Detects critical issues early.
* Prevents unnecessary detailed testing on unstable builds.
* Saves testing time and effort.
* Increases confidence before full test execution.
* Supports faster release validation.

---

## Best Practices

#### Planning

* Identify the application's critical functionality.
* Keep the Smoke Test suite concise.
* Update Smoke Tests when core features change.

#### Execution

* Execute Smoke Tests immediately after deployment or receiving a new build.
* Stop further testing if critical failures are detected.
* Report blocking defects promptly.

---

## In Practice

A new version of a web application is deployed to the testing environment.

Before executing the complete Test Case suite, the QA engineer verifies that users can access the application, log in successfully, navigate major pages, and perform basic business operations.

Since all critical checks pass, the team proceeds with detailed functional and regression testing.

---

## Developer Tips

* Execute Smoke Tests before handing builds to QA whenever possible.
* Prioritize stability of core application workflows.
* Resolve Smoke Test failures before implementing new features.
* Automate Smoke Tests for frequent deployments.

---

## Common Mistakes

* Including every Test Case in the Smoke Test suite.
* Continuing detailed testing despite critical Smoke Test failures.
* Ignoring failures in core functionality.
* Allowing the Smoke Test suite to become outdated.

---

## Summary

Smoke Testing is a quick validation process that verifies whether the most critical application functionality works correctly after a new build or deployment.

By identifying blocking issues early, Smoke Testing helps teams avoid wasting time testing unstable software and improves the overall efficiency of the testing process.

---

## Related Guides

* Functional Testing
* Sanity Testing
* Regression Testing
* Test Execution
* Software Testing Life Cycle (STLC)

---

**Next:** [Sanity Testing →](sanity-testing.md)
