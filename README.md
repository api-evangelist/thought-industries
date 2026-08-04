# Thought Industries (thought-industries)

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

Thought Industries is a B2B learning platform (LMS/LXP) providing REST and GraphQL APIs for programmatic access to courses, users, enrollments, content management, and reporting. Their developer portal enables integration of learning experiences into enterprise workflows with webhook support and comprehensive API coverage for user lifecycle, content, and analytics.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/thought-industries/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/thought-industries/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Education
- Learning
- LMS
- LXP
- E-Learning
- Training

## Timestamps

- **Created:** 2025-03-01
- **Modified:** 2026-05-19

## APIs

### Thought Industries REST API

The Thought Industries REST API v1 provides programmatic access to users, enrollments, courses, groups, content, categories, bundles, reports, and learning paths. Authentication uses API key via X-API-Key header or apiKey query parameter. Base URL is tenant-scoped at https://{subdomain}.thoughtindustries.com/incoming/api/v1/.

- **Human URL:** [https://developer.thoughtindustries.com/](https://developer.thoughtindustries.com/)
- **Base URL:** `https://{subdomain}.thoughtindustries.com/incoming/api/v1`

#### Tags

- Education
- Learning
- LMS
- REST
- Users
- Courses
- Enrollments

#### Properties

- [Documentation](https://api.thoughtindustries.com/)
- [Getting Started](https://developer.thoughtindustries.com/api-tutorials/)
- [Authentication](https://developer.thoughtindustries.com/api-tutorials/)
- [OpenAPI](openapi/thought-industries-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/thought-industries.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/thought-industries.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/thought-industries-user-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/thought-industries-enrollment-schema.json) — [JSON Schema](https://json-schema.org/specification)

### Thought Industries GraphQL API

The Thought Industries GraphQL API provides flexible querying of platform data including courses, users, content, and enrollments. Available at /incoming/api/graphql with schema introspection supported. Complements the REST API for complex queries and mutations.

- **Human URL:** [https://developer.thoughtindustries.com/graphql/](https://developer.thoughtindustries.com/graphql/)
- **Base URL:** `https://{subdomain}.thoughtindustries.com/incoming/api`

#### Tags

- GraphQL
- Learning
- Education
- LMS

#### Properties

- [Documentation](https://developer.thoughtindustries.com/graphql/)
- [Getting Started](https://developer.thoughtindustries.com/api-tutorials/)
- [Postman Collection](collections/thought-industries.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/thought-industries.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/thought-industries)
- [Website](https://www.thoughtindustries.com/)
- [Developer Portal](https://developer.thoughtindustries.com/)
- [Documentation](https://api.thoughtindustries.com/)
- [Getting Started](https://developer.thoughtindustries.com/api-tutorials/)
- [Authentication](https://academy.thoughtindustries.com/courses/api-keys)
- [GitHub Organization](https://github.com/thoughtindustries)
- [Webhooks](https://developer.thoughtindustries.com/)
- [Support](https://support.thoughtindustries.com/)
- [Integrations](https://www.thoughtindustries.com/partners/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
