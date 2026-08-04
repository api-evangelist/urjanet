# Urjanet (urjanet)

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

Urjanet (now part of Arcadia) is a utility-data aggregation platform that programmatically collects utility bill, statement, meter, and interval usage data from thousands of electricity, gas, water, waste, and telecom providers worldwide. Following Arcadia's 2022 acquisition, Urjanet's data access powers the Arcadia "Arc" / Utility Cloud platform, exposed through a REST API (base URL `https://api.urjanet.com`) for connecting utility credentials and retrieving normalized utility data. Pricing is sales-led and not publicly published.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/urjanet/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/urjanet/refs/heads/main/apis.yml)

> Note: "Urjanet" and "Arcadia" are related. Arcadia acquired Urjanet in 2022 and the utility-data API now lives under Arcadia's documentation. This entry profiles the utility-DATA aggregation API and is distinct from any separate consumer-facing Arcadia (arcadia.com) catalog entry.

## Tags

- Utility Data
- Energy
- Utility Bills
- Aggregation
- Meters
- Sustainability

## Timestamps

- **Created:** 2026-06-21

## APIs

### Urjanet Credentials & Connections API

Submit and manage end-user utility account login credentials so the platform can connect to utility providers and begin collecting data, and look up supported utility providers.

- **Human URL:** [https://docs.arcadia.com/v1.0-Utility-Cloud/reference/introduction](https://docs.arcadia.com/v1.0-Utility-Cloud/reference/introduction)
- **Base URL:** `https://api.urjanet.com`

#### Tags

- Credentials
- Connections
- Authentication

#### Properties

- [Documentation](https://docs.arcadia.com/v1.0-Utility-Cloud/docs/api-quick-start-guide)
- [API Reference](https://docs.arcadia.com/v1.0-Utility-Cloud/reference/introduction)
- [OpenAPI](openapi/urjanet-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/urjanet.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/urjanet.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Urjanet Statements & Bills API

Retrieve collected utility statements and bill documents, including billing periods, charges, and source bill PDFs, organized by account and site.

- **Human URL:** [https://docs.arcadia.com/v1.0-Utility-Cloud/reference/introduction](https://docs.arcadia.com/v1.0-Utility-Cloud/reference/introduction)
- **Base URL:** `https://api.urjanet.com`

#### Tags

- Statements
- Bills
- Invoices

#### Properties

- [API Reference](https://docs.arcadia.com/v1.0-Utility-Cloud/reference/introduction)
- [OpenAPI](openapi/urjanet-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/urjanet.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/urjanet.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Urjanet Meters API

List and manage utility meters and service points associated with connected accounts and sites.

- **Human URL:** [https://docs.arcadia.com/v1.0-Utility-Cloud/reference/introduction](https://docs.arcadia.com/v1.0-Utility-Cloud/reference/introduction)
- **Base URL:** `https://api.urjanet.com`

#### Tags

- Meters
- Service Points
- Accounts

#### Properties

- [API Reference](https://docs.arcadia.com/v1.0-Utility-Cloud/reference/introduction)
- [OpenAPI](openapi/urjanet-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/urjanet.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/urjanet.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Urjanet Usage Data API

Access normalized consumption and high-resolution interval (usage) data captured from utility meters and statements across electricity, gas, water, and other commodities.

- **Human URL:** [https://www.arcadia.com/platform/utility-bill-interval-data](https://www.arcadia.com/platform/utility-bill-interval-data)
- **Base URL:** `https://api.urjanet.com`

#### Tags

- Usage Data
- Interval Data
- Consumption

#### Properties

- [Documentation](https://www.arcadia.com/platform/utility-bill-interval-data)
- [OpenAPI](openapi/urjanet-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/urjanet.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/urjanet.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Urjanet Webhooks API

Configure webhook notifications for important platform events, such as new data becoming available or a credential status change that requires action.

- **Human URL:** [https://docs.arcadia.com/v1.0-Utility-Cloud/reference/introduction](https://docs.arcadia.com/v1.0-Utility-Cloud/reference/introduction)
- **Base URL:** `https://api.urjanet.com`

#### Tags

- Webhooks
- Events
- Notifications

#### Properties

- [API Reference](https://docs.arcadia.com/v1.0-Utility-Cloud/reference/introduction)
- [OpenAPI](openapi/urjanet-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/urjanet.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/urjanet.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/urjanet)
- [LinkedIn](https://www.linkedin.com/company/urjanet-inc)
- [Website](https://urjanet.com/)
- [Documentation](https://docs.arcadia.com/v1.0-Utility-Cloud/reference/introduction)
- [Plans](plans/urjanet-plans-pricing.yml)
- [Rate Limits](rate-limits/urjanet-rate-limits.yml)
- [Fin Ops](finops/urjanet-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
