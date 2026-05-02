# Lens (lens)

Lens is an open knowledge platform from Cambia that aggregates global scholarly works and patent records and exposes them through a REST API. The versioned API supports rich Elasticsearch-style queries, cursor pagination, and field projection across the full Lens scholarly and patent corpora, enabling research, science policy, technology landscape, and patent intelligence applications.

**APIs.json:** [apis.yml](apis.yml)

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
- **Modified:** 2026-04-28

## APIs

### Lens API

The Lens API exposes the full corpus of Lens scholarly works and patents via a REST interface. Search endpoints accept Elasticsearch-style query DSL via POST or simple Lucene query strings via GET, with cursor-based pagination, field projection, sorting, stemming controls, and patent family grouping. Authentication is via a bearer token issued from the Lens user profile.

- **Base URL:** https://api.lens.org
- **Documentation:** https://docs.api.lens.org/
- **Swagger UI:** https://api.lens.org/swagger-ui.html
- **OpenAPI:** [openapi/lens-openapi.yml](openapi/lens-openapi.yml)

#### Tags

- Scholarly, Patents, Search, Research

## Common Properties

- [Website](https://www.lens.org/)
- [Documentation](https://docs.api.lens.org/)
- [Plans](https://www.lens.org/lens/user/subscriptions)
- [About](https://www.lens.org/lens/about)
- [TermsOfService](https://www.lens.org/lens/terms-and-conditions)
- [PrivacyPolicy](https://www.lens.org/lens/privacy-policy)

## Maintainers

- **FN:** Kin Lane
- **Email:** kin@apievangelist.com
