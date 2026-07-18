# Web Application Testing Checklist

> **Difficulty:** Beginner
>
> **Estimated Reading Time:** 10 minutes
>
> **Prerequisites:**
>
> * Functional Testing
> * Non-Functional Testing
> * Test Execution

## Overview

This checklist provides a practical reference for testing common features found in modern web applications.

Unlike Test Cases, which verify specific requirements, this checklist serves as a general guide to help QA engineers and developers remember important areas that should be verified before releasing a web application.

Not every item applies to every project. Teams should customize the checklist based on project requirements, business rules, and application scope.

---

## Document Information

| Attribute         | Description                                                                       |
| ----------------- | --------------------------------------------------------------------------------- |
| Purpose           | Provides a reusable checklist for verifying common web application functionality. |
| Typically Used By | QA Engineers, Developers, Project Managers                                        |
| Applied During    | Functional Testing, Regression Testing, Release Testing                           |
| Updated When      | New application features or testing requirements are introduced.                  |

---

## Objective

The objective of this checklist is to improve testing consistency by ensuring that common web application features are verified before deployment.

---

# Pre-Testing

Verify the testing environment before executing any test cases.

* [ ] Correct application version is deployed.
* [ ] Test environment is available.
* [ ] Required test accounts are prepared.
* [ ] Test data is available.
* [ ] Browser cache has been cleared if necessary.
* [ ] Third-party services are accessible.
* [ ] Database is prepared for testing.

---

# Authentication

Verify user authentication features.

* [ ] User can register successfully.
* [ ] User can log in with valid credentials.
* [ ] Invalid credentials display appropriate error messages.
* [ ] Password masking works correctly.
* [ ] Forgot Password process functions correctly.
* [ ] Password Reset works as expected.
* [ ] Logout ends the user session.
* [ ] Session timeout functions correctly.
* [ ] Remember Me behaves as intended (if applicable).
* [ ] Multi-Factor Authentication (MFA) works correctly (if applicable).

---

# Authorization

Verify access permissions.

* [ ] Users can access only authorized pages.
* [ ] Unauthorized pages return appropriate responses.
* [ ] Navigation respects user roles.
* [ ] Hidden features cannot be accessed directly via URL.
* [ ] API endpoints enforce authorization rules.

---

# Forms & Input Validation

Verify user input handling.

* [ ] Required fields are enforced.
* [ ] Optional fields behave correctly.
* [ ] Input length validation works.
* [ ] Accepted input formats are enforced.
* [ ] Invalid data displays helpful error messages.
* [ ] Duplicate submissions are prevented.
* [ ] Form resets function correctly.
* [ ] Client-side validation works.
* [ ] Server-side validation works.

---

# Navigation

Verify navigation throughout the application.

* [ ] Navigation menus function correctly.
* [ ] Internal links work.
* [ ] External links open correctly.
* [ ] Breadcrumbs are accurate (if applicable).
* [ ] Back and Forward browser buttons behave correctly.
* [ ] Page refresh does not produce unexpected behavior.

---

# CRUD Operations

Verify Create, Read, Update, and Delete functionality.

* [ ] Records can be created.
* [ ] Records can be viewed.
* [ ] Records can be edited.
* [ ] Records can be deleted.
* [ ] Confirmation dialogs appear when required.
* [ ] Deleted records are handled correctly.
* [ ] Data persists after refresh.

---

# Search, Filter & Sorting

Verify data retrieval features.

* [ ] Search returns correct results.
* [ ] Empty search behaves correctly.
* [ ] Partial keyword search works.
* [ ] Filters return expected data.
* [ ] Sorting works for supported columns.
* [ ] Pagination functions correctly.

---

# File Upload & Download

Verify file handling.

* [ ] Valid files upload successfully.
* [ ] Invalid file types are rejected.
* [ ] File size limits are enforced.
* [ ] Duplicate uploads behave correctly.
* [ ] Uploaded files can be downloaded.
* [ ] Downloaded files are correct and complete.

---

# Session Management

Verify user sessions.

* [ ] Session expires after inactivity.
* [ ] Session persists when expected.
* [ ] Multiple tabs behave correctly.
* [ ] Simultaneous logins follow business rules.
* [ ] Logout invalidates active sessions.

---

# Error Handling

Verify application responses during failures.

* [ ] Validation errors are clear.
* [ ] Unexpected errors are handled gracefully.
* [ ] Custom error pages display correctly.
* [ ] Stack traces are not exposed.
* [ ] Sensitive information is not displayed.

---

# Browser Compatibility

Verify supported browsers.

* [ ] Google Chrome
* [ ] Microsoft Edge
* [ ] Mozilla Firefox
* [ ] Safari (if supported)

For each supported browser, verify:

* [ ] Layout
* [ ] Functionality
* [ ] Forms
* [ ] Navigation
* [ ] File Upload
* [ ] JavaScript behavior

---

# Responsive Design

Verify supported screen sizes.

* [ ] Desktop
* [ ] Laptop
* [ ] Tablet
* [ ] Mobile

For each device size, verify:

* [ ] Layout adjusts correctly.
* [ ] Text remains readable.
* [ ] Navigation remains usable.
* [ ] Buttons remain accessible.
* [ ] Horizontal scrolling is not introduced unnecessarily.

---

# Performance (Basic Verification)

Perform basic performance checks.

* [ ] Pages load within acceptable time.
* [ ] Images load correctly.
* [ ] Large tables remain usable.
* [ ] Loading indicators appear when expected.
* [ ] No unnecessary delays are observed.

---

# Security (Basic Verification)

Perform basic security validation.

* [ ] HTTPS is enforced.
* [ ] Sensitive pages require authentication.
* [ ] Passwords are never displayed in plain text.
* [ ] User input is validated.
* [ ] File upload restrictions are enforced.
* [ ] Session cookies behave securely.
* [ ] Direct URL access is restricted appropriately.

---

# Accessibility (Basic Verification)

Verify basic accessibility requirements.

* [ ] Images include alternative text where appropriate.
* [ ] Keyboard navigation works.
* [ ] Form labels are properly associated.
* [ ] Color contrast is readable.
* [ ] Focus indicators are visible.

---

# Final Verification

Before completing testing:

* [ ] All planned Test Cases have been executed.
* [ ] Critical defects have been reported.
* [ ] Fixed defects have been retested.
* [ ] Regression testing has been completed.
* [ ] Test evidence has been collected.
* [ ] Test results have been documented.
* [ ] Test Summary Report is prepared (if applicable).

---

## Best Practices

* Customize this checklist based on project requirements.
* Remove items that are not applicable.
* Add project-specific verification points.
* Use this checklist together with detailed Test Cases.
* Review and update the checklist after each release.

---

## In Practice

A QA engineer is preparing to test a new customer portal before release.

Rather than relying solely on memory, the engineer uses this checklist to systematically verify authentication, authorization, CRUD operations, browser compatibility, responsiveness, file uploads, session management, security, accessibility, and final release readiness.

Using a standardized checklist helps ensure that common functionality is consistently verified across every release.

---

## Common Mistakes

* Assuming every project requires the same checklist.
* Skipping regression verification.
* Forgetting browser compatibility testing.
* Ignoring responsive layouts.
* Overlooking session management.
* Testing only happy paths.
* Treating the checklist as a replacement for Test Cases.

---

## Summary

A Web Application Testing Checklist provides a structured reference for verifying the most common functionality found in modern web applications.

When used alongside Test Cases and project-specific requirements, it helps improve testing consistency, reduce missed scenarios, and increase confidence before software is released.

---

## Related Guides

* Functional Testing
* Regression Testing
* Test Cases
* Test Execution
* Release Readiness Checklist

---

**Next:** [Mobile Application Testing Checklist →](mobile-application-testing-checklist.md)
