# Urjanet (urjanet)

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
