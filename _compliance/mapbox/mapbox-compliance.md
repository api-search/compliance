---
api_specs:
- filename: mapbox-activity-api-openapi.yml
  format: yaml
  label: Mapbox Activity API
  slug: mapbox-activity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mapbox/openapi/mapbox-activity-api-openapi.yml
- filename: mapbox-mapbox-tiling-service-api-api-openapi.yml
  format: yaml
  label: Mapbox Tiling Service API
  slug: mapbox-mapbox-tiling-service-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mapbox/openapi/mapbox-mapbox-tiling-service-api-api-openapi.yml
- filename: mapbox-tilesets-api-openapi.yml
  format: yaml
  label: Mapbox Tilesets API
  slug: mapbox-tilesets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mapbox/openapi/mapbox-tilesets-api-openapi.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC3
    issuer: null
    period: '2026'
    report_access: unstated
    scope: null
    text: Mapbox - 2026 SOC 3 Type 2 Report pdf
    type: SOC 3 Type 2 report
  - framework: ISO9001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 9001
    type: badge
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: badge
  - framework: TISAX
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: TISAX
    type: badge
  trust_center:
    url: https://trust.mapbox.com/
frameworks:
- GDPR
- ISO9001
- SOC3
- TISAX
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Mapbox
provenance_date: '2026-11-10'
provider_name: Mapbox
provider_slug: mapbox
slug: mapbox-compliance
source_date: '2026-11-10'
source_filename: mapbox-compliance.yml
source_heading: Compliance
source_page: https://trust.mapbox.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Mapbox\naid: mapbox\nurl: https://trust.mapbox.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/mapbox-trust-center.yml\ntrust_center:\n  url: https://trust.mapbox.com/\nattestations:\n- framework: SOC3\n  type: SOC 3 Type 2 report\n  scope: null\n  period: '2026'\n  issuer: null\n  report_access: unstated\n  text: Mapbox - 2026 SOC 3 Type 2 Report pdf\n- framework: ISO9001\n  type: badge\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 9001\n- framework: GDPR\n  type: badge\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text:\
  \ GDPR\n- framework: TISAX\n  type: badge\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: TISAX\n"
source_yaml_url: https://artifacts.apis.io/mapbox/compliance/mapbox-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Mapbox's own page on 2026-11-10.
synthetic: false
tags:
- Mapping
- Maps
- Geospatial
- Location
- Geocoding
- Routing
---
