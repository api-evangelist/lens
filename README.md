# Lens (lens)

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

Lens is an open knowledge platform from Cambia that aggregates global scholarly works and patent records and exposes them through a REST API. The versioned API supports rich Elasticsearch-style queries, cursor pagination, and field projection across the full Lens scholarly and patent corpora, enabling research, science policy, technology landscape, and patent intelligence applications.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/lens/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/lens/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Scholarly
- Patents
- Research
- Science
- Open Data

## Timestamps

- **Created:** 2025-02-06
- **Modified:** 2026-05-19

## APIs

### Lens API

The Lens API exposes the full corpus of Lens scholarly works and patents via a REST interface. Search endpoints accept Elasticsearch-style query DSL via POST or simple Lucene query strings via GET, with cursor-based pagination, field projection, sorting, stemming controls, and patent family grouping. Authentication is via a bearer token issued from the Lens user profile.

- **Human URL:** [https://docs.api.lens.org/](https://docs.api.lens.org/)
- **Base URL:** `https://api.lens.org`

#### Tags

- Scholarly
- Patents
- Search
- Research

#### Properties

- [Documentation](https://docs.api.lens.org/)
- [Swagger U I](https://api.lens.org/swagger-ui.html)
- [OpenAPI](openapi/lens-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/lens.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/lens.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/lensapp)
- [LinkedIn](https://www.linkedin.com/company/k8slens)
- [Website](https://www.lens.org/)
- [Documentation](https://docs.api.lens.org/)
- [Plans](https://www.lens.org/lens/user/subscriptions)
- [About](https://www.lens.org/lens/about)
- [Terms of Service](https://www.lens.org/lens/terms-and-conditions)
- [Privacy Policy](https://www.lens.org/lens/privacy-policy)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
