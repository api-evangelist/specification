# Specification

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
