# Test Execution

> **Difficulty:** Intermediate
>
> **Estimated Reading Time:** 8 minutes
>
> **Prerequisites:**
>
> * Test Cases
> * Test Data
> * Software Testing Life Cycle (STLC)

## Overview

Test Execution is the phase of the Software Testing Life Cycle (STLC) where prepared Test Cases are executed using the defined Test Data to verify that the software behaves as expected.

During this phase, testers record the actual results, compare them with the expected results, identify defects, and provide objective evidence of the application's quality.

Test Execution serves as the primary validation activity before software is approved for release.

---

## Document Information

| Attribute             | Description                                                                    |
| --------------------- | ------------------------------------------------------------------------------ |
| Purpose               | Verifies that software functions as expected by executing prepared Test Cases. |
| Typically Created By  | QA Engineer                                                                    |
| Typically Reviewed By | QA Lead                                                                        |
| Typically Used By     | QA Team, Developers, Project Managers                                          |
| Updated When          | Test execution progresses or execution results change.                         |

---

## Objective

The objective of Test Execution is to validate that the software behaves as expected by executing planned Test Cases, documenting execution results, and identifying defects that require resolution.

---

## Key Activities

### Execute Test Cases

Execute approved Test Cases according to the Test Plan using the prepared Test Data and record the outcome of each execution.

### Record Actual Results

Document the application's observed behavior, including any deviations from the expected results.

### Compare Results

Compare the Actual Result with the Expected Result to determine whether the Test Case passes or fails.

### Report Defects

Create Bug Reports for failed Test Cases or unexpected system behavior.

### Retest Fixed Defects

Re-execute affected Test Cases after reported defects have been resolved.

### Perform Regression Testing

Verify that recent changes have not introduced new defects into existing functionality.

---

## Test Execution Status

The outcome of each Test Case is commonly recorded using one of the following statuses.

| Status       | Description                                                       |
| ------------ | ----------------------------------------------------------------- |
| Pass         | The Actual Result matches the Expected Result.                    |
| Fail         | The Actual Result does not match the Expected Result.             |
| Blocked      | Execution cannot continue due to an external dependency or issue. |
| Not Executed | The Test Case has not yet been executed.                          |
| Skipped      | The Test Case was intentionally not executed.                     |

These statuses help track testing progress, identify blocked work, and provide visibility into the overall quality of the software throughout the execution phase.

---

## Key Deliverables

| Activity        | Deliverable            |
| --------------- | ---------------------- |
| Test Execution  | Test Execution Results |
| Failed Tests    | Bug Reports            |
| Retesting       | Verification Results   |
| Test Completion | Test Execution Report  |

---

## Benefits

* Validates software functionality against requirements.
* Identifies defects before software release.
* Provides objective evidence of software quality.
* Measures testing progress and execution coverage.
* Supports release readiness decisions.

---

## Best Practices

#### Execution

* Execute Test Cases exactly as documented.
* Use the prepared Test Data consistently throughout execution.
* Record complete and accurate execution results.

#### Defect Reporting

* Report defects immediately after discovery.
* Include clear reproduction steps and supporting evidence.
* Link defects to the related Test Cases whenever possible.

#### Tracking

* Monitor execution progress regularly.
* Retest resolved defects promptly.
* Keep execution status up to date.

---

## In Practice

A QA engineer executes the prepared Test Cases for a new software release using the approved Test Data.

Some Test Cases pass successfully, while others fail due to validation issues or unexpected application behavior.

The failed Test Cases are documented as Bug Reports. After developers resolve the reported defects, the QA engineer performs retesting and regression testing before confirming that the release is ready for deployment.

---

## Developer Tips

* Review failed Test Cases before investigating reported defects.
* Reproduce issues using the same Test Data whenever possible.
* Validate implemented fixes before submitting them for QA verification.
* Consider regression impacts when implementing code changes.
* Collaborate with QA to clarify unexpected behavior.

---

## Common Mistakes

* Executing outdated Test Cases.
* Using incorrect or outdated Test Data.
* Recording incomplete execution results.
* Closing defects without verification.
* Skipping regression testing after bug fixes.

---

## Summary

Test Execution is the process of executing prepared Test Cases to verify that software behaves according to its expected requirements.

Accurate execution, thorough documentation, and timely defect reporting enable development teams to assess software quality and determine whether an application is ready for release.

---

## Related Guides

* Software Testing Types
* Test Cases
* Test Data
* Regression Testing
* Bug Report

---

**Next:** [Software Testing Types →](../03-software-testing-types/software-testing-types.md)
