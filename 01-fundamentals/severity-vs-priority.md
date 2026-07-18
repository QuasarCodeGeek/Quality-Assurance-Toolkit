# Severity vs Priority

> **Difficulty:** Beginner
>
> **Estimated Reading Time:** 6 minutes
>
> **Prerequisites:**
>
> * Defect Life Cycle

## Overview

Severity and Priority are two important attributes used to classify software defects. Although they are closely related, they measure different aspects of a defect and serve different purposes during defect management.

Understanding the difference between severity and priority helps development and QA teams make informed decisions about which defects should be fixed first and how much impact they have on the system.

---

## Severity

Severity measures the impact of a defect on the application's functionality.

It answers the question:

> **How serious is the defect?**

Severity is typically determined by the QA team based on how much the defect affects the software.

### Common Severity Levels

| Level    | Description                                                                 |
| -------- | --------------------------------------------------------------------------- |
| Critical | Causes complete system failure, data loss, or major security issues.        |
| High     | A major feature does not function correctly.                                |
| Medium   | Functionality is affected, but a workaround exists.                         |
| Low      | Minor issue with little impact on functionality, such as cosmetic problems. |

---

## Priority

Priority determines how quickly a defect should be addressed.

It answers the question:

> **How urgently should the defect be fixed?**

Priority is usually determined by the product owner, project manager, or business stakeholders based on business needs.

### Common Priority Levels

| Level  | Description                                              |
| ------ | -------------------------------------------------------- |
| High   | Must be fixed immediately or before release.             |
| Medium | Should be resolved during the current development cycle. |
| Low    | Can be scheduled for a future release.                   |

---

## Key Differences

| Aspect        | Severity                  | Priority                        |
| ------------- | ------------------------- | ------------------------------- |
| Measures      | Technical impact          | Business urgency                |
| Focus         | Software functionality    | Release planning                |
| Determined By | QA Team                   | Product Owner / Project Manager |
| Question      | How serious is the issue? | How soon should it be fixed?    |

---

## Severity and Priority Matrix

| Severity | Priority | Example                                                                             |
| -------- | -------- | ----------------------------------------------------------------------------------- |
| Critical | High     | Application crashes during startup.                                                 |
| High     | Medium   | A major feature fails, but a temporary workaround exists.                           |
| Low      | High     | Company logo is incorrect on the production homepage before a major product launch. |
| Low      | Low      | Minor UI alignment issue on an internal settings page.                              |

---

## Benefits

* Helps teams prioritize defect resolution effectively.
* Improves communication between technical and business teams.
* Supports efficient release planning.
* Reduces the impact of critical defects on users.

---

## Best Practices

#### Severity Assessment

* Evaluate the actual impact on system functionality.
* Consider security, performance, and data integrity.
* Be consistent when assigning severity levels.

#### Priority Assessment

* Consider business deadlines and customer impact.
* Discuss priorities with stakeholders.
* Reassess priorities when project requirements change.

---

## In Practice

Consider an e-commerce application during a major promotional sale.

A spelling mistake appears on the homepage banner. Although the defect has **Low Severity** because it does not affect functionality, it receives **High Priority** because it is highly visible to customers during an important business event.

Meanwhile, a rarely used administrative report fails to export correctly. The defect has **High Severity** because important functionality is broken, but it may receive **Medium Priority** if it does not immediately affect customers.

These examples demonstrate that severity and priority are related but should always be evaluated independently.

---

## Developer Tips

* Do not confuse technical impact with business urgency.
* Assign severity consistently using established guidelines.
* Review priorities regularly with stakeholders.
* Document the reason for unusually high or low priorities.
* Focus on fixing critical defects before optimizing minor issues.

---

## Common Mistakes

* Treating severity and priority as the same concept.
* Assigning every defect the highest severity.
* Ignoring business impact when setting priorities.
* Changing severity to influence development schedules.
* Failing to review priorities as project requirements evolve.

---

## Summary

Severity measures how much a defect affects the software, while priority determines how urgently it should be resolved.

Understanding both concepts enables development and QA teams to make better decisions, allocate resources effectively, and deliver higher-quality software.

---

## Related Guides

* Defect Life Cycle
* Bug Report
* Test Execution
* Regression Testing
* Risk-Based Testing

---

**Next:** [Test Strategy →](../02-planning/test-strategy.md)
