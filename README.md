# Test Scripts (test-scripts)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
