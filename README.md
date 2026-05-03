# Thought Industries

Thought Industries is a B2B learning platform (LMS/LXP) providing REST and GraphQL APIs for programmatic access to courses, users, enrollments, content management, and reporting. Their developer portal enables integration of learning experiences into enterprise workflows.

**Developer Portal:** [https://developer.thoughtindustries.com/](https://developer.thoughtindustries.com/)

## APIs

| Name | Description | Documentation |
|------|-------------|---------------|
| [Thought Industries REST API](https://developer.thoughtindustries.com/) | REST API v1 for users, courses, enrollments, groups, content, categories, and reporting. | [Docs](https://api.thoughtindustries.com/) |
| [Thought Industries GraphQL API](https://developer.thoughtindustries.com/graphql/) | GraphQL API for flexible querying of platform data with schema introspection. | [Docs](https://developer.thoughtindustries.com/graphql/) |

## Common Resources

- **Website:** [https://www.thoughtindustries.com/](https://www.thoughtindustries.com/)
- **Developer Portal:** [https://developer.thoughtindustries.com/](https://developer.thoughtindustries.com/)
- **Getting Started:** [https://developer.thoughtindustries.com/api-tutorials/](https://developer.thoughtindustries.com/api-tutorials/)
- **GitHub Organization:** [https://github.com/thoughtindustries](https://github.com/thoughtindustries)

## OpenAPI Specifications

| File | Description |
|------|-------------|
| [thought-industries-openapi.yml](openapi/thought-industries-openapi.yml) | REST API v1 covering users, courses, enrollments, groups, content, and reports |

## JSON Schemas

| File | Description |
|------|-------------|
| [thought-industries-user-schema.json](json-schema/thought-industries-user-schema.json) | Learner user account schema |
| [thought-industries-enrollment-schema.json](json-schema/thought-industries-enrollment-schema.json) | Course enrollment schema |

## JSON Structures

| File | Description |
|------|-------------|
| [thought-industries-user-structure.json](json-structure/thought-industries-user-structure.json) | User, enrollment, course, and response structure documentation |

## JSON-LD

| File | Description |
|------|-------------|
| [thought-industries-context.jsonld](json-ld/thought-industries-context.jsonld) | JSON-LD context mapping LMS vocabulary to schema.org |

## Examples

| File | Description |
|------|-------------|
| [thought-industries-list-users-example.json](examples/thought-industries-list-users-example.json) | List users request/response |
| [thought-industries-enroll-user-example.json](examples/thought-industries-enroll-user-example.json) | Enroll user request/response |

## Spectral Rules

| File | Description |
|------|-------------|
| [thought-industries-rules.yml](rules/thought-industries-rules.yml) | Spectral ruleset enforcing Thought Industries API conventions |

## Naftiko Capabilities

### Shared Definitions

| File | Description |
|------|-------------|
| [capabilities/shared/rest-api.yaml](capabilities/shared/rest-api.yaml) | Per-API consumed definition for Thought Industries REST API |

### Workflow Capabilities

| File | Description | Tools |
|------|-------------|-------|
| [capabilities/learning-management.yaml](capabilities/learning-management.yaml) | Learning management for users, courses, enrollments, groups, and reporting | 12 tools |

## Vocabulary

| File | Description |
|------|-------------|
| [thought-industries-vocabulary.yml](vocabulary/thought-industries-vocabulary.yml) | Domain vocabulary for LMS and learning management concepts |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com

---

*Profiled by [API Evangelist](https://apievangelist.com) on 2026-05-03*
