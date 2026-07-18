# Severity vs Priority

> **Difficulty:** Beginner
>
> **Estimated Reading Time:** 7 minutes
>
> **Prerequisites:**
>
> * Defect Management
> * Bug Report

## Overview

Severity and Priority are two important attributes used during Defect Management to help teams evaluate software defects.

Although they are closely related, they measure different aspects of a defect.

**Severity** indicates the technical impact of a defect on the application's functionality, while **Priority** indicates how urgently the defect should be resolved based on business needs.

Understanding the difference helps development teams make informed decisions when scheduling defect fixes.

---

## Document Information

| Attribute         | Description                                                               |
| ----------------- | ------------------------------------------------------------------------- |
| Purpose           | Explains how Severity and Priority are used to classify software defects. |
| Typically Used By | QA Engineers, Developers, Project Managers                                |
| Updated When      | Defect classification guidelines change.                                  |

---

## Objective

The objective of Severity and Priority classification is to help teams evaluate the impact and urgency of software defects so they can be managed consistently and efficiently.

---

## Severity

Severity measures **how much a defect affects the software's functionality or stability**.

It is primarily based on the technical impact of the defect rather than business considerations.

### Common Severity Levels

| Level    | Description                                                                 |
| -------- | --------------------------------------------------------------------------- |
| Critical | Causes system failure, data loss, or prevents core functionality.           |
| High     | Major functionality is unavailable or behaves incorrectly.                  |
| Medium   | Functionality works with limitations or has noticeable issues.              |
| Low      | Minor issues with little impact on functionality, such as cosmetic defects. |

---

## Priority

Priority measures **how urgently a defect should be fixed**.

It is determined by business needs, project timelines, customer impact, and release planning.

### Common Priority Levels

| Level  | Description                                                           |
| ------ | --------------------------------------------------------------------- |
| High   | Requires immediate attention and should be fixed as soon as possible. |
| Medium | Should be fixed during the current development cycle.                 |
| Low    | Can be scheduled for a future release if necessary.                   |

---

## Severity vs Priority

| Aspect        | Severity                 | Priority                                 |
| ------------- | ------------------------ | ---------------------------------------- |
| Measures      | Technical impact         | Business urgency                         |
| Focus         | Software functionality   | Release planning                         |
| Determined By | QA Engineers, Developers | QA Leads, Project Managers, Stakeholders |
| Can Change?   | Rarely                   | Frequently                               |

---

## Common Scenarios

| Severity | Priority | Example                                                                       |
| -------- | -------- | ----------------------------------------------------------------------------- |
| Critical | High     | Users cannot log in to the application.                                       |
| Low      | High     | Company logo is incorrect on the production homepage before a product launch. |
| High     | Low      | A rarely used administrative feature fails but has a temporary workaround.    |
| Low      | Low      | Minor spelling mistake in a settings page.                                    |

---

## Key Deliverables

| Activity             | Deliverable             |
| -------------------- | ----------------------- |
| Defect Assessment    | Severity Classification |
| Release Planning     | Priority Assignment     |
| Defect Documentation | Updated Bug Report      |

---

## Benefits

* Supports consistent defect classification.
* Helps teams prioritize development work.
* Improves release planning.
* Enhances communication among stakeholders.
* Enables more effective resource allocation.

---

## Best Practices

#### Classification

* Evaluate Severity based on technical impact.
* Evaluate Priority based on business needs.
* Review classifications when project priorities change.

#### Collaboration

* Discuss unclear classifications with the development team.
* Involve stakeholders when business impact is uncertain.
* Apply classification standards consistently across projects.

---

## In Practice

During testing, a QA engineer discovers that the company logo displayed on the application's homepage is outdated.

Although the issue has little impact on functionality, the application is scheduled for a public product launch the following day.

The defect is classified as **Low Severity** because functionality is unaffected, but **High Priority** because it must be corrected before release.

---

## Developer Tips

* Focus on Severity when assessing technical risk.
* Consider Priority when planning implementation.
* Review both attributes before scheduling work.
* Communicate if defect classification appears inaccurate.
* Reassess Priority as project deadlines change.

---

## Common Mistakes

* Treating Severity and Priority as the same concept.
* Assigning Priority based only on technical impact.
* Ignoring business requirements during prioritization.
* Using inconsistent classification criteria.
* Failing to review Priority when project conditions change.

---

## Summary

Severity and Priority classify software defects from two different perspectives.

Severity measures the technical impact of a defect, while Priority determines how urgently it should be resolved.

Using both classifications consistently helps teams make informed decisions, improve planning, and deliver higher-quality software.

---

## Related Guides

* Defect Management
* Bug Report
* Defect Life Cycle
* Defect Status
* Test Execution

---

**Next:** [Defect Life Cycle →](defect-life-cycle.md)
