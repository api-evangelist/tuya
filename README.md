# Tuya (tuya)

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

Tuya Smart is a global leading AI cloud platform service provider (NYSE: TUYA; HKEX: 2391) that enables IoT device manufacturers, solution providers, and app developers to build smart home and industrial IoT applications. The platform provides APIs for device management, smart home management, scene automation, data analytics, and industry-specific integrations across smart home, energy, security, and industrial verticals. Tuya operates six global data centers and handles over 100 million concurrent requests.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/tuya/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/tuya/refs/heads/main/apis.yml)

## Scope

- **Access:** 3rd-Party

## Tags

- IoT
- Smart Home
- Devices
- Cloud Platform
- Automation
- Industrial IoT
- Device Management

## Timestamps

- **Created:** 2025-03-01
- **Modified:** 2026-05-19

## APIs

### Tuya Device Management API

The Tuya Device Management API provides endpoints to query, control, and manage IoT devices registered to a Tuya cloud project. Capabilities include device information retrieval, factory reset, device renaming, sub-device listing, operation log queries, and user-device association management.

- **Human URL:** [https://developer.tuya.com/en/docs/cloud/device-management?id=K9g6rfntdz78a](https://developer.tuya.com/en/docs/cloud/device-management?id=K9g6rfntdz78a)
- **Base URL:** `https://openapi.tuyaus.com`

#### Tags

- Devices
- IoT
- Device Management

#### Properties

- [Documentation](https://developer.tuya.com/en/docs/cloud/device-management?id=K9g6rfntdz78a)
- [Getting Started](https://developer.tuya.com/en/docs/iot/quick-start1?id=K95ztz9u9t89n)
- [Postman Collection](collections/tuya-device-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tuya-device-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tuya Smart Home API

The Tuya Smart Home API provides management capabilities for smart home deployments, including home and room management, device grouping, scene automation (tap-to-run and automation rules), member management, and data services. Enables developers to build full-featured smart home applications.

- **Human URL:** [https://developer.tuya.com/en/docs/cloud/smart_home_paas?id=Kakujwbddm7fv](https://developer.tuya.com/en/docs/cloud/smart_home_paas?id=Kakujwbddm7fv)
- **Base URL:** `https://openapi.tuyaus.com`

#### Tags

- Smart Home
- IoT
- Automation
- Scene Management

#### Properties

- [Documentation](https://developer.tuya.com/en/docs/cloud/smart_home_paas?id=Kakujwbddm7fv)
- [Postman Collection](collections/tuya-device-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tuya-device-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tuya Authorization API

The Tuya Authorization API handles authentication for cloud-to-cloud integrations. Supports HMAC-SHA256 request signing using Access ID and Access Secret credentials. Provides token management endpoints for obtaining, refreshing, and revoking access tokens. Supports both cloud authorization (server-to-server) and app authorization (user-scoped) modes.

- **Human URL:** [https://developer.tuya.com/en/docs/iot/guide-explanation?id=Ke0wpiw0dwxun](https://developer.tuya.com/en/docs/iot/guide-explanation?id=Ke0wpiw0dwxun)
- **Base URL:** `https://openapi.tuyaus.com`

#### Tags

- Authentication
- Authorization
- Tokens

#### Properties

- [Documentation](https://developer.tuya.com/en/docs/iot/guide-explanation?id=Ke0wpiw0dwxun)
- [API Reference](https://developer.tuya.com/en/docs/iot/api-reference?id=Ka7qb7vhber64)
- [Postman Collection](collections/tuya-device-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tuya-device-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tuya Industry API

The Tuya Industry API provides enterprise IoT capabilities for non-consumer deployments including industrial device registration, device management, status queries, device control, user management, and asset management. Designed for B2B scenarios in real estate, energy, manufacturing, and facilities management.

- **Human URL:** [https://developer.tuya.com/en/docs/cloud](https://developer.tuya.com/en/docs/cloud)
- **Base URL:** `https://openapi.tuyaus.com`

#### Tags

- Industrial IoT
- Enterprise
- Asset Management

#### Properties

- [Documentation](https://developer.tuya.com/en/docs/cloud)
- [Postman Collection](collections/tuya-device-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tuya-device-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/tuya-smart)
- [Website](https://developer.tuya.com/en/)
- [Documentation](https://developer.tuya.com/en/docs/cloud/)
- [Sign Up](https://auth.tuya.com/)
- [Getting Started](https://developer.tuya.com/en/docs/iot/quick-start1?id=K95ztz9u9t89n)
- [A P I  Explorer](https://developer.tuya.com/en/docs/cloud)
- [GitHub Organization](https://github.com/tuya)
- [Authentication](https://developer.tuya.com/en/docs/iot/guide-explanation?id=Ke0wpiw0dwxun)
- [Terms of Service](https://developer.tuya.com/en/docs/iot/compliance?id=Ka9t0qa3qihn3)
- [Portal](https://iot.tuya.com/)
- [OpenAPI](openapi/tuya-device-management-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/tuya-device-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/tuya-command-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/tuya-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Spectral  Rules](rules/tuya-rules.yml)
- [Vocabulary](vocabulary/tuya-vocabulary.yml)
- [M C P Server](https://github.com/tuya/tuya-mcp-sdk)
- [Agent Skill](https://github.com/tuya/tuya-openclaw-skills)
- [L L Ms Txt](https://developer.tuya.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
