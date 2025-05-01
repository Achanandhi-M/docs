---
id: Integration Testing
title:  FAQs on Keploy's Integration Testing
sidebar_label: Integration Testing
tags:
  - explanation
  - faq
  - Integration testing
---

Let's get to the heart of Keploy with some fun Q&A!


### 1. What is Keploy Integration Testing?

Keploy is an open-source testing platform designed to automatically generate test cases from existing API traffic. It allows users to record, replay, and compare API interactions, making it easier to write and maintain test suites.

### 2. How does Keploy Integration Testing work?

Keploy works by recording incoming API calls during normal operations. It then replays these interactions in a test environment and compares the results to the initial responses to detect regressions or unexpected behavior in the code.

### 3. Does Keploy Integration support mocking?

Yes, Keploy allows mocking external dependencies like databases and third-party services during test execution to ensure that tests run in isolation without relying on external systems.

### 4. What are the prerequisites for using Keploy Integration Testing?

To use Keploy, you need:

- A service or application that exposes APIs (e.g., REST or GraphQL).
- Keploy supports programming languages like Go, Node.js, Python, and Java, so the appropriate SDK for your environment should be installed.

### 5. Is Keploy Integration suitable for microservices architecture?

Yes, Keploy is designed to work in microservices-based environments. It can record and replay API calls across services, making it ideal for testing distributed systems.

### 6. Does Keploy Integration testing require code changes to integrate?

Keploy can be integrated without any changes to the application code. However, adding Keploy SDKs may offer more fine-grained control for specific use cases.

### 7. Can Keploy Integration testing help with CI/CD pipelines?

Yes, Keploy integrates with CI/CD pipelines to run automated tests on every commit or code change. This ensures that any regressions are detected early in the development process.

### 8. Is Keploy Integration testing scalable for large projects?

Keploy is designed to be scalable. It can handle high traffic volumes and complex services in large-scale distributed systems. It is efficient for generating and managing test cases across services.

### 9. Does Keploy Integration testing support testing legacy applications?

Yes, Keploy can be used to test legacy systems, especially if they expose APIs. It can record traffic and replay calls without needing to modify the legacy codebase.

### 10. Can Keploy Integration testing be used with databases?

Yes, Keploy can mock database responses during test replay. This helps isolate tests and ensures consistency during test execution.

### 11. Is Keploy Integration testing free to use?

Yes, Keploy is open-source and free to use under the Apache 2.0 license. You can also contribute to its development on GitHub.

### 12. Can I customize Keploy's Integration testing behavior for specific APIs?

Yes, Keploy provides configuration options to customize recording, replay, and comparison logic for specific APIs, giving users control over how their APIs are tested.