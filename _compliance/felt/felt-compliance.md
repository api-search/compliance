---
api_specs:
- filename: felt-comments-api-openapi.yml
  format: yaml
  label: Felt Comments API
  slug: felt-comments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/felt/openapi/felt-comments-api-openapi.yml
- filename: felt-elements-api-openapi.yml
  format: yaml
  label: Felt Elements API
  slug: felt-elements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/felt/openapi/felt-elements-api-openapi.yml
- filename: felt-embed-tokens-api-openapi.yml
  format: yaml
  label: Felt Embed Tokens API
  slug: felt-embed-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/felt/openapi/felt-embed-tokens-api-openapi.yml
- filename: felt-layer-exports-api-openapi.yml
  format: yaml
  label: Felt Layer Exports API
  slug: felt-layer-exports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/felt/openapi/felt-layer-exports-api-openapi.yml
- filename: felt-layer-library-api-openapi.yml
  format: yaml
  label: Felt Layer Library API
  slug: felt-layer-library-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/felt/openapi/felt-layer-library-api-openapi.yml
- filename: felt-layer-uploads-api-openapi.yml
  format: yaml
  label: Felt Layer Uploads API
  slug: felt-layer-uploads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/felt/openapi/felt-layer-uploads-api-openapi.yml
- filename: felt-layers-api-openapi.yml
  format: yaml
  label: Felt Layers API
  slug: felt-layers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/felt/openapi/felt-layers-api-openapi.yml
- filename: felt-maps-api-openapi.yml
  format: yaml
  label: Felt Maps API
  slug: felt-maps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/felt/openapi/felt-maps-api-openapi.yml
- filename: felt-projects-api-openapi.yml
  format: yaml
  label: Felt Projects API
  slug: felt-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/felt/openapi/felt-projects-api-openapi.yml
- filename: felt-sources-api-openapi.yml
  format: yaml
  label: Felt Sources API
  slug: felt-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/felt/openapi/felt-sources-api-openapi.yml
- filename: felt-users-api-openapi.yml
  format: yaml
  label: Felt Users API
  slug: felt-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/felt/openapi/felt-users-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: Felt service
    text: Felt is SOC 2 Type 2 and GDPR compliant, and the SOC 2 report is available on request.
    type: SOC 2 Type 2 report
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: Felt
    text: Felt is SOC 2 Type 2 and GDPR compliant
    type: compliance statement
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: personal information
    text: Felt also complies with applicable data protection laws like CCPA.
    type: compliance statement
  trust_center:
    url: https://felt.com/security
frameworks:
- CCPA
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Felt
provenance_date: '2026-11-09'
provider_name: Felt
provider_slug: felt
slug: felt-compliance
source_date: '2026-11-09'
source_filename: felt-compliance.yml
source_heading: Compliance
source_page: https://felt.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Felt\naid: felt\nurl: https://felt.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/felt-trust-center.yml\ntrust_center:\n  url: https://felt.com/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 report\n  scope: Felt service\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Felt is SOC 2 Type 2 and GDPR compliant, and the SOC 2 report is available on request.\n- framework: GDPR\n  type: compliance statement\n  scope: Felt\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Felt is SOC 2 Type 2 and GDPR compliant\n- framework: CCPA\n  type:\
  \ compliance statement\n  scope: personal information\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Felt also complies with applicable data protection laws like CCPA.\n"
source_yaml_url: https://artifacts.apis.io/felt/compliance/felt-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Felt's own page on 2026-11-09.
synthetic: false
tags:
- Maps
- GIS
- Geospatial
- Collaborative
- Mapping
- Layers
- Embeddings
---
