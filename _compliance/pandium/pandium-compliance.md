---
api_specs:
- filename: pandium-connector-calls-api-openapi.yml
  format: yaml
  label: Pandium Connector Calls API
  slug: pandium-connector-calls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pandium/openapi/pandium-connector-calls-api-openapi.yml
- filename: pandium-integrations-api-openapi.yml
  format: yaml
  label: Pandium Integrations API
  slug: pandium-integrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pandium/openapi/pandium-integrations-api-openapi.yml
- filename: pandium-runs-api-openapi.yml
  format: yaml
  label: Pandium Runs API
  slug: pandium-runs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pandium/openapi/pandium-runs-api-openapi.yml
- filename: pandium-tenant-metadata-api-openapi.yml
  format: yaml
  label: Pandium Tenant Metadata API
  slug: pandium-tenant-metadata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pandium/openapi/pandium-tenant-metadata-api-openapi.yml
- filename: pandium-tenants-api-openapi.yml
  format: yaml
  label: Pandium Tenants API
  slug: pandium-tenants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pandium/openapi/pandium-tenants-api-openapi.yml
- filename: pandium-builds-api-openapi.yml
  format: yaml
  label: Pandium Builds API
  slug: pandium-builds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pandium/openapi/pandium-builds-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Pandium security policies and procedures
    text: Our commitment to securing your data is backed by a SOC 2 Type 2 certification
    type: Type 2 certification
  trust_center:
    url: https://www.pandium.com/security
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Pandium
provenance_date: '2026-11-10'
provider_name: Pandium
provider_slug: pandium
slug: pandium-compliance
source_date: '2026-11-10'
source_filename: pandium-compliance.yml
source_heading: Compliance
source_page: https://www.pandium.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Pandium\naid: pandium\nurl: https://www.pandium.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/pandium-trust-center.yml\ntrust_center:\n  url: https://www.pandium.com/security\nattestations:\n- framework: SOC2\n  type: Type 2 certification\n  scope: Pandium security policies and procedures\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Our commitment to securing your data is backed by a SOC 2 Type 2 certification\n"
source_yaml_url: https://artifacts.apis.io/pandium/compliance/pandium-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Pandium's own page on 2026-11-10.
synthetic: false
tags:
- B2B
- Hub
- Integration
- Workflows
- iPaaS
---
