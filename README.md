# Test Scripts

Automated scripts used to verify software functionality, validate code behavior, and ensure quality through repeatable testing procedures. Test scripts encode testing logic in executable form, enabling continuous integration pipelines to run validation automatically on every code change. They support unit testing, integration testing, end-to-end testing, contract testing, performance testing, and security scanning across REST, GraphQL, SOAP, and gRPC APIs.

**URL:** [https://en.wikipedia.org/wiki/Test_automation](https://en.wikipedia.org/wiki/Test_automation)

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

| Name | Description |
|---|---|
| [Postman API](https://www.postman.com/postman/postman-public-workspace/) | Programmatic access to Postman collections, environments, monitors, and test scripts for CI/CD integration. |
| [Newman CLI](https://github.com/postmanlabs/newman) | Command-line tool for running Postman collections and test scripts in CI/CD pipelines. |
| [Karate API Testing Framework](https://karatelabs.github.io/karate/) | Open-source BDD framework combining API automation, mocks, and performance testing in Gherkin syntax. |
| [REST Assured](https://rest-assured.io/) | Java DSL for BDD-style scripting to validate REST API responses, headers, and payloads. |
| [Dredd API Testing Framework](https://dredd.org/) | Language-agnostic CLI tool that validates API implementations against OpenAPI or API Blueprint specs. |
| [k6 Performance Testing](https://k6.io/) | Modern load-testing tool using JavaScript test scripts to simulate concurrent API users. |
| [Playwright Test](https://playwright.dev/) | Cross-browser end-to-end testing framework supporting API testing scripts in multiple languages. |
| [Cypress](https://www.cypress.io/) | JavaScript end-to-end testing framework with real-time test runner for API and browser automation. |
| [Schemathesis](https://schemathesis.io/) | Property-based testing tool that auto-generates test scripts from OpenAPI/GraphQL schemas. |

## Artifacts

| Type | URL |
|---|---|
| JSON Schema | [test-scripts-schema.json](json-schema/test-scripts-schema.json) |
| JSON Structure | [test-scripts-structure.json](json-structure/test-scripts-structure.json) |
| JSON-LD Context | [test-scripts-context.jsonld](json-ld/test-scripts-context.jsonld) |
| Vocabulary | [test-scripts-vocabulary.yml](vocabulary/test-scripts-vocabulary.yml) |

## Examples

| Name | Description |
|---|---|
| [API Contract Test Example](examples/test-script-api-contract-example.json) | Contract test script verifying GET /users returns 200 with schema-compliant response. |
| [Performance Test Example](examples/test-script-performance-example.json) | k6 performance test script validating search API under 100 concurrent users. |
