# Nuitée (LiteAPI) (nuitee)

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
