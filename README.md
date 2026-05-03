# Salesforce Net Zero Cloud

The Salesforce Net Zero Cloud API enables organizations to track, analyze, and report on their carbon emissions and sustainability data. It provides programmatic access to environmental data, carbon accounting, and ESG reporting capabilities including Scope 1, 2, and 3 emissions, energy consumption, waste management, water usage, and sustainability goal management.

**URL:** https://www.salesforce.com/products/net-zero-cloud/overview/

**Tags:** Carbon Accounting, Carbon Emissions, Climate, Environmental, ESG, Net Zero, Sustainability

## APIs

### Net Zero Cloud REST API

REST API for managing carbon emissions data, sustainability records, and environmental impact tracking within Net Zero Cloud.

- **Base URL:** https://yourinstance.my.salesforce.com/services/data/v59.0/
- **Documentation:** https://developer.salesforce.com/docs/atlas.en-us.netzero_api.meta/netzero_api/
- **OpenAPI:** [salesforce-net-zero-cloud-rest-api-openapi.yml](openapi/salesforce-net-zero-cloud-rest-api-openapi.yml)
- **Authentication:** https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/intro_oauth_and_connected_apps.htm

### Carbon Accounting API

API endpoints for carbon footprint calculations, emission factors, and sustainability metrics aggregation.

- **Documentation:** https://developer.salesforce.com/docs/atlas.en-us.netzero_api.meta/netzero_api/

### Sustainability Data API

API for accessing and managing sustainability data including energy consumption, waste management, water usage, and renewable energy tracking.

- **Documentation:** https://developer.salesforce.com/docs/atlas.en-us.netzero_api.meta/netzero_api/

## Common Resources

| Type | URL |
|------|-----|
| Developer Portal | https://developer.salesforce.com/ |
| Getting Started | https://trailhead.salesforce.com/content/learn/modules/net-zero-cloud-basics |
| Authentication | https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/intro_oauth_and_connected_apps.htm |
| Status | https://status.salesforce.com/ |
| Terms of Service | https://www.salesforce.com/company/legal/agreements/ |
| Privacy Policy | https://www.salesforce.com/company/privacy/ |
| Trailhead Learning | https://trailhead.salesforce.com/content/learn/trails/get-started-with-net-zero-cloud |
| Release Notes | https://help.salesforce.com/s/articleView?id=release-notes.salesforce_release_notes.htm |
| Support | https://help.salesforce.com/ |
| GitHub Organization | https://github.com/salesforce |

## Artifacts

### OpenAPI Specifications

| Spec | Description |
|------|-------------|
| [salesforce-net-zero-cloud-rest-api-openapi.yml](openapi/salesforce-net-zero-cloud-rest-api-openapi.yml) | Net Zero Cloud REST API — emissions, energy, goals, waste, and water |

### Spectral Rules

| Ruleset | Description |
|---------|-------------|
| [salesforce-net-zero-cloud-rules.yml](rules/salesforce-net-zero-cloud-rules.yml) | Spectral rules enforcing Net Zero Cloud API conventions |

### Capabilities

| Capability | Description |
|------------|-------------|
| [carbon-accounting.yaml](capabilities/carbon-accounting.yaml) | Unified workflow capability for carbon accounting and ESG reporting (15 tools) |

**Shared Definitions:**

| Shared | Description |
|--------|-------------|
| [net-zero-cloud-rest-api.yaml](capabilities/shared/net-zero-cloud-rest-api.yaml) | Salesforce Net Zero Cloud REST API consumed definition |

### JSON Schemas

| Schema | Description |
|--------|-------------|
| [salesforce-net-zero-cloud-carbon-emission-schema.json](json-schema/salesforce-net-zero-cloud-carbon-emission-schema.json) | Schema for Carbon Emission records (Scope 1, 2, 3) |
| [salesforce-net-zero-cloud-sustainability-goal-schema.json](json-schema/salesforce-net-zero-cloud-sustainability-goal-schema.json) | Schema for Sustainability Goal records |

### JSON Structures

| Structure | Description |
|-----------|-------------|
| [salesforce-net-zero-cloud-carbon-emission-structure.json](json-structure/salesforce-net-zero-cloud-carbon-emission-structure.json) | Structural documentation for the Carbon Emission resource |

### JSON-LD Context

| Context | Description |
|---------|-------------|
| [salesforce-net-zero-cloud-context.jsonld](json-ld/salesforce-net-zero-cloud-context.jsonld) | JSON-LD context mapping Net Zero Cloud vocabulary to ontologies |

### Examples

| Example | Description |
|---------|-------------|
| [salesforce-net-zero-cloud-create-carbon-emission-example.json](examples/salesforce-net-zero-cloud-create-carbon-emission-example.json) | Example for creating a Scope 1 carbon emission record |
| [salesforce-net-zero-cloud-list-sustainability-goals-example.json](examples/salesforce-net-zero-cloud-list-sustainability-goals-example.json) | Example for listing sustainability goals |

### Vocabulary

| Vocabulary | Description |
|------------|-------------|
| [salesforce-net-zero-cloud-vocabulary.yml](vocabulary/salesforce-net-zero-cloud-vocabulary.yml) | Domain vocabulary for carbon accounting and ESG concepts |

## Maintainers

- Kin Lane (kin@apievangelist.com)
