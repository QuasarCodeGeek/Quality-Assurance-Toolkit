# Boundary Value Analysis (BVA)

> **Difficulty:** Intermediate
>
> **Estimated Reading Time:** 8 minutes
>
> **Prerequisites:**
>
> * Test Cases
> * Requirement Types

## Overview

Boundary Value Analysis (BVA) is a black-box test design technique that focuses on testing values at the boundaries of valid input ranges.

Experience has shown that defects are more likely to occur at the edges of input limits rather than within the middle of a valid range. By testing these boundary values, QA teams can identify validation errors that might otherwise go unnoticed.

Boundary Value Analysis is commonly used when testing numeric ranges, dates, string lengths, file sizes, and other inputs with defined minimum and maximum limits.

---

## Document Information

| Attribute         | Description                                                       |
| ----------------- | ----------------------------------------------------------------- |
| Purpose           | Verifies system behavior at the boundaries of valid input ranges. |
| Typically Used By | QA Engineers, Test Analysts, Developers                           |
| Applied During    | Test Case Design                                                  |
| Commonly Used For | Input validation, form validation, API validation                 |

---

## Objective

The objective of Boundary Value Analysis is to identify defects that occur at the minimum and maximum limits of valid input values.

---

## How Boundary Value Analysis Works

When an input has a defined range, testing should include values:

* Just below the minimum boundary
* At the minimum boundary
* Within the valid range
* At the maximum boundary
* Just above the maximum boundary

Testing these values helps verify that the application correctly accepts valid inputs and rejects invalid ones.

---

## Example

Suppose a user's age must be between **18 and 60**.

A typical set of Boundary Value Analysis test inputs would be:

| Test Value | Expected Result |
| ---------- | --------------- |
| 17         | Rejected        |
| 18         | Accepted        |
| 30         | Accepted        |
| 60         | Accepted        |
| 61         | Rejected        |

Rather than testing every possible age, Boundary Value Analysis focuses on the values that are most likely to reveal defects.

---

## When to Use Boundary Value Analysis

Boundary Value Analysis is most effective when testing:

* Numeric input ranges
* Date ranges
* String length limits
* Password length requirements
* File size restrictions
* Quantity or inventory limits

---

## Key Deliverables

| Activity      | Deliverable               |
| ------------- | ------------------------- |
| Test Design   | Boundary Value Test Cases |
| Validation    | Input Validation Coverage |
| Documentation | Test Case Updates         |

---

## Benefits

* Reduces the number of required Test Cases.
* Improves input validation testing.
* Identifies boundary-related defects efficiently.
* Supports systematic Test Case design.
* Increases confidence in validation logic.

---

## Best Practices

#### Test Design

* Test both valid and invalid boundary values.
* Include values immediately outside the valid range.
* Verify both minimum and maximum limits.

#### Validation

* Confirm expected system responses.
* Test error messages for invalid inputs.
* Consider business rules alongside technical limits.

#### Maintenance

* Update boundary tests when requirements change.
* Reuse Boundary Value Test Cases where applicable.
* Combine BVA with other testing techniques for broader coverage.

---

## In Practice

An online registration form accepts usernames between 6 and 20 characters.

The QA engineer designs Test Cases using usernames with 5, 6, 10, 20, and 21 characters to verify that the application correctly enforces the specified length requirements.

---

## Developer Tips

* Clearly define input limits during implementation.
* Validate both client-side and server-side inputs.
* Review boundary conditions during code reviews.
* Ensure validation rules match documented requirements.
* Consider edge cases when implementing business logic.

---

## Common Mistakes

* Testing only valid boundary values.
* Ignoring values just outside the valid range.
* Assuming user interface validation is sufficient.
* Overlooking boundary conditions in APIs.
* Forgetting to update tests after requirement changes.

---

## Summary

Boundary Value Analysis is a black-box testing technique that focuses on values at the edges of valid input ranges.

By testing boundary conditions rather than every possible input, teams can efficiently identify validation defects while reducing the number of required Test Cases.

---

## Related Guides

* Equivalence Partitioning
* Black-Box Testing
* Test Cases
* Input Validation
* Requirement Types

---

**Next:** [Equivalence Partitioning →](equivalence-partitioning.md)
