# Decision Table Testing

> **Difficulty:** Intermediate
>
> **Estimated Reading Time:** 8 minutes
>
> **Prerequisites:**
>
> * Equivalence Partitioning (EP)
> * Test Cases

## Overview

Decision Table Testing is a black-box test design technique used to verify software behavior when the outcome depends on multiple conditions or business rules.

It organizes different combinations of conditions and their expected actions into a structured table, helping testers identify missing or inconsistent business logic.

Decision Table Testing is commonly used for systems that involve validations, permissions, pricing rules, workflows, and approval processes.

---

## Document Information

| Attribute         | Description                                                                           |
| ----------------- | ------------------------------------------------------------------------------------- |
| Purpose           | Verifies software behavior based on combinations of conditions and expected outcomes. |
| Typically Used By | QA Engineers, Test Analysts, Business Analysts                                        |
| Applied During    | Test Case Design                                                                      |
| Commonly Used For | Business rules, workflows, permissions, validations                                   |

---

## Objective

The objective of Decision Table Testing is to ensure that every meaningful combination of conditions produces the correct system behavior.

---

## How Decision Table Testing Works

A decision table consists of four main parts:

| Component        | Description                                                           |
| ---------------- | --------------------------------------------------------------------- |
| Conditions       | Inputs or business rules that influence system behavior.              |
| Condition Values | The possible values for each condition, such as Yes/No or True/False. |
| Actions          | The expected system responses.                                        |
| Rules            | Unique combinations of conditions and their corresponding actions.    |

Each column in the decision table represents a test scenario that can be converted into one or more Test Cases.

---

## Example

A user can access the Admin Dashboard only when:

* The user is authenticated.
* The user has the Administrator role.

| Conditions / Actions | Rule 1 | Rule 2 | Rule 3 | Rule 4 |
| -------------------- | :----: | :----: | :----: | :----: |
| User Authenticated   |   Yes  |   Yes  |   No   |   No   |
| Administrator Role   |   Yes  |   No   |   Yes  |   No   |
| **Access Granted**   |    ✅   |    ❌   |    ❌   |    ❌   |

Each rule represents a different scenario that should be verified during testing.

---

## When to Use Decision Table Testing

Decision Table Testing is particularly useful for:

* Authentication and authorization
* Discount calculations
* Loan or insurance approvals
* Order processing
* Tax calculations
* Business workflows
* Feature permissions

---

## Key Deliverables

| Activity      | Deliverable               |
| ------------- | ------------------------- |
| Rule Analysis | Decision Table            |
| Test Design   | Decision-Based Test Cases |
| Validation    | Business Rule Coverage    |

---

## Benefits

* Improves coverage of business rules.
* Reduces missed condition combinations.
* Simplifies complex decision logic.
* Supports systematic Test Case design.
* Improves communication with business stakeholders.

---

## Best Practices

#### Test Design

* Identify all relevant conditions.
* Eliminate impossible or invalid combinations.
* Create Test Cases for each meaningful rule.

#### Validation

* Verify expected actions for every rule.
* Review decision tables with stakeholders.
* Update decision tables when business rules change.

#### Maintenance

* Keep decision tables synchronized with requirements.
* Reuse decision tables for regression testing.
* Document assumptions and exceptions.

---

## In Practice

An e-commerce platform applies discounts based on customer membership and promotional coupons.

The QA engineer creates a decision table covering all valid combinations of membership status and coupon availability.

Each rule becomes one or more Test Cases to verify that discounts are calculated correctly.

---

## Developer Tips

* Review business rules before implementation.
* Keep decision logic simple and maintainable.
* Collaborate with QA when defining complex conditions.
* Ensure application behavior matches documented rules.
* Consider edge cases and invalid combinations.

---

## Common Mistakes

* Ignoring certain condition combinations.
* Including impossible scenarios in the decision table.
* Testing only the most common business paths.
* Failing to update decision tables after requirement changes.
* Overcomplicating simple validation rules.

---

## Summary

Decision Table Testing is a black-box test design technique that verifies software behavior across different combinations of business conditions.

By organizing conditions and expected actions into a structured table, teams can improve testing completeness, reduce missed scenarios, and validate complex business rules more effectively.

---

## Related Guides

* Boundary Value Analysis (BVA)
* Equivalence Partitioning (EP)
* State Transition Testing
* Test Cases
* Requirement Types

---

**Next:** [State Transition Testing →](state-transition-testing.md)
