# Silverpop

Silverpop (now Acoustic, formerly IBM Watson Campaign Automation) is a digital marketing automation platform offering email marketing, marketing automation, mobile messaging, and campaign management. The platform provides XML and REST APIs for list management, contact data, campaign execution, transactional messaging, and reporting.

- **Website:** https://www.goacoustic.com
- **Developer Portal:** https://developer.goacoustic.com
- **API Documentation:** https://developer.goacoustic.com/acoustic-campaign/reference/overview
- **GitHub:** https://github.com/Silverpop
- **Node.js SDK:** https://github.com/Silverpop/node-engage

## API

The Silverpop/Acoustic Campaign REST API is available at:
- **US:** https://api-campaign-us-1.goacoustic.com
- **EU:** https://api-campaign-eu-1.goacoustic.com

Authentication uses OAuth 2.0 with client credentials (client_id, client_secret, refresh_token).

## OpenAPI Specs

| Name | Description |
|---|---|
| [Silverpop Engage API](openapi/silverpop-openapi.yml) | REST API covering contacts, campaigns, transactional messaging, reporting, and programs |

## Capabilities

### Shared Definitions

| File | Description |
|---|---|
| [silverpop](capabilities/shared/silverpop.yaml) | Silverpop/Acoustic Campaign REST API consumed definition |

### Workflow Capabilities

| Capability | Description |
|---|---|
| [Email Marketing](capabilities/email-marketing.yaml) | End-to-end email marketing: contacts, campaigns, scheduling, reporting, automation |

## Rules

| Name | Description |
|---|---|
| [Silverpop Spectral Rules](rules/silverpop-rules.yml) | Spectral ruleset enforcing Silverpop API conventions |

## JSON Schema

| Name | Description |
|---|---|
| [Contact Schema](json-schema/silverpop-contact-schema.json) | Schema for the Silverpop Contact resource |

## JSON Structure

| Name | Description |
|---|---|
| [Contact Structure](json-structure/silverpop-contact-structure.json) | Structural documentation for Contact, Database, and Campaign resources |

## JSON-LD

| Name | Description |
|---|---|
| [Silverpop Context](json-ld/silverpop-context.jsonld) | JSON-LD context mapping Silverpop terms to schema.org |

## Examples

| Name | Description |
|---|---|
| [Add Contact](examples/silverpop-add-contact-example.json) | Example: adding a contact to a database |

## Vocabulary

| Name | Description |
|---|---|
| [Silverpop Vocabulary](vocabulary/silverpop-vocabulary.yml) | Domain terms for the email marketing platform |

## Maintainers

**API Evangelist**
- URL: https://apievangelist.com
- Email: info@apievangelist.com
