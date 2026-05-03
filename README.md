# Thermal Power

Thermal power generation data APIs providing access to plant-level operational metrics, fuel consumption, heat rates, and generating capacity for coal, natural gas, petroleum, and nuclear power plants. Primary data source is the U.S. Energy Information Administration (EIA) Open Data API.

**URL:** [https://raw.githubusercontent.com/api-evangelist/thermal-power/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/thermal-power/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Energy
- Thermal Power
- Power Generation
- Electricity
- Coal
- Natural Gas
- Nuclear

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-03

## APIs

### Thermal Power API

The Thermal Power API provides access to thermal power generation data including plant-level operational metrics, fuel consumption, heat rate performance, and capacity utilization for coal, natural gas, petroleum, and nuclear generation assets.

**Human URL:** [https://www.eia.gov/opendata/](https://www.eia.gov/opendata/)

**Base URL:** https://api.eia.gov/v2

#### Tags

- Energy
- Thermal Power
- Power Generation
- Electricity
- EIA
- Fossil Fuels
- Nuclear

#### Operations

| Method | Path | Summary |
|--------|------|---------|
| GET | /electricity/electric-power-operational-data/data | Get Electric Power Operational Data |
| GET | /electricity/facility-fuel/data | Get Facility Fuel Data |
| GET | /electricity/operating-generator-capacity/data | Get Operating Generator Capacity |
| GET | /electricity/rto/fuel-type-data/data | Get RTO Fuel Type Data |

#### Properties

- [Documentation](https://www.eia.gov/opendata/documentation.php)
- [OpenAPI](openapi/thermal-power-openapi.yml)
- [JSON Schema](json-schema/thermal-power-plant-schema.json)
- [JSON-LD](json-ld/thermal-power-context.jsonld)
- [JSON Structure](json-structure/thermal-power-structure.json)
- [Spectral Rules](rules/thermal-power-rules.yml)
- [Capabilities](capabilities/thermal-power-monitoring.yaml)
- [Vocabulary](vocabulary/thermal-power-vocabulary.yml)

## Artifacts

### OpenAPI Specs

- [Thermal Power API](openapi/thermal-power-openapi.yml)

### JSON Schemas

- [Thermal Power Plant Record](json-schema/thermal-power-plant-schema.json)

### JSON Structure

- [Thermal Power Structure](json-structure/thermal-power-structure.json)

### JSON-LD

- [Thermal Power Context](json-ld/thermal-power-context.jsonld)

### Examples

- [Get Electric Power Operational Data](examples/thermal-power-get-electric-power-operational-data-example.json)
- [Get Facility Fuel Data](examples/thermal-power-get-facility-fuel-data-example.json)

### Spectral Rules

- [Thermal Power Rules](rules/thermal-power-rules.yml)

### Capabilities

- [Thermal Power Monitoring](capabilities/thermal-power-monitoring.yaml)

**Shared Definitions:**

- [Thermal Power API](capabilities/shared/thermal-power-api.yaml)

### Vocabulary

- [Thermal Power Vocabulary](vocabulary/thermal-power-vocabulary.yml)

## Common Properties

- [EIA Open Data API](https://www.eia.gov/opendata/)
- [EIA API Documentation](https://www.eia.gov/opendata/documentation.php)
- [EIA API Registration](https://www.eia.gov/opendata/register.php)
- [EIA API Browser](https://www.eia.gov/opendata/browser/)
- [EIA Developer Resources](https://www.eia.gov/developer/)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
