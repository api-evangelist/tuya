# Tuya (tuya)

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
