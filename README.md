# Test Scripts (test-scripts)

Automated scripts used to verify software functionality, validate code behavior, and ensure quality through repeatable testing procedures. Test scripts encode testing logic in executable form, enabling continuous integration pipelines to run validation automatically on every code change. They support unit testing, integration testing, end-to-end testing, contract testing, performance testing, and security scanning across REST, GraphQL, SOAP, and gRPC APIs.

**APIs.json:** [https://en.wikipedia.org/wiki/Test_automation](https://en.wikipedia.org/wiki/Test_automation)

## Tags

- Automation
- CI/CD
- Contract Testing
- Quality Assurance
- Software Development
- Testing

## Timestamps

- **Created:** 2025
- **Modified:** 2026-05-03

## APIs

### Postman API

The Postman API enables programmatic access to Postman collections, environments, monitors, and test scripts. It allows teams to manage and execute API test scripts as part of CI/CD pipelines, retrieve test run results, and integrate Postman with other DevOps tooling.

- **Human URL:** [https://www.postman.com/postman/postman-public-workspace/](https://www.postman.com/postman/postman-public-workspace/)
- **Base URL:** `https://api.getpostman.com`

#### Tags

- API Testing
- Collections
- Test Execution

#### Properties

- [Documentation](https://learning.postman.com/docs/introduction/overview/)
- [OpenAPI](https://www.postman.com/postman/postman-public-workspace/api/72a32ca1-f3a2-4a5e-91f2-token) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/test-scripts.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/test-scripts.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Newman CLI

Newman is the command-line companion for Postman, enabling Postman collections and test scripts to be run directly from the terminal or integrated into CI/CD pipelines such as GitHub Actions, Jenkins, and GitLab CI.

- **Human URL:** [https://github.com/postmanlabs/newman](https://github.com/postmanlabs/newman)
- **Base URL:** `https://github.com/postmanlabs/newman`

#### Tags

- CLI
- CI/CD
- Test Execution

#### Properties

- [Documentation](https://learning.postman.com/docs/collections/using-newman-cli/command-line-integration-with-newman/)
- [Git Hub Org](https://github.com/postmanlabs/newman)
- [Postman Collection](collections/test-scripts.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/test-scripts.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Karate API Testing Framework

Karate is an open-source framework that combines API test automation, mocks, performance testing, and UI automation into a single framework. Test scripts are written in plain-text Gherkin syntax, making them readable by non-programmers while offering powerful assertion and data-driven capabilities.

- **Human URL:** [https://karatelabs.github.io/karate/](https://karatelabs.github.io/karate/)
- **Base URL:** `https://karatelabs.github.io/karate/`

#### Tags

- BDD
- Gherkin
- API Testing
- Test Automation

#### Properties

- [Documentation](https://karatelabs.github.io/karate/)
- [Git Hub Org](https://github.com/karatelabs/karate)
- [Postman Collection](collections/test-scripts.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/test-scripts.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### REST Assured

REST Assured is a Java-based DSL for simplifying testing of REST services. It integrates with JUnit and TestNG, and supports BDD-style test scripting with a fluent API for validating HTTP responses, headers, and JSON/XML payloads.

- **Human URL:** [https://rest-assured.io/](https://rest-assured.io/)
- **Base URL:** `https://rest-assured.io/`

#### Tags

- Java
- BDD
- REST
- Test Automation

#### Properties

- [Documentation](https://github.com/rest-assured/rest-assured/wiki/Usage)
- [Git Hub Org](https://github.com/rest-assured/rest-assured)
- [Postman Collection](collections/test-scripts.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/test-scripts.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dredd API Testing Framework

Dredd is an open-source language-agnostic command-line tool for validating API documentation written in OpenAPI or API Blueprint against its backend implementation. It reads test scripts derived from API specifications and automatically verifies that server responses match documented behavior.

- **Human URL:** [https://dredd.org/](https://dredd.org/)
- **Base URL:** `https://dredd.org/`

#### Tags

- Contract Testing
- OpenAPI
- Test Automation

#### Properties

- [Documentation](https://dredd.org/en/latest/)
- [Git Hub Org](https://github.com/apiaryio/dredd)
- [Postman Collection](collections/test-scripts.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/test-scripts.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### k6 Performance Testing

k6 is a modern load-testing tool that uses JavaScript test scripts to simulate concurrent users hitting APIs. Its scripting model allows teams to write reusable, version-controlled performance test scripts that integrate natively with CI/CD pipelines and output detailed performance metrics.

- **Human URL:** [https://k6.io/](https://k6.io/)
- **Base URL:** `https://api.k6.io`

#### Tags

- Load Testing
- Performance Testing
- JavaScript
- Test Automation

#### Properties

- [Documentation](https://grafana.com/docs/k6/latest/)
- [OpenAPI](https://grafana.com/docs/k6/latest/misc/k6-rest-api/) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/test-scripts.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/test-scripts.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Playwright Test

Playwright is a cross-browser end-to-end testing framework from Microsoft that supports writing test scripts in JavaScript, TypeScript, Python, Java, and .NET. It is widely used for API testing, browser automation, and full-stack integration test scripting in CI/CD pipelines.

- **Human URL:** [https://playwright.dev/](https://playwright.dev/)
- **Base URL:** `https://playwright.dev/`

#### Tags

- End-to-End Testing
- Browser Automation
- JavaScript
- Test Automation

#### Properties

- [Documentation](https://playwright.dev/docs/intro)
- [Git Hub Org](https://github.com/microsoft/playwright)
- [Postman Collection](collections/test-scripts.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/test-scripts.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cypress

Cypress is a JavaScript end-to-end testing framework designed for modern web applications. Its test scripting API supports both API testing and browser automation, with real-time test runner feedback and built-in parallelization for CI/CD environments.

- **Human URL:** [https://www.cypress.io/](https://www.cypress.io/)
- **Base URL:** `https://www.cypress.io/`

#### Tags

- End-to-End Testing
- JavaScript
- Test Automation

#### Properties

- [Documentation](https://docs.cypress.io/)
- [Git Hub Org](https://github.com/cypress-io/cypress)
- [Postman Collection](collections/test-scripts.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/test-scripts.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Schemathesis

Schemathesis is a property-based testing tool for web APIs. It reads OpenAPI or GraphQL schemas and automatically generates test scripts to discover edge cases, crashes, and specification violations through stateful, hypothesis-driven testing.

- **Human URL:** [https://schemathesis.io/](https://schemathesis.io/)
- **Base URL:** `https://schemathesis.io/`

#### Tags

- Property-Based Testing
- OpenAPI
- Fuzz Testing

#### Properties

- [Documentation](https://schemathesis.readthedocs.io/)
- [Git Hub Org](https://github.com/schemathesis/schemathesis)
- [Postman Collection](collections/test-scripts.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/test-scripts.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Git Hub Org](https://github.com/api-evangelist/test-scripts)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/test-scripts/main/json-schema/test-scripts-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/test-scripts/main/json-structure/test-scripts-structure.json)
- [J S O N L D Context](https://raw.githubusercontent.com/api-evangelist/test-scripts/main/json-ld/test-scripts-context.jsonld)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/test-scripts/main/vocabulary/test-scripts-vocabulary.yml)
