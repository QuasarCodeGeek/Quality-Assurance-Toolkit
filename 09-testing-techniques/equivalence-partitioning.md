# Equivalence Partitioning (EP)

> **Difficulty:** Intermediate
>
> **Estimated Reading Time:** 8 minutes
>
> **Prerequisites:**
>
> * Boundary Value Analysis (BVA)
> * Test Cases

## Overview

Equivalence Partitioning (EP) is a black-box test design technique that divides input data into groups, known as **equivalence classes**, where each value within a group is expected to behave similarly.

Instead of testing every possible input, testers select one representative value from each equivalence class. This reduces the total number of Test Cases while maintaining reasonable testing coverage.

Equivalence Partitioning is commonly used for input validation, business rules, numeric ranges, and categorical data.

---

## Document Information

| Attribute         | Description                                                           |
| ----------------- | --------------------------------------------------------------------- |
| Purpose           | Reduces the number of Test Cases by grouping equivalent input values. |
| Typically Used By | QA Engineers, Test Analysts, Developers                               |
| Applied During    | Test Case Design                                                      |
| Commonly Used For | Input validation, business rule validation, form testing              |

---

## Objective

The objective of Equivalence Partitioning is to design efficient Test Cases by selecting representative values from groups of inputs that are expected to produce the same behavior.

---

## How Equivalence Partitioning Works

Inputs are divided into **valid** and **invalid** equivalence classes.

Rather than testing every possible value, one or more representative values are selected from each class.

If one value in an equivalence class behaves correctly, the remaining values in that same class are generally expected to behave the same way.

---

## Example

Suppose a user's age must be between **18 and 60**.

The input can be divided into the following equivalence classes:

| Equivalence Class | Example Value | Expected Result |
| ----------------- | ------------- | --------------- |
| Less than 18      | 15            | Rejected        |
| 18 to 60          | 30            | Accepted        |
| Greater than 60   | 65            | Rejected        |

Instead of testing every possible age, one representative value from each class is sufficient for this technique.

---

## Boundary Value Analysis vs Equivalence Partitioning

Although both techniques reduce testing effort, they focus on different aspects of input validation.

| Boundary Value Analysis                      | Equivalence Partitioning                       |
| -------------------------------------------- | ---------------------------------------------- |
| Tests values at input boundaries.            | Tests representative values from input groups. |
| Focuses on edge cases.                       | Focuses on input categories.                   |
| Best for detecting boundary-related defects. | Best for reducing the number of Test Cases.    |

These techniques are often used together to improve Test Case quality and coverage.

---

## When to Use Equivalence Partitioning

Equivalence Partitioning is effective when testing:

* Numeric ranges
* Input validation
* Dropdown selections
* Business rule validation
* File upload restrictions
* Category-based inputs

---

## Key Deliverables

| Activity      | Deliverable                  |
| ------------- | ---------------------------- |
| Test Design   | Equivalence Class Test Cases |
| Validation    | Input Validation Coverage    |
| Documentation | Updated Test Cases           |

---

## Benefits

* Reduces the number of Test Cases.
* Improves testing efficiency.
* Simplifies Test Case design.
* Provides systematic input coverage.
* Works well with Boundary Value Analysis.

---

## Best Practices

#### Test Design

* Identify both valid and invalid equivalence classes.
* Select representative values for each class.
* Combine Equivalence Partitioning with Boundary Value Analysis when appropriate.

#### Validation

* Verify expected behavior for every equivalence class.
* Consider business rules during partitioning.
* Update Test Cases when input rules change.

#### Maintenance

* Review equivalence classes after requirement updates.
* Reuse representative Test Cases where applicable.
* Keep documentation synchronized with current requirements.

---

## In Practice

An online shopping application allows customers to purchase between **1 and 10** items in a single order.

The QA engineer divides the inputs into three equivalence classes:

* Less than 1 item
* Between 1 and 10 items
* More than 10 items

Representative values from each class are then used to verify the application's validation rules.

---

## Developer Tips

* Clearly define valid and invalid input ranges.
* Ensure validation logic matches documented requirements.
* Review business rules before designing Test Cases.
* Use Equivalence Partitioning to minimize redundant tests.
* Combine multiple testing techniques for better coverage.

---

## Common Mistakes

* Treating every input as a separate Test Case.
* Defining incorrect equivalence classes.
* Ignoring invalid input groups.
* Using only valid representative values.
* Forgetting to update Test Cases when requirements change.

---

## Summary

Equivalence Partitioning is a black-box test design technique that groups similar inputs into equivalence classes and tests representative values from each group.

By reducing unnecessary Test Cases while maintaining meaningful coverage, it helps QA teams design efficient and effective software tests.

---

## Related Guides

* Boundary Value Analysis (BVA)
* Decision Table Testing
* Test Cases
* Functional Testing
* Requirement Types

---

**Next:** [Decision Table Testing →](decision-table-testing.md)
