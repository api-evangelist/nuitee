# Nuitée (LiteAPI) (nuitee)

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

Nuitée is the travel technology company behind LiteAPI, a hotel-booking and distribution API platform. LiteAPI exposes a unified REST interface over 2M+ hotels for static content, real-time rates and availability, the prebook/book/cancel reservation flow, loyalty and vouchers, and booking webhooks, with a commission/markup revenue model and a free sandbox.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/nuitee/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/nuitee/refs/heads/main/apis.yml)

## Tags

- Travel
- Hotels
- Booking
- Distribution
- Hospitality

## Timestamps

- **Created:** 2026-06-25
- **Modified:** 2026-06-25

## APIs

### LiteAPI Hotel Data API

Static hotel content and supporting reference data - hotel lists and details, guest reviews, plus countries, cities, currencies, facilities, chains, hotel types, places, and IATA codes.

- **Human URL:** [https://docs.liteapi.travel/reference/api-endpoints-overview](https://docs.liteapi.travel/reference/api-endpoints-overview)
- **Base URL:** `https://api.liteapi.travel/v3.0`

#### Tags

- Hotels
- Static Content
- Reviews
- Search

#### Properties

- [Documentation](https://docs.liteapi.travel/reference/get_data-hotels)
- [API Reference](https://docs.liteapi.travel/reference/api-endpoints-overview)
- [OpenAPI](openapi/nuitee-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/nuitee.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nuitee.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### LiteAPI Rates Search API

Real-time room rates and availability across multiple hotels by hotel IDs, city, coordinates, place, or IATA code, with occupancy, currency, board type, refundability, and margin/markup commission controls.

- **Human URL:** [https://docs.liteapi.travel/reference/post_hotels-rates](https://docs.liteapi.travel/reference/post_hotels-rates)
- **Base URL:** `https://api.liteapi.travel/v3.0`

#### Tags

- Rates
- Availability
- Search
- Pricing

#### Properties

- [Documentation](https://docs.liteapi.travel/reference/post_hotels-rates)
- [API Reference](https://docs.liteapi.travel/reference/api-endpoints-overview)
- [OpenAPI](openapi/nuitee-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/nuitee.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nuitee.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### LiteAPI Booking API

The reservation lifecycle - prebook a selected rate to lock price and obtain a prebookId, confirm the booking with guest and payment details, retrieve booking details, list bookings, and cancel a booking.

- **Human URL:** [https://docs.liteapi.travel/reference/post_rates-prebook](https://docs.liteapi.travel/reference/post_rates-prebook)
- **Base URL:** `https://api.liteapi.travel/v3.0`

#### Tags

- Booking
- Prebook
- Reservations
- Cancellation

#### Properties

- [Documentation](https://docs.liteapi.travel/reference/post_rates-prebook)
- [API Reference](https://docs.liteapi.travel/reference/api-endpoints-overview)
- [OpenAPI](openapi/nuitee-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/nuitee.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nuitee.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### LiteAPI Loyalty and Vouchers API

Loyalty program configuration with cashback rates, guest loyalty point balances and redemption, and discount voucher creation, listing, updates, status toggling, and deletion.

- **Human URL:** [https://docs.liteapi.travel/reference/get_loyalties](https://docs.liteapi.travel/reference/get_loyalties)
- **Base URL:** `https://api.liteapi.travel/v3.0`

#### Tags

- Loyalty
- Cashback
- Vouchers
- Rewards

#### Properties

- [Documentation](https://docs.liteapi.travel/reference/get_loyalties)
- [API Reference](https://docs.liteapi.travel/reference/api-endpoints-overview)
- [OpenAPI](openapi/nuitee-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/nuitee.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nuitee.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### LiteAPI Webhooks

Event notifications that push booking lifecycle changes (such as new and cancelled reservations) to a subscriber-configured HTTPS callback URL.

- **Human URL:** [https://docs.liteapi.travel/docs/webhooks](https://docs.liteapi.travel/docs/webhooks)
- **Base URL:** `https://api.liteapi.travel/v3.0`

#### Tags

- Webhooks
- Events
- Notifications

#### Properties

- [Documentation](https://docs.liteapi.travel/docs/webhooks)
- [OpenAPI](openapi/nuitee-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

## Common Properties

- [GitHub Organization](https://github.com/liteapi-travel)
- [LinkedIn](https://www.linkedin.com/company/nuitee)
- [Website](https://www.liteapi.travel)
- [Documentation](https://docs.liteapi.travel)
- [Plans](plans/nuitee-plans-pricing.yml)
- [Rate Limits](rate-limits/nuitee-rate-limits.yml)
- [Fin Ops](finops/nuitee-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
