# Clear Capital (clear-capital)

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
