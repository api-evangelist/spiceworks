# Spiceworks

Spiceworks (https://community.spiceworks.com/) is an IT professional community and network providing tools for IT management, including a cloud-based help desk, network monitoring, and IT asset inventory. The Spiceworks Cloud Apps API enables developers to build integrated applications within the Spiceworks platform, accessing Help Desk ticketing, device inventory, and user management data through a JavaScript SDK with OAuth-based authentication.

## APIs

### Spiceworks Cloud Apps API

The Spiceworks Cloud Apps API provides a JavaScript SDK for building integrated apps within the Spiceworks platform, with access to Help Desk ticketing data, device inventory, and user information. Apps are embedded within the Spiceworks UI and communicate through a postMessage-based bridge.

- **Documentation:** https://spiceworks.github.io/developers.spiceworks.com/documentation/cloud-apps/
- **Authentication:** https://spiceworks.github.io/developers.spiceworks.com/documentation/cloud-apps/authentication/
- **Help Desk Reference:** https://spiceworks.github.io/developers.spiceworks.com/documentation/cloud-apps/reference/helpdesk/
- **SDK:** https://github.com/spiceworks/spiceworks-js-sdk
- **OpenAPI:** [openapi/spiceworks-cloud-apps-openapi.yml](openapi/spiceworks-cloud-apps-openapi.yml)

## OpenAPI Specifications

| API | File |
|-----|------|
| Spiceworks Cloud Apps API | [openapi/spiceworks-cloud-apps-openapi.yml](openapi/spiceworks-cloud-apps-openapi.yml) |

## Spectral Rules

| Ruleset | File |
|---------|------|
| Spiceworks Rules | [rules/spiceworks-rules.yml](rules/spiceworks-rules.yml) |

## Capabilities

| Capability | Description | File |
|------------|-------------|------|
| IT Management | Unified IT help desk and inventory workflow for technicians | [capabilities/it-management.yaml](capabilities/it-management.yaml) |

### Shared Definitions

| API | File |
|-----|------|
| Cloud Apps | [capabilities/shared/cloud-apps.yaml](capabilities/shared/cloud-apps.yaml) |

## JSON Schema

| Schema | File |
|--------|------|
| Help Desk Ticket | [json-schema/spiceworks-ticket-schema.json](json-schema/spiceworks-ticket-schema.json) |
| Inventory Device | [json-schema/spiceworks-device-schema.json](json-schema/spiceworks-device-schema.json) |

## JSON Structure

| Structure | File |
|-----------|------|
| Help Desk Ticket | [json-structure/spiceworks-ticket-structure.json](json-structure/spiceworks-ticket-structure.json) |

## JSON-LD

| Context | File |
|---------|------|
| Spiceworks Context | [json-ld/spiceworks-context.jsonld](json-ld/spiceworks-context.jsonld) |

## Examples

| Example | File |
|---------|------|
| List Tickets | [examples/spiceworks-list-tickets-example.json](examples/spiceworks-list-tickets-example.json) |
| Get Device | [examples/spiceworks-get-device-example.json](examples/spiceworks-get-device-example.json) |

## Vocabulary

| Vocabulary | File |
|------------|------|
| Spiceworks Vocabulary | [vocabulary/spiceworks-vocabulary.yml](vocabulary/spiceworks-vocabulary.yml) |

## Links

- **Community:** https://community.spiceworks.com/
- **Developer Portal:** https://spiceworks.github.io/developers.spiceworks.com/
- **Help Center:** https://community.spiceworks.com/help
- **Blog:** https://community.spiceworks.com/blog
- **GitHub:** https://github.com/spiceworks
- **LinkedIn:** https://www.linkedin.com/company/spiceworks
- **Terms of Service:** https://community.spiceworks.com/legal/terms
- **Privacy Policy:** https://community.spiceworks.com/legal/privacy
