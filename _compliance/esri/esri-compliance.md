---
api_specs:
- filename: esri-auth-api-openapi.yml
  format: yaml
  label: Esri Auth API
  slug: esri-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/esri/openapi/esri-auth-api-openapi.yml
- filename: esri-geocoding-api-openapi.yml
  format: yaml
  label: Esri Geocoding API
  slug: esri-geocoding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/esri/openapi/esri-geocoding-api-openapi.yml
- filename: esri-routing-api-openapi.yml
  format: yaml
  label: Esri Routing API
  slug: esri-routing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/esri/openapi/esri-routing-api-openapi.yml
- filename: esri-places-api-openapi.yml
  format: yaml
  label: Esri Places API
  slug: esri-places-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/esri/openapi/esri-places-api-openapi.yml
- filename: esri-portal-api-openapi.yml
  format: yaml
  label: Esri Portal API
  slug: esri-portal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/esri/openapi/esri-portal-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: FedRAMP
    issuer: null
    period: null
    report_access: unstated
    scope: Online Services from Esri
    text: the third party validated assurance of industry-leading FedRAMP moderate authorization and ISO 27001 certification
    type: authorization
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: Online Services from Esri
    text: ISO 27001 certification
    type: certification
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Esri corporate select internal systems only; does NOT cover products or customer datasets
    text: Esri corporate maintains a SOC 2 certification scoped to select internal systems that does NOT cover the assurance of our products, their operation, or customer datasets within Esri products.
    type: certification
  trust_center:
    url: https://trust.arcgis.com/en/compliance/compliance.htm
frameworks:
- FedRAMP
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Esri
provenance_date: '2026-11-09'
provider_name: Esri
provider_slug: esri
slug: esri-compliance
source_date: '2026-11-09'
source_filename: esri-compliance.yml
source_heading: Compliance
source_page: https://trust.arcgis.com/en/compliance/compliance.htm
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Esri\naid: esri\nurl: https://trust.arcgis.com/en/compliance/compliance.htm\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.arcgis.com/en/compliance/compliance.htm\nattestations:\n- framework: FedRAMP\n  type: authorization\n  scope: Online Services from Esri\n  period: null\n  issuer: null\n  report_access: unstated\n  text: the third party validated assurance of industry-leading FedRAMP moderate authorization and ISO 27001 certification\n- framework: ISO27001\n  type: certification\n  scope: Online Services from Esri\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001\
  \ certification\n- framework: SOC2\n  type: certification\n  scope: Esri corporate select internal systems only; does NOT cover products or customer datasets\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Esri corporate maintains a SOC 2 certification scoped to select internal systems that does NOT cover the\n    assurance of our products, their operation, or customer datasets within Esri products.\n"
source_yaml_url: https://artifacts.apis.io/esri/compliance/esri-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Esri's own page on 2026-11-09.
synthetic: false
tags:
- Geographic
- Geospatial
- GIS
- Location
- Mapping
- Maps
- Spatial Analysis
- Geocoding
- Routing
---
