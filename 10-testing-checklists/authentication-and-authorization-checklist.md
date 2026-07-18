# Authentication & Authorization Checklist

> **Difficulty:** Intermediate
>
> **Estimated Reading Time:** 9 minutes
>
> **Prerequisites:**
>
> * Functional Testing
> * Security Testing
> * Test Execution

## Overview

This checklist provides a practical reference for verifying authentication and authorization features commonly found in modern applications.

Authentication confirms a user's identity, while authorization determines what resources or actions that authenticated user is permitted to access.

Because authentication and authorization are critical to application security, these features should be thoroughly verified before every software release.

---

## Document Information

| Attribute         | Description                                                                            |
| ----------------- | -------------------------------------------------------------------------------------- |
| Purpose           | Provides a reusable checklist for verifying authentication and authorization features. |
| Typically Used By | QA Engineers, Developers, Security Testers                                             |
| Applied During    | Functional Testing, Security Testing, Regression Testing                               |
| Updated When      | Authentication methods, user roles, or security requirements change.                   |

---

## Objective

The objective of this checklist is to ensure that users can securely authenticate themselves and access only the resources and functionality permitted by their assigned roles and permissions.

---

# Authentication

Verify user authentication.

* [ ] Users can log in using valid credentials.
* [ ] Invalid credentials are rejected.
* [ ] Appropriate error messages are displayed.
* [ ] Password fields are masked.
* [ ] Password visibility toggle works correctly (if applicable).
* [ ] Login is case-sensitive where required.
* [ ] Users cannot log in with disabled or inactive accounts.
* [ ] Session is created successfully after login.

---

# Account Registration

Verify account creation.

* [ ] Required fields are validated.
* [ ] Duplicate accounts are prevented.
* [ ] Email format validation works.
* [ ] Password policy is enforced.
* [ ] Email verification works (if applicable).
* [ ] Account activation behaves correctly.

---

# Password Management

Verify password-related functionality.

* [ ] Forgot Password process works.
* [ ] Password Reset succeeds.
* [ ] Expired reset links are rejected.
* [ ] Invalid reset tokens are rejected.
* [ ] Password complexity rules are enforced.
* [ ] Password confirmation is validated.
* [ ] Previously used passwords are restricted (if applicable).

---

# Session Management

Verify user sessions.

* [ ] Session starts after successful login.
* [ ] Logout terminates the session.
* [ ] Session timeout works correctly.
* [ ] Expired sessions require reauthentication.
* [ ] Browser Back button does not restore protected pages after logout.
* [ ] Simultaneous sessions follow business rules.
* [ ] Session cookies are handled securely.

---

# Multi-Factor Authentication (MFA)

If MFA is implemented, verify:

* [ ] MFA challenge appears after login.
* [ ] Correct verification codes are accepted.
* [ ] Invalid verification codes are rejected.
* [ ] Expired verification codes are rejected.
* [ ] Backup or recovery methods work correctly.
* [ ] Users cannot bypass MFA.

---

# Authorization

Verify access permissions.

* [ ] Users can access only authorized pages.
* [ ] Unauthorized pages return appropriate responses.
* [ ] Navigation respects assigned roles.
* [ ] Hidden features cannot be accessed directly.
* [ ] Restricted API endpoints reject unauthorized requests.
* [ ] User interface elements respect permissions.

---

# Role-Based Access Control (RBAC)

Verify user roles.

* [ ] Administrator permissions.
* [ ] Manager permissions.
* [ ] Standard User permissions.
* [ ] Read-only permissions (if applicable).
* [ ] Guest access (if applicable).

For each role, verify:

* [ ] Accessible pages.
* [ ] Allowed actions.
* [ ] Restricted actions.
* [ ] Data visibility.

---

# Data Protection

Verify access to sensitive information.

* [ ] Users cannot access another user's data.
* [ ] Direct URL manipulation is prevented.
* [ ] Sensitive information is hidden from unauthorized users.
* [ ] Download permissions are enforced.
* [ ] Export permissions follow business rules.

---

# Error Handling

Verify authentication and authorization failures.

* [ ] Invalid login attempts return appropriate errors.
* [ ] Unauthorized access returns proper status codes.
* [ ] Sensitive information is not exposed in error messages.
* [ ] Locked accounts are handled correctly.
* [ ] Excessive failed login attempts follow security policies.

---

# Security (Basic Verification)

Perform basic security validation.

* [ ] HTTPS is enforced.
* [ ] Passwords are never stored or displayed in plain text.
* [ ] Authentication tokens are protected.
* [ ] Session identifiers change after login where appropriate.
* [ ] User input is validated.
* [ ] Authentication cookies are configured securely.

---

# Final Verification

Before completing testing:

* [ ] All authentication Test Cases have been executed.
* [ ] All authorization Test Cases have been executed.
* [ ] Critical security defects have been reported.
* [ ] Fixed issues have been retested.
* [ ] Regression testing has been completed.
* [ ] Test evidence has been documented.

---

## Best Practices

* Test using multiple user roles.
* Verify both successful and unsuccessful authentication scenarios.
* Include expired sessions and invalid credentials in testing.
* Confirm authorization rules at both the user interface and API levels.
* Retest authentication after major security-related changes.

---

## In Practice

A QA engineer is testing a human resources management system with multiple user roles.

Using this checklist, the engineer verifies user registration, login, password management, session handling, role-based access control, restricted pages, API authorization, and secure handling of sensitive employee information before approving the release.

---

## Common Mistakes

* Testing only administrator accounts.
* Ignoring unauthorized access attempts.
* Forgetting session timeout verification.
* Not testing password reset functionality.
* Assuming hidden pages are inaccessible.
* Skipping API authorization testing.
* Treating the checklist as a replacement for detailed security Test Cases.

---

## Summary

An Authentication & Authorization Checklist provides a structured reference for verifying user identity, access control, and permission management across an application.

When used alongside project-specific Test Cases, it helps teams identify security issues early, reduce unauthorized access risks, and improve confidence before software is released.

---

## Related Guides

* Security Testing
* Functional Testing
* Test Cases
* API Testing Checklist
* Release Readiness Checklist

---

**Next:** [Regression Testing Checklist →](regression-testing-checklist.md)
