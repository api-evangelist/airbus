# Airbus (airbus)
A European multinational aerospace corporation designing, manufacturing, and selling commercial aircraft, helicopters, defense, and space products. Through its Space Solutions / OneAtlas division Airbus publishes a developer API portal for satellite imagery, mapping, and elevation data.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/airbus/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=airbus-api-evangelist&utm_content=repo)

## Tags:

 - Aerospace, Defense, Manufacturing, Aviation, Earth Observation, Satellite Imagery

## Timestamps

- **Created:** 2026-05-05
- **Modified:** 2026-05-16

## APIs

### OneAtlas Living Library API
Subscription-based catalogue access to Airbus Pléiades, Pléiades Neo, and SPOT optical imagery for AOI search, preview, and streaming.

**Human URL:** [https://api.oneatlas.airbus.com/](https://api.oneatlas.airbus.com/)

#### Tags:
 - Earth Observation, Satellite Imagery, Living Library

### OneAtlas Pay-Per-Order Archives API
On-demand purchase of historical archive imagery from Airbus optical and radar constellations.

**Human URL:** [https://api.oneatlas.airbus.com/](https://api.oneatlas.airbus.com/)

#### Tags:
 - Earth Observation, Satellite Imagery, Archives

### OneAtlas Pay-Per-Order Tasking API
On-demand satellite tasking for new imagery acquisitions over a user-defined area of interest.

**Human URL:** [https://api.oneatlas.airbus.com/](https://api.oneatlas.airbus.com/)

#### Tags:
 - Earth Observation, Satellite Imagery, Tasking

### OneAtlas Basemap API
Global high-resolution basemap tile service derived from Airbus optical imagery.

**Human URL:** [https://api.oneatlas.airbus.com/](https://api.oneatlas.airbus.com/)

#### Tags:
 - Mapping, Basemap, Earth Observation

### OneAtlas Radar & Elevation API
Access to Airbus radar (SAR) imagery and elevation products including WorldDEM.

**Human URL:** [https://api.oneatlas.airbus.com/](https://api.oneatlas.airbus.com/)

#### Tags:
 - Radar, SAR, Elevation, DEM

## Common Properties

- [Website](https://www.airbus.com/)
- [Portal](https://api.oneatlas.airbus.com/)
- [AccountManagement](https://account.foundation.oneatlas.airbus.com/)
- [StatusPage](https://status.oneatlas.airbus.com/)

## Features

| Name | Description |
|------|-------------|
| Optical Imagery | Access to Pléiades, Pléiades Neo, and SPOT optical imagery via the Living Library catalogue and archive ordering. |
| Radar Imagery | SAR imagery from the TerraSAR-X / TanDEM-X constellation and from the new Radar Constellation. |
| Satellite Tasking | Pay-per-order tasking for new imagery acquisitions over a user-defined AOI. |
| Elevation Products | Global elevation models including WorldDEM derived from Airbus radar interferometry. |
| Basemap Tile Service | High-resolution global basemap tile service for embedding in GIS and web maps. |
| API Key + OAuth 2.0 | Authentication via per-user API key issued by the OneAtlas account portal with OAuth 2.0 access-token exchange. |

## Use Cases

| Name | Description |
|------|-------------|
| Land-Use / Land-Cover Monitoring | Periodic optical imagery used to monitor land-use change, deforestation, agriculture, and urban expansion. |
| Defense & Intelligence | Tasking and archive ordering of high-resolution optical and SAR imagery for defense and intelligence customers. |
| Infrastructure Monitoring | Repeat radar acquisitions for monitoring pipelines, dams, mines, and other linear infrastructure. |
| GIS Basemaps | Embedding the OneAtlas basemap into GIS workflows and web-mapping products. |
| Disaster Response | Rapid tasking and archive ordering after natural disasters to support response and recovery. |

## Authentication

| Name | Description |
|------|-------------|
| API Key | Per-user API key issued via the OneAtlas account portal. |
| OAuth 2.0 | OAuth 2.0 token exchange using the API key. |
| Account Onboarding | Production access requires an active commercial agreement and account on account.foundation.oneatlas.airbus.com. |

## Compliance

| Name | Description |
|------|-------------|
| GDPR | General Data Protection Regulation compliance for European customers. |
| Export Control | High-resolution imagery and radar products are subject to French / EU dual-use export controls (Regulation EU 2021/821) and U.S. EAR re-export rules where applicable. |
| ITAR / Dual-Use | Airbus Defense and Space products are governed by national defense-export regimes including ITAR equivalents and EU dual-use regulation. |

## Integrations

| Name | Description |
|------|-------------|
| ArcGIS | Esri ArcGIS integrations for streaming Airbus basemaps and imagery into the ArcGIS platform. |
| QGIS | QGIS plugins for connecting to Airbus tile and WMS / WMTS services. |
| AWS | Airbus distributes selected imagery products through AWS Marketplace and Earth on AWS. |
| Skywise | Aviation-data platform powered by Airbus and Palantir, exposed to airline operators via separate enterprise integration. |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
