# Quality Assurance (QA) vs Quality Control (QC)

> **Difficulty:** Beginner
>
> **Estimated Reading Time:** 5 minutes
>
> **Prerequisites:** None

## Overview

Quality Assurance (QA) and Quality Control (QC) are closely related concepts in software development, but they serve different purposes.

**Quality Assurance (QA)** focuses on improving and maintaining the processes used to develop software. Its primary goal is to prevent defects before they occur by establishing standards, guidelines, and best practices throughout the Software Development Life Cycle (SDLC).

**Quality Control (QC)** focuses on evaluating the final product by identifying defects through various testing activities. Its goal is to detect and correct issues before the software is released to end users.

In simple terms:

> **QA prevents defects. QC finds defects.**

Both are essential to delivering reliable, maintainable, and high-quality software.

---

## Quality Assurance (QA)

Quality Assurance is **process-oriented**.

It focuses on improving the way software is developed by establishing standards and preventing issues before implementation.

### Typical QA Activities

* Define coding standards
* Review software requirements
* Create test strategies and test plans
* Conduct design and code reviews
* Establish CI/CD pipelines
* Monitor development processes
* Continuously improve workflows

### Objective

Prevent defects before they are introduced into the software.

---

## Quality Control (QC)

Quality Control is **product-oriented**.

It evaluates the software through testing to verify that it meets the expected requirements and quality standards.

### Typical QC Activities

* Manual Testing
* Automated Testing
* Functional Testing
* Regression Testing
* Performance Testing
* Security Testing
* User Acceptance Testing (UAT)
* Bug Verification

### Objective

Detect and report defects before software reaches end users.

---

## Key Differences

| Aspect         | Quality Assurance (QA)       | Quality Control (QC)      |
| -------------- | ---------------------------- | ------------------------- |
| Focus          | Process                      | Product                   |
| Objective      | Prevent defects              | Detect defects            |
| Approach       | Proactive                    | Reactive                  |
| Responsibility | Entire development team      | QA/Test Engineers         |
| Timing         | Throughout development       | During testing            |
| Outcome        | Improved development process | Verified software quality |

---

## Best Practices

#### Development Process
- Start QA at the beginning of the project.
- Treat testing as a continuous activity.
- Review requirements before writing code.

#### Testing
- Automate repetitive tests whenever possible.
#### Documentation
- Document known issues and resolutions.
- Continuously improve development processes.

---

## Common Misconceptions

### "QA is just testing."

Testing is only one component of software quality. QA covers the entire development process.

### "Only QA Engineers are responsible for quality."

Software quality is a shared responsibility among developers, testers, designers, project managers, and stakeholders.

### "More bugs found means better QA."

The ultimate goal of QA is to prevent defects, not simply discover more of them.

---

## In Practice

Consider the development of a new software application.

### Quality Assurance (QA)

Before development begins, the team:

* Reviews business and technical requirements.
* Defines coding standards and development guidelines.
* Creates a testing strategy and test plan.
* Establishes version control and CI/CD workflows.
* Performs design and code reviews.
* Documents development processes and best practices.

These activities help reduce the likelihood of introducing defects during development.

### Quality Control (QC)

Once features are implemented, the team:

* Verifies that requirements are met.
* Tests core application functionality.
* Validates user inputs and edge cases.
* Confirms bug fixes through regression testing.
* Tests the application across supported devices or browsers.
* Reports and tracks defects until they are resolved.

These activities ensure the software functions correctly and is ready for release.


---

## Developer Tips

* Understand requirements before writing code.
* Keep features small and testable.
* Write unit tests whenever practical.
* Review pull requests before merging.
* Automate repetitive regression tests.
* Run smoke tests before deployment.
* Keep documentation synchronized with implementation.

---

## Common Mistakes

* Treating QA as the final phase of development.
* Skipping requirement reviews.
* Deploying without smoke testing.
* Ignoring edge cases and invalid user inputs.
* Relying solely on manual testing.
* Fixing bugs without adding regression tests.
* Focusing only on happy path scenarios.

---

## Summary

Quality Assurance ensures that software is built using effective and consistent development processes, while Quality Control verifies that the finished product meets the expected quality standards.

Together, QA and QC form a continuous quality management approach that helps teams deliver reliable, maintainable, and user-focused software.

---

## Related Guides

- Software Testing Principles
- Software Testing Life Cycle (STLC)
- Test Strategy
- Smoke Testing
- Regression Testing

---

**Next:** [Software Testing Principles →](testing-principles.md)