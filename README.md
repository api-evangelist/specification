# Specification

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

A subject-matter collection covering the API specification landscape — the formats, standards, tooling, and practices around machine-readable API contracts. Includes OpenAPI, AsyncAPI, JSON Schema, Arazzo, GraphQL SDL, Protocol Buffers, and the methodology of specification-first API development.

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

API Design, API Governance, AsyncAPI, Contract Testing, JSON Schema, OpenAPI, Specifications, Standards

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-05-02

## Covered Specifications

| Format | Maintainer | Use Case |
|---|---|---|
| [OpenAPI](https://www.openapis.org/) | OpenAPI Initiative | REST API description, code generation, documentation |
| [AsyncAPI](https://www.asyncapi.com/) | AsyncAPI Initiative | Event-driven and messaging APIs |
| [JSON Schema](https://json-schema.org/) | JSON Schema Org | Data validation and API request/response schemas |
| [Arazzo](https://spec.openapis.org/arazzo/latest.html) | OpenAPI Initiative | Multi-step API workflow sequences |
| GraphQL SDL | GraphQL Foundation | GraphQL type system definitions |
| Protocol Buffers | Google | gRPC API definitions |

## Artifacts

### JSON Schema

- [specification-openapi-schema.json](json-schema/specification-openapi-schema.json) — Schema for API specification metadata applicable across formats

### JSON Structure

- [specification-structure.json](json-structure/specification-structure.json) — Taxonomy of the API specification format landscape

### JSON-LD

- [specification-context.jsonld](json-ld/specification-context.jsonld) — JSON-LD context mapping specification vocabulary to linked data semantics

### Vocabulary

- [specification-vocabulary.yml](vocabulary/specification-vocabulary.yml) — Domain vocabulary covering API specification concepts, formats, and practices

## Key Concepts

- **Specification-First Development** — API contract authored before implementation
- **Contract Testing** — Validating implementation against specification
- **Code Generation** — Generating SDKs, stubs, and clients from specs
- **Linting** — Enforcing style and governance rules on specifications
- **Breaking Changes** — Incompatible modifications requiring version bumps

## Resources

- [OpenAPI Initiative](https://www.openapis.org/)
- [AsyncAPI Initiative](https://www.asyncapi.com/)
- [JSON Schema Organization](https://json-schema.org/)
- [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI Tools Directory](https://openapi.tools/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
