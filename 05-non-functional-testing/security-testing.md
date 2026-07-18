# Security Testing

> **Difficulty:** Intermediate
>
> **Estimated Reading Time:** 7 minutes
>
> **Prerequisites:**
>
> * Non-Functional Testing
> * Test Execution

## Overview

Security Testing is a type of Non-Functional Testing that evaluates whether a software application protects its data, users, and system resources against unauthorized access, misuse, and security threats.

Its primary purpose is to verify that security controls function as intended and that the application satisfies its defined security requirements.

Security Testing helps reduce security risks before software is deployed to production.

---

## Document Information

| Attribute         | Description                                                                          |
| ----------------- | ------------------------------------------------------------------------------------ |
| Purpose           | Verifies that the application's security controls protect data and system resources. |
| Typically Used By | QA Engineers, Security Engineers, Developers                                         |
| Updated When      | Security requirements, authentication mechanisms, or system architecture change.     |

---

## Objective

The objective of Security Testing is to validate that the application protects sensitive information, enforces security controls, and resists common security threats according to its defined requirements.

---

## Common Verification Areas

Security Testing commonly verifies:

* Authentication
* Authorization
* Password policies
* Session management
* Input validation
* Data encryption
* Secure communication (HTTPS/TLS)
* Error handling for security-sensitive operations

---

## Key Deliverables

| Activity                | Deliverable                  |
| ----------------------- | ---------------------------- |
| Security Test Execution | Security Test Results        |
| Security Findings       | Security Defect Reports      |
| Security Validation     | Security Test Summary Report |

---

## Benefits

* Identifies security weaknesses before deployment.
* Protects sensitive user and business data.
* Reduces security risks and vulnerabilities.
* Improves stakeholder confidence.
* Supports compliance with security requirements.

---

## Best Practices

#### Planning

* Define security requirements early.
* Identify sensitive data and critical business functions.
* Include security testing throughout the development lifecycle.

#### Execution

* Verify authentication and authorization rules.
* Validate input handling and error responses.
* Confirm that sensitive data is protected during storage and transmission.

---

## In Practice

A company develops an online banking application.

During Security Testing, the QA team verifies that users can access only their own accounts, passwords are handled securely, sessions expire appropriately after inactivity, sensitive data is transmitted over secure connections, and invalid or malicious inputs are handled safely without exposing sensitive system information.

---

## Developer Tips

* Follow secure coding practices.
* Validate all user input on the server.
* Apply the principle of least privilege.
* Protect sensitive data using appropriate encryption.
* Avoid exposing internal system details through error messages.

---

## Common Mistakes

* Treating Security Testing as a one-time activity.
* Relying only on authentication while neglecting authorization.
* Storing or transmitting sensitive data insecurely.
* Ignoring input validation.
* Exposing sensitive information through logs or error messages.

---

## Summary

Security Testing evaluates whether a software application adequately protects its users, data, and system resources through effective security controls.

By validating authentication, authorization, data protection, and other security requirements, development teams can reduce vulnerabilities and improve the overall security posture of their applications.

---

## Related Guides

* Non-Functional Testing
* Performance Testing
* Compatibility Testing
* Test Execution
* Risk Assessment

---

**Next:** [Compatibility Testing →](compatibility-testing.md)
