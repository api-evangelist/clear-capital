# Clear Capital (clear-capital)

Clear Capital is a real-estate valuation and property data platform serving mortgage lenders, investors, and capital markets. Its developer surface is exposed through two sales-led REST products - the Property Analytics API (ClearAVM automated valuations, comparables ranked by ClearRank, property characteristics, and market trends) and the Property Valuation API (ordering and fulfillment of appraisal and valuation products such as Hybrid/Desktop appraisal, BPO, CDA, and UDC). Access is gated behind a commercial agreement; full reference docs live at docs.api.clearcapital.com.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/clear-capital/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/clear-capital/refs/heads/main/apis.yml)

## Tags

- Real Estate
- Property Data
- Valuation
- AVM
- Appraisal
- Mortgage

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Clear Capital ClearAVM / Valuation API

Lending-grade automated valuation model (ClearAVM) and Rental AVM delivered over a RESTful interface, returning a point value estimate, value certainty, and supporting analytics for a subject property. Interactive ClearAVM accepts property condition as an input. Specific request and response schemas are documented behind Clear Capital's gated developer portal and are not reproduced here.

- **Human URL:** [https://www.clearcapital.com/analytics/clear-avm/](https://www.clearcapital.com/analytics/clear-avm/)
- **Base URL:** `https://api.clearcapital.com`

#### Tags

- AVM
- Valuation
- ClearAVM

#### Properties

- [Documentation](https://docs.api.clearcapital.com/introduction)
- [API Reference](https://www.clearcapital.com/analytics/clear-avm/)
- [OpenAPI](openapi/clear-capital-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/clear-capital.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/clear-capital.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Clear Capital Property Data API

Property characteristics (bedrooms, bathrooms, gross living area, photos), home price index and historical trends, sales and listing history, and owner and tax history, sourced from Clear Capital's property dataset covering nearly every U.S. address and updated hourly. Delivered through the Property Analytics API.

- **Human URL:** [https://www.clearcapital.com/products/property-analytics-api/](https://www.clearcapital.com/products/property-analytics-api/)
- **Base URL:** `https://api.clearcapital.com`

#### Tags

- Property Data
- Characteristics
- Market Trends

#### Properties

- [Documentation](https://docs.api.clearcapital.com/introduction)
- [API Reference](https://www.clearcapital.com/products/property-analytics-api/)
- [OpenAPI](openapi/clear-capital-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/clear-capital.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/clear-capital.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Clear Capital Comparables (Comps) API

Comparable sales and comparable rentals for a subject property, ranked by Clear Capital's proprietary ClearRank algorithm, returned as part of a customizable Property Analytics valuation report. Exact request and response schemas are documented in the gated developer portal.

- **Human URL:** [https://www.clearcapital.com/products/property-analytics-api/](https://www.clearcapital.com/products/property-analytics-api/)
- **Base URL:** `https://api.clearcapital.com`

#### Tags

- Comparables
- Comps
- ClearRank

#### Properties

- [Documentation](https://docs.api.clearcapital.com/introduction)
- [API Reference](https://www.clearcapital.com/products/property-analytics-api/)
- [OpenAPI](openapi/clear-capital-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/clear-capital.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/clear-capital.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Clear Capital Appraisal & Orders API

Ordering and fulfillment of Clear Capital valuation products via the Property Valuation API - Hybrid Appraisal, Desktop Appraisal (GSE 1004 Desktop/70D), Broker Price Opinion (BPO), Collateral Desktop Analysis (CDA), and Universal Data Collection (UDC) - with real-time fulfillment milestone event notifications. Endpoint paths and payloads are documented behind Clear Capital's gated developer portal.

- **Human URL:** [https://www.clearcapital.com/products/property-valuation-api/](https://www.clearcapital.com/products/property-valuation-api/)
- **Base URL:** `https://api.clearcapital.com`

#### Tags

- Appraisal
- Orders
- Fulfillment
- BPO

#### Properties

- [Documentation](https://docs.api.clearcapital.com/introduction)
- [API Reference](https://www.clearcapital.com/products/property-valuation-api/)
- [OpenAPI](openapi/clear-capital-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/clear-capital.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/clear-capital.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/clearcapital)
- [LinkedIn](https://www.linkedin.com/company/clear-capital)
- [Website](https://www.clearcapital.com)
- [Documentation](https://docs.api.clearcapital.com/introduction)
- [Plans](plans/clear-capital-plans-pricing.yml)
- [Rate Limits](rate-limits/clear-capital-rate-limits.yml)
- [Fin Ops](finops/clear-capital-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
