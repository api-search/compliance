---
api_specs:
- filename: geocodio-lists-api-openapi.yml
  format: yaml
  label: Geocodio Lists API
  slug: geocodio-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/geocodio/openapi/geocodio-lists-api-openapi.yml
- filename: geocodio-distance-api-openapi.yml
  format: yaml
  label: Geocodio Distance API
  slug: geocodio-distance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/geocodio/openapi/geocodio-distance-api-openapi.yml
- filename: geocodio-distance-jobs-api-openapi.yml
  format: yaml
  label: Geocodio Distance Jobs API
  slug: geocodio-distance-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/geocodio/openapi/geocodio-distance-jobs-api-openapi.yml
- filename: geocodio-distance-matrix-api-openapi.yml
  format: yaml
  label: Geocodio Distance Matrix API
  slug: geocodio-distance-matrix-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/geocodio/openapi/geocodio-distance-matrix-api-openapi.yml
- filename: geocodio-geocode-api-openapi.yml
  format: yaml
  label: Geocodio Geocode API
  slug: geocodio-geocode-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/geocodio/openapi/geocodio-geocode-api-openapi.yml
- filename: geocodio-reverse-api-openapi.yml
  format: yaml
  label: Geocodio Reverse API
  slug: geocodio-reverse-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/geocodio/openapi/geocodio-reverse-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: audited annually
    report_access: on_request
    scope: Geocodio Enterprise platform
    text: 'SOC 2 Type II: audited annually'
    type: SOC 2 Type II audit
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: US health data, including BAA
    text: HIPAA/HITECH-compliant for US health data, including BAA
    type: HIPAA/HITECH compliance
  trust_center:
    url: https://www.geocod.io/security
frameworks:
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Geocodio
provenance_date: '2026-11-09'
provider_name: Geocodio
provider_slug: geocodio
slug: geocodio-compliance
source_date: '2026-11-09'
source_filename: geocodio-compliance.yml
source_heading: Compliance
source_page: https://www.geocod.io/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Geocodio\naid: geocodio\nurl: https://www.geocod.io/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/geocodio-trust-center.yml\ntrust_center:\n  url: https://www.geocod.io/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II audit\n  scope: Geocodio Enterprise platform\n  period: audited annually\n  issuer: null\n  report_access: on_request\n  text: 'SOC 2 Type II: audited annually'\n- framework: HIPAA\n  type: HIPAA/HITECH compliance\n  scope: US health data, including BAA\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA/HITECH-compliant for US health\
  \ data, including BAA\n"
source_yaml_url: https://artifacts.apis.io/geocodio/compliance/geocodio-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Geocodio's own page on 2026-11-09.
synthetic: false
tags:
- Geocoding
- Reverse Geocoding
- Addresses
- Data Append
- Census
- Geospatial
---
