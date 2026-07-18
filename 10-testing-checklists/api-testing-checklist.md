# API Testing Checklist

> **Difficulty:** Intermediate
>
> **Estimated Reading Time:** 9 minutes
>
> **Prerequisites:**
>
> * Functional Testing
> * Test Execution
> * Basic Understanding of REST APIs

## Overview

This checklist provides a practical reference for verifying common behaviors of web APIs.

Unlike detailed API Test Cases, this checklist serves as a reusable guide to help QA engineers and developers validate functionality, reliability, security, and performance before an API is released or integrated into other systems.

Not every item applies to every API. Teams should customize this checklist based on the API's requirements, architecture, and business rules.

---

## Document Information

| Attribute         | Description                                            |
| ----------------- | ------------------------------------------------------ |
| Purpose           | Provides a reusable checklist for testing web APIs.    |
| Typically Used By | QA Engineers, Developers, Automation Testers           |
| Applied During    | API Testing, Integration Testing, Regression Testing   |
| Updated When      | API endpoints, business rules, or integrations change. |

---

## Objective

The objective of this checklist is to ensure that API endpoints behave correctly, securely, and consistently under expected and unexpected conditions.

---

# Pre-Testing

Verify the testing environment before executing API tests.

* [ ] Correct API version is deployed.
* [ ] Base URL is accessible.
* [ ] Required authentication credentials are available.
* [ ] Test data is prepared.
* [ ] API documentation is available.
* [ ] Required third-party services are operational.
* [ ] Database or dependent services are ready.

---

# Endpoint Validation

Verify each API endpoint.

* [ ] Correct HTTP method is used.
* [ ] Endpoint URL is correct.
* [ ] Required endpoints are available.
* [ ] Deprecated endpoints behave as documented.
* [ ] Invalid endpoints return appropriate responses.

---

# Request Validation

Verify request handling.

* [ ] Required parameters are validated.
* [ ] Optional parameters behave correctly.
* [ ] Invalid parameter values are rejected.
* [ ] Missing required fields return validation errors.
* [ ] Invalid data types are rejected.
* [ ] Boundary values are handled correctly.
* [ ] Empty request bodies are handled appropriately.

---

# Response Validation

Verify API responses.

* [ ] Correct HTTP status code is returned.
* [ ] Response body matches the expected schema.
* [ ] Returned data is accurate.
* [ ] Response headers are correct.
* [ ] Content-Type is correct.
* [ ] Error responses are meaningful and consistent.

---

# Authentication

Verify authentication mechanisms.

* [ ] Valid credentials are accepted.
* [ ] Invalid credentials are rejected.
* [ ] Missing authentication is handled correctly.
* [ ] Expired tokens are rejected.
* [ ] Revoked tokens are rejected.
* [ ] Token refresh works correctly (if applicable).

---

# Authorization

Verify access permissions.

* [ ] Users can access only authorized resources.
* [ ] Unauthorized requests return appropriate responses.
* [ ] Role-based access control is enforced.
* [ ] Sensitive endpoints require proper authorization.
* [ ] Users cannot access another user's data.

---

# CRUD Operations

Verify Create, Read, Update, and Delete operations.

* [ ] Create requests succeed.
* [ ] Read requests return expected data.
* [ ] Update requests modify existing data correctly.
* [ ] Delete requests remove data appropriately.
* [ ] Deleted resources behave according to business rules.

---

# Data Validation

Verify data integrity.

* [ ] Database records are created correctly.
* [ ] Updated values are stored correctly.
* [ ] Deleted records are handled correctly.
* [ ] Duplicate data is prevented when required.
* [ ] Relationships between records remain valid.

---

# Error Handling

Verify error scenarios.

* [ ] Invalid requests return appropriate error codes.
* [ ] Server errors are handled gracefully.
* [ ] Validation messages are informative.
* [ ] Sensitive system information is not exposed.
* [ ] Unexpected exceptions return consistent responses.

---

# Performance (Basic Verification)

Perform basic performance checks.

* [ ] Response time is acceptable.
* [ ] Large responses are handled correctly.
* [ ] Multiple consecutive requests succeed.
* [ ] API remains responsive under expected usage.

---

# Security (Basic Verification)

Perform basic security validation.

* [ ] HTTPS is enforced.
* [ ] Sensitive data is encrypted during transmission.
* [ ] Input validation prevents malicious requests.
* [ ] Authentication tokens are handled securely.
* [ ] Security headers are present where applicable.
* [ ] Rate limiting is enforced (if applicable).

---

# Documentation

Verify API documentation.

* [ ] Endpoints are documented.
* [ ] Request examples are accurate.
* [ ] Response examples are accurate.
* [ ] Error codes are documented.
* [ ] Authentication requirements are documented.

---

# Final Verification

Before completing testing:

* [ ] All planned API Test Cases have been executed.
* [ ] Critical defects have been reported.
* [ ] Fixed defects have been retested.
* [ ] Regression testing has been completed.
* [ ] Test evidence has been collected.
* [ ] Test results have been documented.
* [ ] Test Summary Report is prepared (if applicable).

---

## Best Practices

* Validate both successful and unsuccessful requests.
* Test boundary and invalid input values.
* Verify both authentication and authorization.
* Compare responses against the API specification.
* Automate repetitive API tests whenever practical.

---

## In Practice

A QA engineer is testing a REST API for an e-commerce platform.

Using this checklist, the engineer verifies authentication, authorization, CRUD operations, request validation, response consistency, error handling, documentation, and performance before approving the API for integration with the web and mobile applications.

---

## Common Mistakes

* Testing only successful requests.
* Ignoring invalid input scenarios.
* Skipping authorization testing.
* Not validating response schemas.
* Overlooking error messages and status codes.
* Ignoring API documentation accuracy.
* Treating the checklist as a replacement for API Test Cases.

---

## Summary

An API Testing Checklist provides a structured reference for verifying the functionality, security, reliability, and consistency of web APIs.

When used alongside API Test Cases and project-specific requirements, it helps teams identify defects early and improve confidence before integrating or releasing API services.

---

## Related Guides

* Integration Testing
* Functional Testing
* Test Cases
* Test Execution
* Authentication & Authorization Checklist

---

**Next:** [Authentication & Authorization Checklist →](authentication-and-authorization-checklist.md)
