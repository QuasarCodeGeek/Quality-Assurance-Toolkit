# Defect Leakage

> **Difficulty:** Intermediate
>
> **Estimated Reading Time:** 7 minutes
>
> **Prerequisites:**
>
> * Test Metrics
> * Defect Management

## Overview

Defect Leakage is a software quality metric that measures the number of defects discovered after a software release compared to the total number of defects identified before and after release.

It helps evaluate the effectiveness of the testing process by indicating how many defects were not detected during planned testing activities.

A lower Defect Leakage generally indicates that testing was more effective in identifying defects before release.

---

## Document Information

| Attribute         | Description                                                                             |
| ----------------- | --------------------------------------------------------------------------------------- |
| Purpose           | Measures the effectiveness of testing by tracking defects found after software release. |
| Typically Used By | QA Engineers, QA Leads, Project Managers                                                |
| Updated When      | Production defects are reported or release quality is reviewed.                         |

---

## Objective

The objective of Defect Leakage is to evaluate how effectively testing activities identify defects before software is released to end users.

---

## Measuring Defect Leakage

Defect Leakage is commonly expressed as a percentage.

```text
Defect Leakage (%) =
(Post-Release Defects ÷ Total Defects) × 100
```

Where:

* **Post-Release Defects** are defects discovered after deployment.
* **Total Defects** are the combined defects found before and after release.

Organizations may use different calculation methods, so teams should consistently follow the metric defined by their organization.

---

## Example

A software release has:

* 95 defects discovered during testing
* 5 defects reported after deployment

```text
Total Defects = 95 + 5 = 100

Defect Leakage =
(5 ÷ 100) × 100 = 5%
```

This indicates that **5% of all identified defects escaped the testing process and were discovered after release.**

---

## Key Deliverables

| Activity            | Deliverable                         |
| ------------------- | ----------------------------------- |
| Release Analysis    | Defect Leakage Report               |
| Quality Monitoring  | QA Metrics Dashboard                |
| Process Improvement | Testing Improvement Recommendations |

---

## Benefits

* Measures testing effectiveness.
* Identifies weaknesses in the testing process.
* Supports continuous process improvement.
* Helps improve future release quality.
* Provides insight into production quality.

---

## Best Practices

#### Measurement

* Track production defects consistently.
* Use a standardized leakage calculation method.
* Compare results across multiple releases.

#### Analysis

* Investigate why defects escaped testing.
* Identify testing gaps and high-risk areas.
* Review recurring production issues.

#### Improvement

* Strengthen Test Cases for missed scenarios.
* Improve regression testing where necessary.
* Share lessons learned with the development team.

---

## In Practice

Following a software release, the support team reports several production defects that were not identified during testing.

The QA team calculates the project's Defect Leakage and reviews the escaped defects to determine why they were missed.

The findings are used to improve future Test Cases, expand regression testing, and strengthen release validation.

---

## Developer Tips

* Review production defects carefully to understand why they escaped testing.
* Strengthen automated and regression tests for recurring issues.
* Use Defect Leakage trends to improve development and testing practices.
* Focus on preventing similar production defects in future releases.
* Treat production defects as opportunities to improve software quality.

---

## Common Mistakes

* Tracking only testing defects while ignoring production issues.
* Calculating Defect Leakage using inconsistent methods.
* Focusing only on the percentage instead of analyzing root causes.
* Comparing releases with significantly different project scopes.
* Treating Defect Leakage as a measure of individual performance.

---

## Summary

Defect Leakage measures how many defects are discovered after software is released, providing valuable insight into the effectiveness of the testing process.

By analyzing Defect Leakage over time, teams can identify testing gaps, strengthen quality assurance practices, and continuously improve future software releases.

---

## Related Guides

* Test Metrics
* Test Coverage
* Defect Density
* Test Summary Report
* Defect Management

---

**Next:** [Test Summary Report →](test-summary-report.md)
